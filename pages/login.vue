<template>
  <div class="container">
    <div class="message">
      <p>
        use your
        <br />free time to
        <br />
        <span class="bigger">learn.</span>
      </p>
    </div>
    <div class="login-form">
      <span>Login</span>
      <form action>
        <label for="username">Username</label>
        <input
          id="username"
          class="form-input"
          type="text"
          placeholder="Ex: ElonMusk"
          name="username"
        />
        <label for="pass">Password</label>
        <input id="pass" type="password" name="pass" />
        <div class="button-container">
          <button class="button">Login</button>
          <nuxt-link to="register" class="button">Register</nuxt-link>
        </div>
      </form>
    </div>
  </div>
</template>

<style scoped>
.container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-template-rows: 1fr;
  margin: 5em auto;
  align-items: center;
  height: 500px;
  padding: 0;
}

.message {
  grid-column: 1 / 2;
  grid-row: 1 / 2;
  font-size: 4em;
}

.message p {
  line-height: 130%;
}

.login-form {
  width: 100%;
  grid-column: 2 / 3;
  grid-row: 1 / 1;
  background-color: #f29b19;
  width: 100%;
  height: 80%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  border-radius: 50px;
}

label {
  color: black;
  width: 50%;
  margin-right: auto;
  font-size: 1.3em;
}

form {
  display: flex;
  flex-direction: column;
  justify-content: center;
  justify-self: start;
  padding: 0 5em;
}

input {
  margin-left: 0;
  border-radius: 5px;
  border: none;
  padding: 0.5em;
  font-size: 1.5em;
}

span {
  font-size: 3em;
  padding: 0;
  margin: 0;
  align-self: center;
  color: black;
}

.button-container {
  margin: 2em;
  height: 50%;
  display: flex;
  justify-content: space-around;
  align-items: center;
}

.button {
  cursor: pointer;
  background-color: black;
  color: white;
  border: none;
  border-radius: 30px;
  padding: 0.6em 1.5em;
  font-size: 1.3em;
  transition: all 200ms ease-in-out;
  text-decoration: none;
}

.button:hover {
  background-color: white;
  color: black;
}

.bigger {
  color: black;
  font-size: 2em;
}
</style>
