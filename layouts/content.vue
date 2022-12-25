<template>
	<div id="app">
		<AppHeader />
		<main class="px-1">
      <div class="content border-radius-1 w-100 bg-white">
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

export default {
	components: {AppHeader, AppFooter},

}
</script>
