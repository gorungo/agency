<template>
  <div class="">
    <h1 class="">{{ $t('services.internet.title') }}</h1>
    <p class="">{{ $t('services.internet.subtitle') }}</p>
    <div class="mt-2">
      <h3>{{ $t('services.internet.landing.title') }}</h3>
      <div class="mt-2 w-100 row same-height">
        <div class="col-4 col-md-4">
          <div class="service-card card card-body height-100">
            <img src="/images/icon/services-internet.svg" height="200" alt=""/>
            <div class="service-card__title">
              Верстка
            </div>
            <div class="service-card__subtitle">
              <p>В работу входит*</p>
              <ul>
                <li>верстка</li>
              </ul>
            </div>
            <div class="service-card__price">от 5000 руб.</div>
          </div>
        </div>
        <div class="col-4 col-md-4">
          <div class="service-card card card-body height-100">
            <img src="/images/icon/services-internet.svg" height="200" alt=""/>
            <div class="service-card__title">Текст и верстка</div>
            <div class="service-card__subtitle">
              <p>В работу входит*</p>
              <ul>
                <li>верстка</li>
                <li>текст</li>
              </ul>
            </div>
            <div class="service-card__price">от 10000 руб.</div>
          </div>
        </div>
        <div class="col-4 col-md-4">
          <div class="service-card card card-body height-100">
            <img src="/images/icon/services-internet.svg" height="200" alt=""/>
            <div class="service-card__title">Гулять так гулять</div>
            <div class="service-card__subtitle">
              <p>В работу входит*</p>
              <ul>
                <li>дизайн</li>
                <li>верстка</li>
                <li>текст</li>
              </ul>
            </div>
            <div class="service-card__price">от 30000 руб.</div>
          </div>
        </div>
      </div>
    </div>
    <div>
      <p>
        * - при необходимости отдельно оплачиваются услуги хостинга, покупка изображений
      </p>
    </div>

  </div>
</template>

<script>
export default {
  name: "index",
  layout: 'services',
}
</script>
