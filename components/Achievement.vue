<template>
  <div class="achievement">
    <h1>Products</h1>
    <div class="achievement__products-info">
      <span class="achievement__products-info__date">2019-09</span>
      <h2>PortfolioSite - soyamaguchi.me</h2>
      <p>個人開発</p>
      <a href="https://soyamaguchi.me" target="_blank" rel="noopener">
        soyamaguchi.me
      </a>
    </div>
    <div class="achievement__products-info">
      <span class="achievement__products-info__date">2019-08</span>
      <h2>知っておいて損はないお得な自治体情報 - Advice2.com</h2>
      <p>個人開発</p>
      <a href="https://advice2.com" target="_blank" rel="noopener">
        advice2.com
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Achievement'
}
</script>

<style lang="scss" scoped>
$font-fam: 'Helvetica Neue', Helvetica, Arial, sans-serif;

.achievement {
  h1 {
    margin: 0 0 3rem;
    font-family: $font-fam;
    color: #808080;
  }
  &__products-info {
    margin-bottom: 2rem;
    &__date {
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
