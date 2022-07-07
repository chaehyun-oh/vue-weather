<template>
	<HeaderDisplay />
	<WeatherContents />
</template>

<script>
import HeaderDisplay from "./components/HeaderDisplay";
import WeatherContents from "./components/weather/WeatherContent.vue";

export default {
	name: "App",
	components: {
		HeaderDisplay,
		WeatherContents,
	},
};
</script>

<style></style>
