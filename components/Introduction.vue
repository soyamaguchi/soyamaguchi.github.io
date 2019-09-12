<template>
  <div class="introduction">
    <p>
      <n-link to="/about">Soya Yamaguchi</n-link>
      is a developer based in Osaka, Japan.<br />
      My career as a software engineer is in my third year.
    </p>
    <h2>Contact</h2>
    <ul>
      <li>
        <a href="https://github.com/soyamaguchi" target="_blank" rel="noopener">
          GitHub
        </a>
      </li>
      <li>
        <a
          href="https://twitter.com/_soyamaguchi_"
          target="_blank"
          rel="noopener"
        >
          Twitter
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Introduction'
  // props: {
  // }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
.introduction {
  p,
  a {
    color: #474747;
  }
  p {
    line-height: 1.7;
  }
  h2 {
    margin-top: 4rem;
    margin-bottom: 0;
    font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
    color: #616161;
  }
  ul {
    list-style-type: none;
    padding: 0;
  }
  li {
    display: inline-block;
    margin: 0 0.5rem;
  }
}
</style>
