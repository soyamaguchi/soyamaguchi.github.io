<template>
  <div class="about__me">
    <h1>About me</h1>
    <section class="about__me__info">
      <figure class="about__me__info__img"></figure>
      <span class="about__me__info__name">
        <h2>Soya Yamaguchi</h2>
      </span>
      <div class="about__me__info__feature">
        <p>
          三重県出身大阪府在住、1993年生まれ。<br />
          仕事、個人など問わずコードを書いており、フルスタックに幅広くやります。<br />
          DDDやClean Architectureなどのアーキテクチャに興味があるお年頃。<br />
          でもやはり探究心をもって専門性を磨いていきたい。
        </p>
      </div>
      <div class="about__me__info__skills">
        <span>Frontend</span>
        <p>HTML / CSS / JavaScript / Vue.js / Nuxt.js</p>
        <span>Backend</span>
        <p>
          Java / Struts2 / Spring / VB.NET / Ruby / Rails / Oracle / PostgreSQL
        </p>
        <span>Other</span>
        <p>Docker / AWS</p>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'Achievement'
}
</script>

<style lang="scss" scoped>
$font-fam: 'Helvetica Neue', Helvetica, Arial, sans-serif;

.about__me {
  h1 {
    color: #808080;
    font-family: $font-fam;
    margin: 0 0 3rem;
  }
  &__info {
    &__img {
      width: 210px;
      height: 210px;
      border-radius: 50%;
      background-image: url('../assets/profile.jpg');
      background-position: center 80%;
      margin: 0;
    }
    &__name {
      font-family: $font-fam;
      color: #616161;
    }
    &__feature {
      color: #474747;
      line-height: 1.6;
      margin-bottom: 2rem;
    }
    &__skills {
      span {
        font-family: $font-fam;
        color: #616161;
        font-weight: bold;
        font-size: 1.2rem;
      }
      p {
        color: #474747;
        margin: 0 0.5rem 1rem;
      }
    }
  }
}
</style>
