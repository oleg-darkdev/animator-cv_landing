<script lang="ts">
	import { navigation } from '$sharedData';
	// import {  } from '$widgets';
	// import {  } from '$entities';

</script>

<div class="navigation w-container">
	<div class="container-for-small-narrow-blocks">
		<div class="small-2"></div>
		<div class="small-3"></div>
		<div class="small-5"></div>
		<div class="div-block-28"></div>
		<div class="small-4"></div>
		<div class="small-6"></div>
	</div>
	<div class="navigation-wrapper">
		<div class="logo-container-nav">
			<!-- <img
				src="images/647a180254c7dbfbed92a642_Group%201.svg"
				loading="lazy"
				alt="two four consulting - game development"
				class="image-21"
			/> -->
		</div>
		<div class="navigation-right-part">
			<!-- w-layout-grid  -->
			<div class="navigation-links">
				{#each navigation as { text, link }}
					<a href={link} class="m-2 link">{text}</a>
				{/each}
				<!-- My work -->
			</div>
			<a href="#contact" class="main-button w-button"> Kontakt ze mną </a>
		</div>
	</div>
</div>

<style lang="postcss">
	
.navigation-links {
	grid-column-gap: 48px;
	grid-template-rows: auto;
	grid-template-columns: auto auto auto;
}


@media screen and (max-width: 767px) {
	.navigation {
		height: 62px;
	}

	.navigation-links {
		grid-column-gap: 16px;
	}
}

@media screen and (max-width: 479px) {
	.navigation {
		height: 66px;
		position: static;
	}

	.navigation-links {
		display: none;
	}
}
</style>
