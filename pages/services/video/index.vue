<template>
  <div class="">
    <h1 class="">{{ $t('services.video.title')}}</h1>
    <p class="">{{ $t('services.video.subtitle')}}</p>
    <div class="mt-2 w-100 row">
      <div class="col-4">
        <div class="service-card card card-body height-100">
          <img src="/images/icon/services-video.svg" height="200" alt="" />
          <div class="service-card__title">{{$t('services.video.logoAnimation.title')}}</div>
          <div class="service-card__subtitle mt-1">{{$t('services.video.logoAnimation.description')}}</div>
          <div class="service-card__duration">{{$t('text.maxDuration')}} {{$t('services.video.logoAnimation.maxDuration')}}</div>
          <div class="service-card__price mt-1">{{$t('services.video.logoAnimation.price')}}</div>
        </div>
      </div>
      <div class="col-4">
        <div class="service-card card card-body height-100">
          <img src="/images/icon/services-video.svg" height="200" alt="" />
          <div class="service-card__title">{{$t('services.video.animation.title')}}</div>
          <div class="service-card__subtitle mt-1">{{$t('services.video.animation.description')}}</div>
          <div class="service-card__duration">{{$t('text.maxDuration')}} {{$t('services.video.animation.maxDuration')}}</div>
          <div class="service-card__price mt-1">{{$t('services.video.animation.price')}}</div>
        </div>
      </div>
      <div class="col-4">
        <div class="service-card card card-body height-100">
          <img src="/images/icon/services-video.svg" height="200" alt="" />
          <div class="service-card__title">{{$t('services.video.film.title')}}</div>
          <div class="service-card__subtitle mt-1">{{$t('services.video.film.description')}}</div>
          <div class="service-card__duration">{{$t('text.maxDuration')}} {{$t('services.video.film.maxDuration')}}</div>
          <div class="service-card__price mt-1">{{$t('services.video.film.price')}}</div>
        </div>
      </div>
    </div>
    <div>

    </div>
  </div>
</template>

<script>
export default {
  name: "index",
  layout: 'services',
}
</script>
