<template>
  <div>
    <nuxt/>
  </div>
</template>

<style>

@font-face {
  font-family: 'bradley-hand';
  src: URL('/BRADHI.ttf') format('truetype');
}

html {
  /* font-family: 'PT Sans', sans-serif, "Helvetica Neue"; */
  font-family: 'bradley-hand';
  font-weight: 700;
  font-size: 19px;
  line-height:2;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  min-height: 100%;
}

p{
  font-size: 19px;
}

body{
  background-image: url('/bg.jpg');
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-position: center; 
  background-size:cover;
  min-height: 100%;
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

