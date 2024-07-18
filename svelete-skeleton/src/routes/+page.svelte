<!-- YOU CAN DELETE EVERYTHING IN THIS PAGE -->
<script>
	let visible = true;
</script>
<div class="container h-full mx-auto flex justify-center items-center">
	<div class="space-y-5">
	
{#if visible}
<aside class="alert variant-ghost">
	<!-- Icon -->
	<div>(icon)</div>
	<!-- Message -->
	<div class="alert-message">
		<h3 class="h3">(title)</h3>
		<p>You prompt has been stored into db </p>
	</div>
	<!-- Actions -->
	<div class="alert-actions">(buttons)</div>
</aside>
{/if}
		
		<div class="variant-filled-primary p-10 items-center justify-center text-center w-30">primary</div>
		<h1 class="h1">Let's get cracking bones!</h1>
		<p>Start by exploring:</p>
		<ul>
			<li><code class="code">/src/routes/+layout.svelte</code> - barebones layout</li>
			<li><code class="code">/src/app.postcss</code> - app wide css</li>
			<li>
				<code class="code">/src/routes/+page.svelte</code> - this page, you can replace the contents
			</li>
		</ul>
	</div>
</div>
