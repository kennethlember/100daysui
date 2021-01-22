<template>
  <div class="flex-center">
    <div class="home-content">
      <h1></h1>
      <p class="bigtext">Sign up for the giveaway</p>
      <div class="textboxes">
        <div class="user-textbox">
          <p>
            <label>Full name: </label>
            <input type="text" id="myName" placeholder="Enter full name" />
          </p>
        </div>
        <div class="email-textbox">
          <p>
            <label>E-mail: </label>
            <input type="text" id="myEmail" placeholder="Enter e-mail" />
          </p>
        </div>
      </div>
      <div class="buttons">
        <button class="signup" type="button">Sign up</button>
      </div>
    </div>
  </div>
</template>

<style>
html {
  background: darkmagenta;
}

body {
  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
}

.home-content {
  padding: 14px;
  background-color: darkorchid;
  width: 100%;
  align-content: center;
  box-shadow: 0 0 10px 5px black;
}

.bigtext {
  color: white;
  font-size: 20px;
  font-weight: bold;
}

.textboxes {
  display: flex;
  flex-direction: column;
  color: white;
}

input {
  height: 19px;
  border: 1px solid black;
  border-radius: 5%;
  background-color: darkmagenta;
  color: white;
}

::placeholder {
  color: silver;
  opacity: 1;
}

.buttons {
  color: black;
}

.signup {
  background-color: orchid;
  border: 2px solid black;
  color: black;
  font-weight: bold;
  padding: 5px 10px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
}
label {
  display: inline-block;

  margin-right: 30px;
  text-align: right;
}

input {
}

fieldset {
  border: none;
  width: 500px;
  margin: 0px auto;
}
</style>
