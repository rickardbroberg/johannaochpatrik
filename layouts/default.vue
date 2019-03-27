<template>
  <div>
    <nuxt/>
  </div>
</template>

<style>


html {
  font-family: 'PT Sans', sans-serif, "Helvetica Neue";
  font-size: 18px;
  line-height:2;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

body{
  background-image: url('/bg.jpg');
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-position: center; 
}

*, *:before, *:after {
  box-sizing: border-box;
  margin: 0;
}

@media only screen and (min-width: 768px) {

  html {
    line-height:1.5;
  }

}

</style>

