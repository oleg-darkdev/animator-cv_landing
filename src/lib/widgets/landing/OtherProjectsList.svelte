<script lang="ts">
	import { projects } from '$sharedData';
	// import {  } from '$widgets';
	// import {  } from '$entities'
</script>

<section class="section">
	<div class="div-block-23">
		<h2 class="heading-7 cases">and more of them...</h2>
	</div>
	<div class="container-5 pb-10">
		<div class="features-right">
			{#each projects as project}
				<div class="features-card {project.class}">
					<div class="w-layout-grid case-card">
						<div class="slider-5 w-slider">
							<!-- 							id="w-node-_399bd6cd-db27-17cb-3cd8-add4fe7e39ad-5f1f18df"
 -->
							<div class="w-slider-mask">
								<!-- img tu -->
								<div class="slide-6 {project.class} w-slide"></div>
								<!-- <div class="slide-7 w-slide"></div> -->
								<!-- <div class="slide-8 w-slide">
									<div style="padding-top:56.17021276595745%" class="w-embed-youtubevideo youtube">
										<iframe
											src=""
											frameborder="0"
											style="position:absolute;left:0;top:0;width:100%;height:100%;pointer-events:auto"
											allow="autoplay; encrypted-media"
											title="Le Joueur manquant - team building - TEASER 2"
										></iframe>
									</div>
								</div> -->
							</div>
							<!-- <div class="w-slider-arrow-left">
								<div class="icon-3 w-icon-slider-left"></div>
							</div>
							<div class="w-slider-arrow-right">
								<div class="icon-2 w-icon-slider-right"></div>
							</div>
							<div class="slide-nav-2 w-slider-nav w-round w-num"></div> -->
						</div>
						<!-- 							id="w-node-c9e8c90b-34c1-8010-0b97-6882c496b533-5f1f18df"
 -->
						<div class="case-iamge-wrap"></div>
						<!-- 							id="w-node-_96188501-fda1-318f-fd6e-bd7a94b70d27-5f1f18df"
 -->
						<div class="w-layout-grid grid-18">
							<div class="div-block-20">
								<div class="div-block-19">
									<div class="div-block-22">
										{#each project.tags as tag}
											<div class="caps-text {project.class}">
												{tag}
											</div>
										{/each}
									</div>
									<div class="tab-heading-for-content">
										<h3 class="heading-6">{project.title}</h3>
									</div>
								</div>
								<div class="div-block-21">
									<!-- <div class="made-for">Made with Kronos Experience</div> -->
									<img
										src={project.logo}
										loading="lazy"
										alt="{project.title} logo"
										class="image-30 circle"
									/>
								</div>
							</div>
							<div class="case-description">
								{project.shortDesc}
							</div>
							<div class="case-description">
								{#each project.desc as desc}
									<p>{desc}</p>
								{/each}
							</div>
							<!-- id="w-node-edf97139-dbca-f49c-8e85-5f14a8704e53-5f1f18df"  -->
							<div class="div-block-17">
								<img src={project.infoImg} loading="lazy" alt="project info" />
							</div>
							<!-- 									id="w-node-_3e5a7ee6-3fd9-0922-2ae5-3f8f979fcb2e-5f1f18df"
 -->
							<!-- 								id="w-node-_479bdc3f-ba2e-1379-ac1a-551002e31a10-5f1f18df"
 -->
							<!-- <a href="/" target="_blank" class="read-article">Learn more</a> -->
						</div>
					</div>
				</div>
			{/each}
		</div>
		<!-- <div class="features-wrapper">
			<div class="features-left"></div>
		</div> -->
	</div>
</section>

<style lang="postcss">
	.features-card.second {
		top: 165px;
	}

	.features-card .third {
		top: 180px;
	}

	.caps-text .second {
		color: #fd6f00;
	}

	.caps-text .second,
	.caps-text.third,
	.caps-text.fourth,
	.caps-text.fifth,
	.caps-text.sixth,
	.caps-text.seventh,
	.caps-text.eighth {
		margin-top: 0;
		margin-bottom: 14px;
		padding-top: 0%;
		font-size: 12px;
		display: flex;
	}

	.slide-6 {
		color: #000;
		background-image: url('/images/648a116abeaeb6c4bc75ce95_Screen-Shot-2022-03-01-at-9.01%201.png');
		background-position: 0 0;
		background-size: cover;
		border-radius: 12px;
	}

	.slide-6.second {
		background-image: url('/images/648b08e909b094066059b72d_Frame%2072%20%281%29%20%281%29.png');
	}

	.slide-6.third {
		background-image: url('/images/648b44c47b4cddf09a125804_Frame%2075%20%281%29.png');
	}

	.slide-6.fourth {
		background-image: url('/images/648b52351f6842e01751d037_image%20%288%29.png');
	}
	.slide-6.fifth {
		background-image: url('/images/648b52351f6842e01751d037_image%20%288%29.png');
	}
	.slide-6.sixth {
		background-image: url('/images/648b52351f6842e01751d037_image%20%288%29.png');
	}
	.slide-6.seventh {
		background-image: url('/images/648b52351f6842e01751d037_image%20%288%29.png');
	}
	.slide-6.eighth {
		background-image: url('/images/648b52351f6842e01751d037_image%20%288%29.png');
	}

	@media screen and (max-width: 991px) {
		.caps-text .second,
		.caps-text.third,
		.caps-text.fourth,
		.caps-text.fifth,
		.caps-text.sixth,
		.caps-text.seventh,
		.caps-text.eighth {
			font-size: 0.7em;
		}
	}
</style>
