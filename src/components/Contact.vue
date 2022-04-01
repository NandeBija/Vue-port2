<template>
  <section id="cont2">
    <div class="contact">
      <h1 class="h1">Get in touch</h1>
      <h2 class="h2">
        <span style="border-bottom: 3px solid red">Contact</span>
      </h2>
      <div class="container">
        <div class="row" id="form">
          <div class="container py-5 h-100">
            <div
              class="row d-flex justify-content-center align-items-center h-100"
            >
              <div class="col col-xl-10">
                <div class="card" style="border-radius: 1rem">
                  <div class="row g-0">
                    <div class="col-md-6 col-lg-5 d-none d-md-block">
                      <img
                        src="https://i.postimg.cc/fL4K0VGL/markus-winkler-q3-QPw37-J6-Xs-unsplash.jpg"
                        alt="login form"
                        class="img-fluid"
                        style="border-radius: 1rem 0 0 1rem"
                      />
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
                          />
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
                            rows="4"
                            required
                          >
                          </textarea>

                          <div class="submit">
                            <button @click="submit">Submit</button>
                          </div>
                          <div class="divider d-flex align-items-center my-4">
                            <p class="text-center fw-bold mx-3 mb-0 text-muted">
                              OR
                            </p>
                          </div>

                          <a
                            class="btn btn-primary  "
                            style="background-color: #3b5998"
                            href="https://www.linkedin.com/in/nande-bija-6333441b8/"
                            role="button"
                          >
                            <img
                              src="https://img.icons8.com/fluency/30/000000/linkedin.png"
                              style="padding: 8px; width: "
                            />Connect with LinkedIn
                          </a>
                        </form>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
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
  text-align: left;
  padding: 40px;
  border-radius: 10px;
  border-radius: 10px;
}

.img-fluid {
  height: 100%;
  width: 100%;
}
#form {
  background-color: white;
  border-radius: 10px;
  padding-bottom: 20px;
}
.divider:after,
.divider:before {
  content: "";
  flex: 1;
  height: 1px;
  background: #eee;
}

.h1,
h1 {
  text-align: center;
  color: gray;
  font-size: medium;
  padding-top: 1.5%;
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
  border: 1px solid #ddd;
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
.btn {
  margin-left: 115px;
  text-align: center;
  height: 55px;
  width: 300px;
  border-radius: 45px;
}

button {
  background: #dc3545;
  border: 1px;
  /* float: right; */
  color: white;
  padding-bottom: 20px;

  padding: 5px 15px;
  border-radius: 20px;
}
button:hover{
  background-color: #77161f ;
  
}
.submit {
  text-align: center;
  padding-bottom: 15px;
  padding-top: 15px;
}


@media screen and (max-width: 600px) {
  .address i {
    font-size: 60px;
    padding: 20px;
  }
  .btn {
  margin: auto;
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
    background: white;
    box-shadow: 0 8px 27px 0 rgba(54, 54, 56, 0.37);
    backdrop-filter: blur(4px);
    -webkit-backdrop-filter: blur(4px);
    border-radius: 10px;
    border: 1px solid rgba(255, 255, 255, 0.18);
  }
}
</style>
