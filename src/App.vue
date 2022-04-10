<template>
  <div id="nav">
    <router-link to="/">Главная</router-link>
    <router-link to="/about">О компании</router-link>
  </div>
  <router-view/>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800;900&display=swap');
/* font-family: 'Inter', sans-serif; */

*,*::before,*::after{
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

:root{
  --navColor: #716D6D;
  --navActiveColor: #DFA046;
  --titleColor: #000;
  --titleActiveColor: #F1AA1E;
  --dbTitleColor: #6D6565;
  --dbTitleActiveColor: #F1AA1E;
  --bgColorInfo: #F2BF6E;
  --bgColorNetwork: #252821;
}

body{
  max-width: 100vw; height: auto;
}

#app{
  font-family: 'Inter', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav{
  position: absolute;
  top: 3.9%;
  left: 37.5%;
  font-size: 1.3rem;
  font-weight: 600;
  z-index: 999;
}

#nav a{
  margin-right: 3rem;
  color: var(--navColor);
  text-decoration: none;
  transition: color 0.15s;
}

#nav a:hover{
  color: #514e4e;
}

#nav a.router-link-exact-active{
  color: var(--navActiveColor);
}

@media (max-width: 1287px){
  #nav{
    top: 3.2%;
    left: 51%;
    font-size: 1.1rem;
  }
}

@media (max-width: 1110px){
  #nav{
    top: 3.2%;
    left: 5%;
    font-size: 1.2rem;
  }
}

@media (max-height: 910px){
  #nav{
    font-size: 1.2rem;
  }
}

@media (max-height: 800px){
  #nav{
    font-size: 0.9rem;
  }
}
</style>
