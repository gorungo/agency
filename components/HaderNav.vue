<template>
  <nav class="header-nav">
    <ul>
      <li><nuxt-link :to="localePath('/services')">{{$t('nav.services.title')}}</nuxt-link></li>
      <li><nuxt-link :to="localePath('/folio')">{{$t('nav.portfolio.title')}}</nuxt-link></li>
      <li><nuxt-link :to="localePath('/info/about')">{{$t('nav.info.about.title')}}</nuxt-link></li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: "HeaderNav"
}
</script>

