<template>
  <div class="app">
    <div class="my-container">
      <div class="my-header">
        <div class="">
          آرام تجارت
        </div>
        <div class="flex mr-2">
          <img class="logo" src="public/images/logo.png" alt="">
        </div>
      </div>
      <div class="coworkers">
        <div>
          <img class="coworkers-image" src="public/images/four.svg" alt="">
          <div class="relative inline-block">
            <div class="mb-2">
              در حال به روز رسانی هستیم
            </div>
            <div>
              لطفا شکیبا باشید
            </div>
            <div class="gears">
              <img class="gear1 rotating" src="public/images/gear1.png" alt="">
              <img class="gear2 rotating" src="public/images/gear1.png" alt="">
              <img class="gear3 rotating" src="public/images/gear1.png" alt="">
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
  color: #b0883e;
  background: rgb(28, 28, 28);
}
.flex{
  display: flex;
}

.my-container {
  height: 100%;
}

.app {
  text-align: center;
  height: 100vh;
}
.mr-2{
  margin-right: 10px;
}
.my-header {
  text-align: right;
  margin-bottom: 40px;
  display: flex;
  justify-content: end;
  align-items: center;
  gap: 10px;
  width: 100%;
  border-bottom: solid 1px #b0883e;
  padding: 6px 0;
  background: rgb(0, 0, 0);

}
.gears{
  position: absolute;
  right: -30px;
  top: 0;
  opacity: 0.5;
}
.gear1{
  position: absolute;
  width: 40px;
  height: 40px;
  top: -10px;
  right: -20px;
}
.gear2{
  position: absolute;
  top: -20px;
  right: -45px;
  width: 20px;
  height: 20px;
}
.gear3 {
  position: absolute;
  top: 10px;
  right: -52px;
  width: 30px;
  height: 30px;
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
.relative{
  position: relative;
}
.coworkers-image {
  height: 420px;
  width: 100%;
  margin-bottom: 30px;
}

.mb-2{
  margin-bottom:10px ;
}

.inline-block{
  display: inline-block;
}

/* Rotate Animation */
@keyframes rotate {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
}

.rotating {
  animation: rotate 5s linear infinite; 
}


@font-face {
  font-family: yekan;
  src: url('./assets/fonts/yekanbakh/YekanBakhFaNum-Black.woff2');
}
</style>