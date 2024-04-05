<!-- Customization tailored for the LinkedIn Auto Applier -->

<div class="container h-full mx-auto flex justify-center items-center">
	<div class="space-y-10 text-center flex flex-col items-center">
		<h2 class="h2">Welcome to LinkedIn Auto Applier.</h2>
		<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/81/LinkedIn_icon.svg/2048px-LinkedIn_icon.svg.png" alt="LinkedIn Logo" class="w-20 h-20 mt-4 mb-4"> <!-- Logo added here -->
		<!-- Dynamic Logo -->
		<figure>
			<section class="img-bg" />
			<svg
				class="fill-current transform scale-100"
				xmlns="http://www.w3.org/2000/svg"
				viewBox="0 0 200 200"
				style="color: #0a66c2;"
			>
				<!-- Add a custom SVG that resonates with LinkedIn's theme -->
			</svg>
		</figure>
		<!-- / -->
		<!-- <div class="flex justify-center space-x-2">
			<a
				class="btn variant-filled"
				href="https://yourdocumentation.com/"
				target="_blank"
				rel="noreferrer"
			>
				View Documentation
			</a>
		</div>
		<div class="space-y-2">
			<p>Start by editing:</p>
			<p><code class="code">/src/routes/+layout.svelte</code></p>
			<p><code class="code">/src/routes/+page.svelte</code></p>
		</div> -->
	</div>
</div>

<style lang="postcss">
	figure {
		@apply flex relative flex-col;
	}
	figure svg,
	.img-bg {
		@apply w-64 h-64  ;
	}
	.img-bg {
		@apply absolute z-[-1] rounded-full blur-[50px] transition-all;
		animation: pulse 5s cubic-bezier(0, 0, 0.5) infinite,
			colorShift 5s linear infinite;
	}
	@keyframes colorShift {
		0%, 100% {
			background-color: #0a66c2; /* LinkedIn Blue */
		}
		50% {
			background-color: #2851A3; /* A different shade of blue */
		}
	}
	@keyframes pulse {
		50% {
			transform: scale(1.05); /* Subtle pulse effect */
		}
	}
</style>

