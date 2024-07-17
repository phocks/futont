<button class="root">Futont</button>

<style lang="scss">
	@use '../lib/mixins.scss' as *;

	.root {
		@include text-crop($top-adjustment: -0.5px, $bottom-adjustment: -2px);
		font-size: 32px;
		line-height: 1.3;
		font-weight: 400;
		font-style: normal;
		padding: 8px;
		background-color: aquamarine;
		border: none;
		margin: 0 0 0 16px;
	}
</style>
