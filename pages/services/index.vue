<template>
  <div>
      <div class="content center-block border-radius-1 top-left-radius-10">
        <h1 class="">{{ $t('services.title')}}</h1>
        <div class="mt-2 w-100">
          <services-nav-cards />
        </div>
      </div>
  </div>
</template>

<script>
import ServicesNavCards from "~/components/ServicesNavCards";
export default {
  name: 'IndexPage',
  components: {ServicesNavCards},
  layout: 'home'
}
</script>
