<script lang="ts">
	// import {  } from '$shared';
	// import {  } from '$widgets';
	// import {  } from '$entities';

	import { blur, crossfade, draw, fade, fly, scale, slide } from 'svelte/transition';

	let showAnswer = $state(false);

	let { q, a } = $props();
</script>

<div class="accordion-item---brix tabs-accordion---brix">
	<div onclick={() => (showAnswer = !showAnswer)} class="faq-question-bar w-inline-block">
		<div class="question-title">
			<span class="emoji">⁉️</span>
			{q}
		</div>
		<div class="faq-circle">
			<img src="images/647c6bd97783a706163e1707_plus.svg" alt="" class="plus-icon" />
		</div>
	</div>

	{#if showAnswer}
		<div transition:fade class="accordion-content---brix">
			{#each a as answer}
				<p class="accordion-paragraph---brix">
					{answer}
				</p>
			{/each}
		</div>
	{/if}
</div>

<style lang="postcss">
</style>
