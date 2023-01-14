<template>
  <nav class="services-nav-cards">
    <div class="row">
      <div class="col-6">
        <nuxt-link :to="localePath('/services/internet')">
          <div class="card card-body text-center bg-light-panel bg-gr-2">
            <img src="/images/icon/services-internet.svg" height="200" alt="" />
            <h3>{{$t('services.internet.title')}}</h3>
          </div>
        </nuxt-link>
      </div>
      <div class="col-6">
        <nuxt-link :to="localePath('/services/video')">
          <div class="card card-body bottom-left-radius-5 text-center bg-gr-1">
            <img src="/images/icon/services-video.svg" height="200" alt="" />
            <h3>{{$t('services.video.title')}}</h3>
          </div>
        </nuxt-link>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "ServicesNavCards"
}
</script>

