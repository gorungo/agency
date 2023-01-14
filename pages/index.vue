<template>
  <div class="content">
    <div class="banner-main anibg-1">
      <div class="banner-main__title-block">
        <h1 class="banner-main__title" v-html="$t('seo.slogan')"></h1>
      </div>
      <img src="/images/bg/banner-home.svg" width="80%" alt="banner" class="">
    </div>
    <section class="mt-4">
      <h3 class="title_vs_link">{{$t('portfolio.latestTitle')}}<nuxt-link to="/folio">{{$t('text.more')}}</nuxt-link></h3>
      <div class="row folio">
        <div class="col-md-3 col-3 folio-image-cover">
          <img src="/images/folio/fay-1.jpg" data-fancybox="gallery-new" class="folio-image" alt="folio"/>
        </div>
        <div class="col-md-3 col-3 folio-image-cover">
          <img src="/images/folio/practice-1.jpg" data-fancybox="gallery-new" class="folio-image" alt="folio"/>
        </div>
        <div class="col-md-3 col-3 folio-image-cover">
          <img src="/images/folio/bali-1.jpg" data-fancybox="gallery-new" class="folio-image" alt="folio"/>
        </div>
        <div class="col-md-3 col-3 folio-image-cover">
          <img src="/images/folio/cryptoscan-1.jpg" data-fancybox="gallery-new" class="folio-image" alt="folio"/>
        </div>
      </div>
    </section>
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
