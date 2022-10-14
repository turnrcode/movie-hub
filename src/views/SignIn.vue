<template>
  <header class="showcase">
        <div class="showcase-top">
            <img src="../assets/logo-netflix.png" alt="NETFLIX">
            <!-- <a href="#" class="btn btn-rounded">Register</a> -->
            <!-- <router-link class="btn" id="" :to="{name:'home'}">Register</router-link> -->
        </div>

        <div class="login">
                <h1>Sign In</h1>
            <form id="">
      <div class="form-group">
        <label id="name-label" for="name"></label>
        <input
          type="email"
          id="email"
          class="form-control"
          placeholder="Email or phone number"
          required
        />
      </div>
      <div class="form-group">
        <label id="email-label" for="email"></label>
        <input
          type="password"
          id="password"
          class="form-control"
          placeholder="Password"
          required
        />
      </div>

      <div class="form-group">
        <button id="submit" class="submit-button">Sign In</button>
      </div>
      
        <div class="row">
            <label>
          <input
            type="checkbox"
            class="input-checkbox"
          />  Remember me
        </label>
        <!-- <a href="#">Need help?</a> -->
        </div>
        
      </form>

      <br>
      <div class="row">
        <h6>New to Netflix? <router-link :to="{name:'home'}">Sign up now</router-link></h6>
      <p>This page is protected by Google reCAPTCHA to ensure you're not a bot. <a href="#">Learn more</a>.</p>
      </div>
      
        </div>
    </header>
</template>

<!-- <script>
export default {
    name:'SignUp'

}
</script> -->

<style scoped>
.login{
    z-index: 5;
    position: relative;
    width: 100%;
    margin: 0 auto 0 auto;
    padding: 20px;
    background: rgba(0, 0, 0, 0.7);
}
@media (min-width: 576px) {
  .login {
    max-width: 540px;
  }
}

@media (min-width: 768px) {
  .login {
    max-width: 450px;
    height: 80vh;
  }
}
@media (min-width: 380px) {
  .login {
    max-width: 450px;
    height: 70vh;
  }
}

.showcase {
	width: 100%;
	height: 100vh;
	position: relative;
	background: url('../assets/Netflix-Background.jpg') no-repeat center center/cover;
}

.showcase::after {
	content: '';
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
	/* z-index: 1; */
	background: rgba(0, 0, 0, 0.5);
	box-shadow: none;
}

.showcase-top {
	position: relative;
	z-index: 2;
	height: 90px;
    display: flex;
    justify-content: space-between;
}

.showcase-top img {
    width: 170px;
    height: auto;
	position: absolute;
	top: 50%;
	left: 10%;
	transform: translate(-50%, -50%);
	margin-left: 0;
}


.showcase-content {
	position: relative;
	z-index: 2;
	width: 65%;
	margin: auto;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	text-align: center;
	margin-top: 9rem;
}

h1 {
  font-weight: 600;
  line-height: 1.2;
  font-size: 1.7rem;
}

p {
  font-size: .7rem;
}

h1,
p {
  margin-top: 1rem;
  margin-bottom: 0.5rem;
}

label {
  display: flex;
  align-items: center;
  font-size: 1.125rem;
  margin-bottom: 0.5rem;
}

input,
button,
select,
textarea {
  margin: 0;
  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
}

button {
  border: none;
}

/* form */

form {
  padding: 2.5rem 0.625rem;
  border-radius: 0.25rem;
  text-align: left;
}

@media (min-width: 480px) {
  form {
    padding: 2.5rem;
  }
}

.form-group {
  margin: 0 auto 1.25rem auto;
  padding: 0.25rem;
}

.form-control {
  display: block;
  width: 100%;
  height: 2.375rem;
  padding: 0.375rem 0.75rem;
  color: #495057;
  background-color: var(--light-color);
  background-clip: padding-box;
  border: 1px solid #ced4da;
  border-radius: 0.25rem;
  transition: border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
}

.form-control:focus {
  border-color: #80bdff;
  outline: 0;
  box-shadow: 0 0 0 0.2rem rgba(0, 123, 255, 0.25);
}

.submit-button {
  display: block;
  width: 100%;
  padding: 10px 0 10px 0;
  background-color: var(--primary-color);
  color: var(--light-color);
  border-radius: 2px;
  font-size: 20px;
  cursor: pointer;
}
</style>