<button on:click>
	<slot />
</button>

<style>
	button {
		@apply mr-2 mb-2 rounded-lg bg-blue-700 px-5 py-2.5 text-sm font-medium text-white hover:bg-blue-800 focus:ring-4 focus:ring-blue-300;
	}
</style>
