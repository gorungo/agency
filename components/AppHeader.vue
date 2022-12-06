<template>
<header>
  <nuxt-link :to="localePath('/')"><img src="/images/logo/main_logo_color.svg" height="24" alt="logo"/></nuxt-link>
  <header-nav />
  <div style="width: 172px; text-align: right;">
    <lang-switcher />
  </div>
</header>
</template>

<script>
import HeaderNav from "~/components/HaderNav";
import LangSwitcher from "~/components/LangSwitcher";
export default {
  name: "AppHeader",
  components: {LangSwitcher, HeaderNav}
}
</script>

