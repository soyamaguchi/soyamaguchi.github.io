<template>
  <div id="app">
    <div id="nav">
      <div><router-link to="/" id="top">soyamaguchi.me</router-link></div>
      <nav>
        <router-link to="/about">About</router-link>
        <router-link to="/works">Works</router-link>
      </nav>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
body {
  width: 830px;
  height: 100vh;
  margin: 0 auto;
  font-family: 'Noto Sans JP', sans-serif;
}

@media screen and (max-width: 830px) {
  body {
    width: 90vw;
  }
}

/*#app {*/
/*  font-family: 'Avenir', Helvetica, Arial, sans-serif;*/
/*  -webkit-font-smoothing: antialiased;*/
/*  -moz-osx-font-smoothing: grayscale;*/
/*  text-align: center;*/
/*  color: #2c3e50;*/
/*}*/

#nav {
  margin-top: 2rem;
  display: flex;
  justify-content: space-between;
  a {
    text-decoration: none;
    color: #606060;
    font-weight: normal;
    font-size: 1rem;
  }
  nav a {
    margin-left: 1rem;
    color: #adadad;
    &.router-link-exact-active {
      color: #8f8f8f;
    }
  }
}
</style>
