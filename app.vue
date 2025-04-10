<template>
  <div class="app">
    <div class="my-container">
      <div class="my-header">
        <div>
          <img class="logo" src="public/images/logo.png" alt="">
        </div>
      </div>
      <div class="coworkers">
        <div>
          <img src="public/images/four.svg" alt="">
          <div>
            <div class="mb-2">
              در حال به روز رسانی هستیم
            </div>
            <div>
              لطفا شکیبا باشید
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style>
body {
  margin: 0;
  font-family: yekan;
  color: #516d7c;
}

.my-container {
  height: 100%;
}

.app {
  text-align: center;
  height: 100vh;
}

.my-header {
  text-align: left;
  padding: 5px;
  margin-bottom: 25px;
}

.logo {
  width: 40px;
  height: 40px;
  border-radius: 8px;
}

.coworkers {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 0 10px;
}

.coworkers img {
  height: 420px;
  width: 100%;
  margin-bottom: 30px;
}

.mb-2{
  margin-bottom:10px ;
}

@font-face {
  font-family: yekan;
  src: url('./assets/fonts/yekanbakh/YekanBakhFaNum-Black.woff2');
}
</style>