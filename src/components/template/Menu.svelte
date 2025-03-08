<script>
	export let titulo = 'Menu';
</script>

<div class="fle flex-col">
	<span class="text-sm font-bold text-zinc-500">{titulo} </span>

	<ul class="flex flex-col">
		<slot></slot>
	</ul>
</div>
