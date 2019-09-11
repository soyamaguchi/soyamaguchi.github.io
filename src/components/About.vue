<template>
  <div class="about__me">
    <h1>About me</h1>
    <div class="about__me__info">
      <div class="about__me__img"></div>
      <!-- <img src="../assets/profile.jpg" alt="profile.jpg"> -->
      <!-- <h2>PortfolioSite - soyamaguchi.me</h2>
      <p>個人開発</p>
      <a href="https://soyamaguchi.me" target="_blank" rel="noopener">soyamaguchi.me</a> -->
    </div>
  </div>
</template>

<script>
export default {
  name: 'Achievement',
}
</script>

<style lang="scss" scoped>
$font-fam: 'Helvetica Neue', Helvetica, Arial, sans-serif;

.about__me {
  h1 {
    margin: 0 0 3rem;
    font-family: $font-fam;
    color: #808080;
  }
  .about__me__info {
    margin-bottom: 2rem;
    .about__me__img {
        display: inline-block;
        width: 210px;
        height: 210px;
        border-radius: 50%;
        background-image: url("../assets/profile.jpg");
        background-position: center 80%;
    }
    .date {
      color: #c2c2c2;
    }
    h2 {
      margin: 0;
      font-family: $font-fam;
      color: #616161;
    }
    p,
    a {
      color: #474747;
    }
    p {
      margin: 0.5rem 0;
    }
  }
}
</style>