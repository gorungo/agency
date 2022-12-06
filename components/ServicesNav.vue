<template>
  <nav class="services-nav">
    <nuxt-link :to="localePath('/services/video')">{{$t('services.video.title')}}</nuxt-link>
    <nuxt-link :to="localePath('/services/internet')">{{$t('services.internet.title')}}</nuxt-link>
  </nav>
</template>

<script>
export default {
  name: "ServicesNav"
}
</script>

