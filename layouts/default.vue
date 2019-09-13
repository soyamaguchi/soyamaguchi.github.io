<template>
  <div>
    <div id="nav">
      <div><n-link id="top" to="/">soyamaguchi.me</n-link></div>
      <nav>
        <n-link to="/about">About</n-link>
        <n-link to="/works">Works</n-link>
      </nav>
    </div>
    <nuxt />
  </div>
</template>

<style lang="scss">
body {
  width: 810px;
  margin: 0 auto;
  font-family: 'Noto Sans JP', sans-serif;
}

@media screen and (max-width: 810px) {
  body {
    width: 90vw;
  }
}

#nav {
  margin-top: 2rem;
  display: flex;
  justify-content: space-between;
  a {
    text-decoration: none;
    color: #616161;
    font-weight: normal;
    font-size: 1rem;
  }
  nav a {
    margin-left: 0.8rem;
    color: #adadad;
    &.nuxt-link-exact-active {
      color: #8f8f8f;
    }
  }
}
</style>
