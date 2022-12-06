<template>
<div>
  <strong>{{$i18n.locale}}</strong>
  <nuxt-link
    v-for="locale in availableLocales"
    :key="locale.code"
    :to="switchLocalePath(locale.code)">{{ locale.code }}</nuxt-link>
</div>
</template>

<script>
export default {
  name: "LangSwitcher",
  computed: {
    availableLocales () {
      return this.$i18n.locales.filter(i => i.code !== this.$i18n.locale)
    }
  }
}
</script>
