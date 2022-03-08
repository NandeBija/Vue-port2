<template>
  <section id="cont2">
    <div class="contact">
      <h1 class="h1">Get in touch</h1>
      <h2 class="h2">
        <span style="border-bottom: 3px solid red">Contact</span>
      </h2>
      <div class="container">
        <div class="row" id="form">
          <div class="col" id="left">
            <div class="left-container">
              <div class="left-inner-container">
                <h2>Let's Chat!</h2>
                <p>
                  Whether you have a question, want to start a project or simply
                  want to connect.
                </p>
                <br />
                <p>Feel free to send me a message in the contact form</p>
              </div>
              <div class="address">
                <div>
                  <i class="material-icons">email</i>
                  <p>@mail.com</p>
                </div>
                <div>
                  <i class="material-icons">map</i>
                  <p>Address</p>
                </div>
                <div>
                  <i class="material-icons">phone</i>
                  <p>+27 12 3456 789</p>
                </div>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="container">
              <form
                action="https://formspree.io/f/xknyjnke"
                method="post"
                target="_blank"
              >
                <!-- the 'dot prevent' prevents the form from cleaaring the data back to default after submitting -->

                <label> Name:</label>
                <input
                  name="name"
                  type="text"
                  required
                  v-model="name"
                  placeholder="Enter full name and surname"
                />
                <label> Email:</label>
                <input
                  type="email"
                  required
                  v-model="email"
                  placeholder="Enter your email"
                  name="email"
                />

                <label> Number:</label>
                <input
                  type="text"
                  required
                  v-model="number"
                  placeholder="Enter your number"
                  name="number"
                />
                <div v-if="numberError" class="number">{{ numberError }}</div>

                <!--  dropdown for the role of whoever uses the form-->
                <label> Role:</label>
                <select v-model="role">
                  <option value="developer">Web developer</option>
                  <option value="designer">Web designer</option>
                  <option value="interested">Interested party</option>
                  <option value="other">Other</option>
                </select>
                <label for="inputMessage"> Message:</label>
                <textarea
                  class="form-control"
                  name="message"
                  id="inputMessage"
                  rows="5"
                  required
                >
                </textarea>
                <!-- working with checkboxes using booleans  -->
                <!-- <div class="terms">
                  <input type="checkbox" v-model="terms" required />
                  <label> Accept terms and conditions</label>
                </div> -->
                <div class="submit">
                  <button @click="submit">Submit</button>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      name: "", //This starts of as an empty string in order for it to be updated by what //
      //the user types in the webpage//
      number: "",
      role: "",
      terms: false,
      // names: [],
      message: "",
      numberError: "", //   erro message for when number is less than 10characters
    };
  },
  methods: {
    handleSubmit() {
      //   validate number has more than 10 characters
      this.numberError =
        this.number.length > 9
          ? ""
          : "Number must be at least 10 characters long";
    },
    submit() {},
  },
};
</script>

<style scoped>
#cont2 {
  background-color: #f5d3d559;
  padding-bottom: 80px;
  padding-top: 50px;
  font-size: 1.2em;
}
form {
  max-width: 100%;
  margin: 30px auto;
  text-align: left;
  padding: 40px;
  border-radius: 10px;
  background: #cf9f811e;
  box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.3);
  backdrop-filter: blur(4px);
  -webkit-backdrop-filter: blur(4px);
  border-radius: 10px;
  border: 1px solid rgba(255, 255, 255, 0.18);
}
#form {
  background-color: white;
  border-radius: 10px;
  padding-bottom: 20px;
}
.h1,
h1 {
  text-align: center;
  color: gray;
  font-size: medium;
  padding-top: 1.5%;
}

.col {
  height: 20%;
}
.address {
  display: flex;
}
.address i {
  font-size: 60px;
  padding: 65px;
}

label {
  color: rgb(12, 6, 6);
  display: inline-block;
  margin: 25px 0 15px;
  font-size: 0.6em;
  text-transform: uppercase;
  letter-spacing: 1px;
  font-weight: bold;
}
.h2,
h2 {
  text-align: center;
  padding-bottom: 40px;
}

input,
select {
  display: block;
  padding: 10px 6px;
  width: 100%;
  box-sizing: border-box;
  border: none;
  border-bottom: 1px solid #ddd;
  color: #555;
}
.cont {
  color: rgb(228, 18, 18);
}
.number {
  color: yellow;
  margin-top: 10px;
  font-weight: bold;
}
form {
  height: 94%;
}
input[type="checkbox"] {
  display: inline-flex;
  width: 16px;
  margin: 0 10px 0 0;
  position: relative;
  top: 2px;
}
#message {
  height: 110px;
}
.left-inner-container {
  padding-top: 130px;
}
.contact {
  box-shadow: 20px;
}
button {
  background: white;
  border: 1px;
  float: right;
  padding-bottom: 20px;
  padding: 5px 15px;
  border-radius: 20px;
}
.submit {
  text-align: center;
  padding: 20px;
}

@media screen and (max-width: 600px) {
  .address i {
    font-size: 60px;
    padding: 20px;
  }
  #cont2 {
    background-color: #f5d3d559;
    padding-bottom: 80px;
    padding-top: 30px;
    font-size: 1.2em;
  }
  .address i {
    display: none;
  }
  #left {
    display: none;
  }
  form {
    width: 100%;
    background: rgba(236, 4, 4, 0.25);
    box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
    backdrop-filter: blur(4px);
    -webkit-backdrop-filter: blur(4px);
    border-radius: 10px;
    border: 1px solid rgba(255, 255, 255, 0.18);
  }
}
</style>
