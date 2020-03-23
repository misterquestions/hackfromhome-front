<template>
  <div class="container">
    <p>Challenges</p>
    <div class="challenges">
      <ul>
        <li>
          <a class="button" href="#">Challenge 1</a>
        </li>
        <li>
          <a class="button" href="#">Challenge 2</a>
        </li>
        <li>
          <a class="button" href="#">Challenge 3</a>
        </li>
        <li>
          <a class="button" href="#">Challenge 4</a>
        </li>
        <li>
          <a class="button" href="#">Challenge 5</a>
        </li>
      </ul>
    </div>
  </div>
</template>
<style scoped>
p {
  font-size: 64px;
}

.challenges {
  display: flex;
  align-items: end;
  justify-content: center;
}

ul {
  list-style: none;
  width: 100%;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

li {
  margin: 1em auto;
  width: 100%;
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
  border: 1px solid black;
}

.button:hover {
  background-color: white;
  color: black;
  border: 1px solid black;
}
</style>
