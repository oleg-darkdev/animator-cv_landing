<script lang="ts">
	import { forWhom } from '$sharedData';
	// import {  } from '$widgets';
	// import {  } from '$entities'
</script>

<section class="blog-industries-wrapper">
	<!-- <h2 class="forWhom-title">Find out more about gamified experiences</h2>
	<div class="subtitle">
		Have a look at my blog articles which explain different aspects of gamification, AI application
		for games, team building ideas and more.
	</div>
	<div class="industry-line-wrapper-copy">
		<div
			id="w-node-_368a0c60-63c6-4ced-64b9-29fed102a9d1-5f1f18df"
			class="w-layout-grid sing-e-blog-grid"
		>
			<div id="w-node-_8d18b4e5-18b8-3fdf-e8d8-d223c9f1a17b-5f1f18df" class="blog-photo-wrap"></div>
			<div id="w-node-f59a9d4e-507d-7b85-f092-718bc23327b0-5f1f18df" class="blog-tag tag1">
				<div id="w-node-bffe9153-6d00-cc48-dc32-05586dce4378-5f1f18df" class="text-block-5">AI</div>
			</div>
			<h1
				id="w-node-_8de2d13e-f014-a7f5-e9db-514cb46ebdec-5f1f18df"
				class="blog-article-description"
			>
				Revolutionizing Game Creation: The Impact of AI
			</h1>
			<div id="w-node-b3fa854c-fe2a-1e6a-b288-88f97ef44460-5f1f18df" class="text-block-4">
				If you’re interested in tech news, you might hear a lot about Artificial Intelligence (also
				known as AI) lately.
			</div>
			<a
				id="w-node-_019c19a5-efa2-3ffc-f494-e6d72b8eff96-5f1f18df"
				href="https://loquiz.com/2023/03/10/game-creation-impact-ai/"
				target="_blank"
				class="read-article">Read article</a
			>
		</div>
		<div
			id="w-node-_2f93bc8a-b6cb-e0b2-6477-bb8cf4d3c1a8-5f1f18df"
			class="w-layout-grid sing-e-blog-grid"
		>
			<div
				id="w-node-_5ff4e447-a6ce-2e70-cfff-e0f8c9cc480f-5f1f18df"
				class="blog-photo-wrap second"
			></div>
			<div id="w-node-_2f93bc8a-b6cb-e0b2-6477-bb8cf4d3c1aa-5f1f18df" class="blog-tag">
				<div id="w-node-_2f93bc8a-b6cb-e0b2-6477-bb8cf4d3c1ab-5f1f18df" class="text-block-5">
					Corporate
				</div>
			</div>
			<h1
				id="w-node-_2f93bc8a-b6cb-e0b2-6477-bb8cf4d3c1ad-5f1f18df"
				class="blog-article-description"
			>
				25 Office team building scavenger hunt ideas to test now!
			</h1>
			<div id="w-node-_2f93bc8a-b6cb-e0b2-6477-bb8cf4d3c1af-5f1f18df" class="text-block-4">
				Most of us spend our whole workdays in an office. We do our best to deliver the best work.
				Thus, should a workplace be a dull place to be? Absolutely not.
			</div>
			<a
				id="w-node-_2f93bc8a-b6cb-e0b2-6477-bb8cf4d3c1b1-5f1f18df"
				href="https://loquiz.com/2022/04/07/25-office-team-building-scavenger-hunt-ideas/"
				target="_blank"
				class="read-article">Read article</a
			>
		</div>
		<div class="w-layout-grid sing-e-blog-grid">
			<div
				id="w-node-_7b4eb344-d80c-ba6f-13d0-09a2a7adbc7a-5f1f18df"
				class="blog-photo-wrap third"
			></div>
			<div id="w-node-db1b4925-25f1-9456-1c3a-545345e9528a-5f1f18df" class="blog-tag tag3">
				<div id="w-node-db1b4925-25f1-9456-1c3a-545345e9528b-5f1f18df" class="text-block-5">
					Tours
				</div>
			</div>
			<h1
				id="w-node-db1b4925-25f1-9456-1c3a-545345e9528d-5f1f18df"
				class="blog-article-description"
			>
				Create your own Audio Tour (that you can sell) in 5 steps
			</h1>
			<div id="w-node-db1b4925-25f1-9456-1c3a-545345e9528f-5f1f18df" class="text-block-4">
				With the ongoing crisis, some types of events are still going very well. I have one in mind:
				the local GPS activities for individual people.
			</div>
			<a
				id="w-node-db1b4925-25f1-9456-1c3a-545345e95291-5f1f18df"
				href="https://loquiz.com/2021/03/15/create-your-own-audio-tour/"
				target="_blank"
				class="read-article">Read article</a
			>
		</div>
	</div> -->

	<!--  i animacje  -->
	<div class="industries">
		<h2 class="forWhom-title industriess mx-auto max-w-2xl text-center">
			Jakie branże mogą skorzystać z moich usług <span class='emoji'>🎉</span>  animacji i grywalizacji <span class='emoji'>🧩</span>
		</h2>

		<div class="subtitle mx-auto max-w-2xl">
			<p class="">
				Niezależnie od dziedziny, w której pracujesz, grywalizacja jest kluczem do zwiększenia
				zaangażowania 🤩, motywacji 🤪 i skuteczności 🧐, i sukcesu 😎
			</p>
			<p>
				Wejdź do świata, w którym praca z ludźmi i grywalizacja płynnie się przeplatają i obserwuj,
				jak twoja praca z ludźmi zmienia się na twoich oczach 👀
			</p>
		</div>
		<div class="industry-line-wrapper">
			{#each forWhom as { title, shortDesc, icon, brandColor, imgClass, emoji }}
				<div class=" industry-block {brandColor}">
					<div class="hr-logo">
						<img src={icon} loading="lazy" alt="" class={imgClass} />
					</div>
					<div class="hr-content">
						<div class="industry-title">{title} <span class='emoji'>{emoji}</span></div>
						<div class="text-block-3">{shortDesc}</div>
					</div>
				</div>
			{/each}

			<div class="industry-block empty">
				<div class="hr-logo"></div>
				<div class="hr-content">
					<!-- You name it! -->
					<div class="industry-title">Jak zwał, tak zwał!</div>
					<div class="text-block-3">
						Dostosowuję grywalizację 🧩 do każdej istniejącej działalności!
					</div>
				</div>
			</div>
		</div>
	</div>
</section>

<!-- 

<h2 class="forWhom-title">You can test some of my games just now!</h2>
<div id="ready-games" class="test-games">
	<div class="subtitle testgames">
		To do so, <br />1. Download the Loquiz app (
		<a href="https://play.google.com/store/apps/details?id=ee.loquiz&hl=en" target="_blank"
			>Android</a
		>
		& <a href="https://apps.apple.com/us/app/loquiz/id575826783" target="_blank">iOS</a>), open it
		<br />2. Accept all the permission (feel free to uninstall the app after testing a game)
		<br />3. Through the Loquiz App (not through your own camera), scan the QR Code which you find
		on the games pages:
	</div>
	<div class="test-games-wrapper">
		<div class="w-layout-grid sing-e-blog-grid testgames">
			<div
				id="w-node-_3c1962a8-f889-b3a6-109e-ca826a97890a-5f1f18df"
				class="test-game-photo-wrapper"
			></div>
			<div
				id="w-node-e1f0b2b2-860e-44e1-9d0c-2aa665119f94-5f1f18df"
				class="w-layout-grid test-game-content"
			>
				<h3
					id="w-node-d79eca00-33ab-4b0d-ad58-2f51b8c4ad13-5f1f18df"
					class="blog-article-description"
				>
					Jule Verne's Last Travel Adventure
				</h3>
				<div id="w-node-d79eca00-33ab-4b0d-ad58-2f51b8c4ad15-5f1f18df" class="text-block-4">
					This game is a story that I created from scratch based on the works of Jules Verne. He
					makes you travel from Nantes to an island in the Pacific using the mythical vehicles of
					his stories!
				</div>
				<a
					id="w-node-d79eca00-33ab-4b0d-ad58-2f51b8c4ad17-5f1f18df"
					href="https://loquiz.com/games/jules-vernes-last-travel/"
					target="_blank"
					class="read-article">Test it out</a
				>
			</div>
		</div>
		<div class="w-layout-grid sing-e-blog-grid testgames">
			<div
				id="w-node-cb795c6f-e02d-c846-5ba0-4b47cc70444c-5f1f18df"
				class="test-game-photo-wrapper second"
			></div>
			<div
				id="w-node-ddd0586d-c451-b7ac-f01f-7d74a9307089-5f1f18df"
				class="w-layout-grid test-game-content"
			>
				<h3
					id="w-node-ddd0586d-c451-b7ac-f01f-7d74a930708a-5f1f18df"
					class="blog-article-description"
				>
					A Virtual Escape Room
				</h3>
				<div id="w-node-ddd0586d-c451-b7ac-f01f-7d74a930708c-5f1f18df" class="text-block-4">
					When we can’t have fun during family/friends meetings for Christmas or New Year Eve as
					before, the virtual can be a solution. So here is a good way to enjoy yourself with your
					relatives now: A virtual escape room to try for free with up to 5 players.
				</div>
				<a
					id="w-node-ddd0586d-c451-b7ac-f01f-7d74a930708e-5f1f18df"
					href="https://loquiz.com/games/%f0%9f%94%a6-the-dark-manor/"
					target="_blank"
					class="read-article">Test it out</a
				>
			</div>
		</div>
		<div class="w-layout-grid sing-e-blog-grid testgames">
			<div
				id="w-node-d9f00d98-d053-7584-bf44-f9490be0896e-5f1f18df"
				class="test-game-photo-wrapper third"
			></div>
			<div
				id="w-node-_510fb207-da24-5ca6-b28a-988666d5a41c-5f1f18df"
				class="w-layout-grid test-game-content"
			>
				<h3
					id="w-node-_510fb207-da24-5ca6-b28a-988666d5a41d-5f1f18df"
					class="blog-article-description"
				>
					Ugly Sweater Escape
				</h3>
				<div id="w-node-_510fb207-da24-5ca6-b28a-988666d5a41f-5f1f18df" class="text-block-4">
					You find yourself locked in a cold room with ugly sweaters. The only way to escape is to
					unlock sweaters... Beware, the temperature is decreasing. You will need these ugly
					sweaters to succeed in this team building game!
				</div>
				<a
					id="w-node-_510fb207-da24-5ca6-b28a-988666d5a421-5f1f18df"
					href="https://loquiz.com/games/ugly-holiday-sweater-escape-game/"
					target="_blank"
					class="read-article">Test it out</a
				>
			</div>
		</div>
	</div>
</div> -->

<style lang="postcss">
	.industry-line-wrapper {
		grid-gap: 4px;
		justify-content: justify-between;
		margin: 0.8em auto 0;
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
	}

	.industry-line-wrapper-copy {
		width: auto;
		max-width: 100%;
		grid-column-gap: 68px;
		grid-row-gap: 68px;
		grid-template-rows: auto;
		grid-template-columns: minmax(200px, 1fr) minmax(200px, 1fr) minmax(200px, 1fr);
		grid-auto-columns: 1fr;
		justify-content: flex-start;
		align-items: flex-start;
		margin: 0 0 112px;
		display: grid;
		overflow: visible;
	}

	@media screen and (max-width: 991px) {
		.industry-line-wrapper-copy {
			grid-column-gap: 24px;
			grid-row-gap: 24px;
			flex-direction: column;
			grid-template-rows: auto auto auto;
			grid-template-columns: minmax(200px, 1fr);
			justify-items: stretch;
			margin-bottom: 5em;
			margin-left: 16vw;
		}
	}
	@media screen and (max-width: 767px) {
		.industry-line-wrapper {
			grid-column-gap: 8px;
			font-size: 12px;
		}
		.industry-line-wrapper-copy {
			width: auto;
			grid-row-gap: 32px;
			margin-left: auto;
		}
	}

	@media screen and (max-width: 479px) {
		.industry-line-wrapper {
			width: 100%;
			grid-row-gap: 8px;
			flex-direction: column;
			margin-top: 0;
		}
		.industry-line-wrapper-copy {
			width: auto;
			grid-row-gap: 38px;
		}
	}
</style>
