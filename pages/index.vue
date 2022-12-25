<template>
  <div class="content">
    <div class="banner-main anibg-1">
      <div class="banner-main__title-block">
        <h1 class="banner-main__title" v-html="$t('seo.slogan')"></h1>
      </div>
      <img src="/images/bg/banner-home.svg" width="80%" alt="banner" class="">
    </div>
  </div>
</template>

<script>
import ServicesNav from "~/components/ServicesNav";

export default {
  name: 'IndexPage',
  components: {ServicesNav},
  layout: 'home'
}
</script>
