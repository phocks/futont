<script lang="ts">
</script>

<div class="wrapper">
	<div class="text">Futont</div>
</div>

<style lang="scss">
	@use '../lib/mixins.scss' as *;

	.wrapper {
		background-color: aquamarine;
		height: 40px;
		display: flex;
		align-items: center;
	}

	.text {
		font-size: 32px;
		line-height: 1.3;
		font-weight: 400;
		font-style: normal;
		border: none;
		@include text-crop($top-adjustment: -0.5px, $bottom-adjustment: -2px);
		@supports (-moz-appearance: none) {
			transform: translateY(0.045em);
		}
	}
</style>
