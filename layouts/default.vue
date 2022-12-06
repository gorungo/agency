<template>
	<div id="app">
		<AppHeader />
		<main class="w-100">
				<nuxt />
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
