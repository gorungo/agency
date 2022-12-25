<template>
	<div id="app">
		<AppHeader />
		<main class="px-1">
      <div class="content border-radius-1 w-100 top-left-radius-10 bg-white">
        <div class="container min-h-60">
          <div class="mb-2">
            <services-nav />
          </div>
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
