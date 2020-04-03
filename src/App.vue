<template>
	<VueDisbounce id="app">
		<div class="page1">下拉</div>
		<div class="page2">下拉</div>
		<div class="page3">下拉</div>
	</VueDisbounce>
</template>

<script>
import VueDisbounce from "./component";

export default {
	components: {
		VueDisbounce
	},

	created() {}
};
</script>

<style>
* {
	margin: 0;
	padding: 0;
}
.page1 {
	height: 100vh;
	background: #f1f1f1;
}
.page2 {
	height: 100vh;
	background: #fff;
}
.page3 {
	height: 100vh;
	background: #ebebeb;
}
</style>