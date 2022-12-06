<template>
	<div id="app">
		<AppHeader />
		<main class="px-1">
      <div class="content border-radius-1 w-100 top-left-radius-10">
        <div class="container min-h-60">
          <nuxt />
        </div>
      </div>
		</main>
		<AppFooter />
	</div>
</template>

<script>
import AppHeader from "~/components/AppHeader"
import AppFooter from "~/components/AppFooter"
import ServicesNav from "~/components/ServicesNav";

export default {
	components: {ServicesNav, AppHeader, AppFooter},

}
</script>
