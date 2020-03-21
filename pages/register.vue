<template>
  <div class="container">
    <span>Welcome! Please register if you don't have an account</span>
    <form action>
      <label for="email">Email</label>
      <input type="email" name="email" id="email" />
      <label for="pass">Password</label>
      <input type="password" name="pass" id="pass" />
      <label for="repass">Repeat password</label>
      <input type="password" name="repass" id="repass" />
    </form>

    <button class="button">Register</button>
  </div>
</template>
<style scoped>
.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.container span {
  margin: 0 auto;
  text-align: center;
  padding: 2em 0;
  border-top: 1px solid black;
  border-bottom: 1px solid black;
  width: 100%;
  font-size: 1.3em;
  font-weight: bold;
}

form {
  margin: 2em 10em;
  padding-bottom: 2em;
  display: flex;
  flex-direction: column;
  width: 100%;
  position: relative;
  border-bottom: 1px solid black;
}

.button {
  cursor: pointer;
  background-color: black;
  color: white;
  border: none;
  border-radius: 30px;
  border: 1px solid black;
  padding: 0.6em 1.5em;
  font-size: 1.3em;
  transition: all 200ms ease-in-out;
  text-decoration: none;
}

.button:hover {
  background-color: white;
  color: black;
  border: 1px solid black;
}

label {
  font-size: 1.3em;
}

form input,
form label {
  width: 30%;
  margin: 0.3em auto;
}
</style>
