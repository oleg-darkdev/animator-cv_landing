<script lang="ts">
	import { faq } from '$sharedData';
	// import {  } from '$widgets';
	import { FaqCard } from '$entitiesLanding'

</script>

<h2 class="clients-title "><span class='emoji'>⁉️</span>  Często pytano mnie o to <span class='emoji'>⁉️</span></h2>
<section class="faq1">
	{#each faq as { a, q }}
		<FaqCard {a} {q}/>
	{/each}
</section>

<style lang="postcss">
</style>
