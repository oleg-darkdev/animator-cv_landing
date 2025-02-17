<script lang="ts">
	import { clients } from '$sharedData';
	// import {  } from '$widgets';
	// import {  } from '$entities';
</script>

<section class="container-2 div-block-7">
	<div class="w-layout-grid grid-10">
		<h2 class="clients-title">
			<!--  <span class='emoji'>✨</span>  -->
			Ponad 15 firm <span class="emoji">🏢</span> stworzyło grywalizację i wrażenia animacyjne
			<span class="emoji">🥳</span> z moją pomocą
		</h2>
		<div class="subtitle">
			W ciągu ostatnich <span class="emoji"> 5️⃣</span> lat miałem zaszczyt współpracować ze
			świetnymi firmami na kilku kontynentach 🌍, aby pomoc w ich
			działaniach i wydarzeniach.
		</div>
		<div class="flex max-w-5xl flex-wrap items-center justify-center gap-4">
			{#each clients as { text, link, logo, brandColor }}
				<a href={link} target="_blank">
					<img src="images/clients/{logo}" loading="lazy" alt="{text} logo" class={brandColor} />
				</a>
			{/each}
		</div>
	</div>
</section>

<style lang="postcss">
</style>
