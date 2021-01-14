<template>
  <div class="flex-center">
    <div class="home-content">
      <h1></h1>
      <p class="bigtext">Checkout</p>
      <div class="textboxes">
        <div class="user-textbox">
          <p>
            <label>First name: </label>
            <input type="text" id="myName" value="John" />
          </p>
        </div>
        <div class="surname-textbox">
          <p>
            <label>Last name: </label>
            <input type="text" id="myName" value="Smith" />
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
          <button class="signup" type="button">Continue to pay</button>
        </div>
      </div>
    </div>
  </div>
</template>
<style>
* {
  font-family: Verdana, Geneva, Tahoma, sans-serif;
}
.bigtext {
  font-weight: bold;
  border: 2px solid black;
  background-color: white;
}
label {
  display: inline-block;
  width: 200px;
  margin-right: 30px;
  text-align: right;
}

input {
  background-color: lightblue;
  border: none;
  border-radius: 3%;
}

fieldset {
  border: none;
  width: 500px;
  margin: 0px auto;
}
.flex-center {
  background-color: darkblue;
  padding: 25px;
}
.textboxes {
  color: white;
}
.signup {
  border: 1px solid black;
  border-radius: 3%;
  color: white;
  padding: 10px 22px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 20px;
  background: rgb(5, 0, 97);
  background: radial-gradient(
    circle,
    rgba(5, 0, 97, 1) 0%,
    rgba(0, 212, 255, 1) 100%,
    rgba(0, 255, 248, 1) 100%
  );
}
</style>
