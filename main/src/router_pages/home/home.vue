<template>
	<div>
		<theme-header />
		<theme-list />
		<theme-footer />
	</div>
</template>

<script type="text/javascript">
	import ThemeHeader from "../../vue_components/theme/header.vue";
	import ThemeList from "../../vue_components/theme/list.vue";
	import ThemeFooter from "../../vue_components/theme/footer.vue";

	export default {
		name: "home",
		components: {
			"theme-header": ThemeHeader,
			"theme-list": ThemeList,
			"theme-footer": ThemeFooter
		}
	};
</script>