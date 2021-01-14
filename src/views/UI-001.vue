<template>
  <div class="flex-center">
    <div class="home-content">
      <h1>
        <img class="epictext" src="../assets/epictext2.gif" />
      </h1>
      <p class="bigtext">Sign up for the RTX 3090 giveaway (real)</p>
      <div class="textboxes">
        <div class="user-textbox">
          <p>
            <label>Full name: </label>
            <input type="text" id="myName" value="John Smith" />
          </p>
        </div>
        <div class="email-textbox">
          <p>
            <label>E-mail: </label>
            <input type="text" id="myEmail" value="johnsmith@grindr.com" />
          </p>
        </div>
        <div class="cc-textbox">
          <p>
            <label>Credit card number: </label>
            <input type="text" id="myCC" value="1234 5678 9101 1121" />
          </p>
        </div>
        <div class="ccb-textbox">
          <p>
            <label>CVV: </label>
            <input type="text" id="myCCB" value="420" />
          </p>
        </div>
        <div class="buttons">
          <button class="signup" type="button">Sign up</button>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
body {
  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
}

.home-content {
  padding: 14px;
  background-color: gray;
  width: 100%;
  border: 5px solid black;
  border-radius: 3%;
}

.bigtext {
  color: white;
  font-size: 20px;
  font-weight: bold;
}

.textboxes {
  align-content: center;
  color: white;
  padding-right: 65px;
}

input {
  height: 19px;
  border: 1px solid black;
  border-radius: 5%;
  background-color: orange;
}

.epictext {
  border: 2px solid black;
}

.buttons {
  color: black;
}

.signup {
  background-color: orange;
  border: 2px solid black;
  border-radius: 5%;
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
  width: 200px;
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
