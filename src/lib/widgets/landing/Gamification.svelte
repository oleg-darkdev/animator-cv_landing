<script lang="ts">
	// import {  } from '$shared';
	// import {  } from '$widgets';
	// import {  } from '$entities'
</script>

<section class="div-block-14">
	<div class="process-image-wrapper">
		<!-- 			srcset="images/6485c1f83e0ecc1f1a2b0309_Group%2034%20%282%29-p-500.png 500w, images/6485c1f83e0ecc1f1a2b0309_Group%2034%20%282%29-p-800.png 800w, images/6485c1f83e0ecc1f1a2b0309_Group%2034%20%282%29-p-1080.png 1080w, images/6485c1f83e0ecc1f1a2b0309_Group%2034%20%282%29-p-1600.png 1600w, images/6485c1f83e0ecc1f1a2b0309_Group%2034%20%282%29-p-2000.png 2000w, images/6485c1f83e0ecc1f1a2b0309_Group%2034%20%282%29-p-2600.png 2600w, images/6485c1f83e0ecc1f1a2b0309_Group%2034%20%282%29-p-3200.png 3200w, images/6485c1f83e0ecc1f1a2b0309_Group%2034%20%282%29.png 3856w"
 -->
		<img
			src="images/bicycle-bg.svg"
			loading="lazy"
			sizes="(max-width: 479px) 78vw, 62vw"
			alt="how to build a game"
			class="image-20"
		/>
	</div>
</section>

<section class="benefits">
	<!-- Why should you use gamification for your corporate events? -->
	<h2 class="heading-7 white">Dlaczego warto korzystać z grywalizacji podczas wydarzeń?</h2>
	<div class="w-layout-hflex benefits-1-line">
		<div class="benefit">
			<div class="benefits-content-wrapper">
				<div class="industry-title color">Wzrost zaangażowania uczestników</div>
				<div class="text-block-14">
					Działania oparte na grze zwiększają zaangażowanie poprzez nagradzanie pracy zespołowej,
					kreatywności i zabawy! 🏆
				</div>
			</div>
			<div class="benefits-img-wrapper upper">
				<img
					src="images/649bec57942109f7fdf74fb8_Frame%2081.svg"
					loading="lazy"
					alt="improve engagement"
					class="employee-engagement-img"
				/>
			</div>
		</div>
		<div class="benefit">
			<div class="benefits-content-wrapper">
				<div class="industry-title color">Zwiększenie motywacji</div>
				<div class="text-block-14">
					Motywowanie uczestników poprzez wspieranie współpracy, nauki i uznania👏
				</div>
			</div>
			<div class="benefits-img-wrapper second">
				<img
					src="images/649bde29259279b96fdb2e1c_Group%2037.svg"
					loading="lazy"
					alt="boost motivation"
					class="boost-motivation-img"
				/>
			</div>
		</div>
	</div>

	<div class="w-layout-hflex benefits-2-line">
		<div class="benefit">
			<div class="benefits-img-wrapper upper">
				<img
					src="images/649bf2395950c02faf4407b1_Frame%2082.svg"
					loading="lazy"
					alt="gamified training"
					class="training-img"
				/>
			</div>
			<div class="benefits-content-wrapper gutter">
				<div class="industry-title color">Łatwiejsze szkolenie i coaching</div>
				<div class="text-block-14">
					Zaangażuj uczestników w interaktywne i wciągające scenariusze.
				</div>
			</div>
		</div>
		<div class="benefit two">
			<div class="benefits-content-wrapper">
				<div class="industry-title color">Optymalizacja procesów operacyjnych</div>
				<div class="text-block-14">
					Zoptymalizuj je, zachęcając uczestników do innowacji, współpracy i rozwiązywania
					problemów.
				</div>
			</div>
			<div class="benefits-img-wrapper third">
				<img
					src="images/649b4aef72789a284ff78497_Frame%2079%20%281%29.svg"
					loading="lazy"
					alt=""
					class="optimize-process-img"
				/>
			</div>
		</div>
	</div>
</section>

<style lang="postcss">
	.benefits {
		height: auto;
		background-color: #000;
		border-radius: 18px;
		margin-bottom: 112px;
		margin-left: 11%;
		margin-right: 11%;
		padding: 56px 36px;
		overflow: hidden;
	}

	.benefit {
		width: auto;
		min-height: 210px;
		grid-column-gap: 12px;
		grid-row-gap: 12px;
		background-color: #ffefc4;
		border-radius: 12px;
		justify-content: space-between;
		align-items: flex-start;
		padding: 36px;
		display: flex;
		overflow: hidden;
	}

	.benefit.two {
		grid-column-gap: 16px;
		grid-row-gap: 16px;
		background-color: #ffefc4;
		align-items: flex-end;
		padding-top: 36px;
		padding-bottom: 0;
	}

	.benefits-1-line {
		width: 100%;
		grid-column-gap: 16px;
		grid-row-gap: 16px;
		grid-template-rows: auto;
		grid-template-columns: 1fr 45%;
		grid-auto-columns: 1fr;
		align-items: center;
		margin-top: 0;
		display: grid;
	}

	.benefits-img-wrapper {
		width: 160px;
		height: 160px;
		min-width: 160px;
		background-color: #fff;
		border-bottom-right-radius: 12px;
		border-bottom-left-radius: 12px;
		justify-content: flex-start;
		align-items: flex-start;
		margin-left: 0;
		display: flex;
	}

	.benefits-img-wrapper.second {
		width: 172px;
		height: 176px;
		min-width: 172px;
		border: 2px solid #000;
		border-bottom-width: 1px;
		border-radius: 12px 12px 0 0;
		padding-top: 26px;
		padding-left: 26px;
		padding-right: 26px;
	}

	.benefits-img-wrapper.third {
		width: 172px;
		height: 210px;
		min-width: 172px;
		border-left: 2px solid #000;
		border-right: 2px solid #000;
		border-bottom-right-radius: 0;
		border-bottom-left-radius: 0;
		padding-top: 42px;
		padding-left: 18px;
		padding-right: 18px;
	}

	.benefits-img-wrapper.upper {
		height: 176px;
		min-width: 172px;
		border-bottom: 2px solid #000;
		border-left: 2px solid #000;
		border-right: 2px solid #000;
		margin-top: -36px;
		padding: 0;
		overflow: hidden;
	}

	.benefits-2-line {
		width: 100%;
		grid-column-gap: 16px;
		grid-row-gap: 16px;
		grid-template-rows: auto;
		grid-template-columns: 45% 1fr;
		grid-auto-columns: 1fr;
		align-items: center;
		margin-top: 16px;
		display: grid;
	}

	.benefits-content-wrapper {
		min-height: 180px;
		flex-direction: column;
		justify-content: flex-start;
		align-self: flex-start;
		align-items: flex-start;
		padding-right: 0;
		display: flex;
	}

	.boost-motivation-img {
		width: 100%;
	}

	.employee-engagement-img {
		width: 96%;
	}

	.training-img {
		width: auto;
		min-width: 100%;
		overflow: hidden;
	}

	@media screen and (max-width: 991px) {
		.benefits {
			margin-left: 5%;
			margin-right: 5%;
		}

		.benefit {
			grid-column-gap: 24px;
			grid-row-gap: 24px;
		}

		.benefits-1-line {
			grid-column-gap: 8px;
			grid-row-gap: 8px;
			grid-template-rows: auto auto;
			grid-template-columns: 1fr;
		}

		.benefits-2-line {
			grid-column-gap: 8px;
			grid-row-gap: 8px;
			grid-template-rows: auto auto;
			grid-template-columns: 1fr;
			margin-top: 8px;
		}
	}

	@media screen and (max-width: 767px) {
		.benefits {
			margin-bottom: 64px;
			padding: 36px 24px;
		}

		.benefit {
			min-height: 200px;
			padding-top: 22px;
		}
	}

	@media screen and (max-width: 479px) {
		.benefits-img-wrapper.second {
			width: 90px;
			height: 90px;
			min-width: 90px;
			border-bottom-width: 2px;
			border-bottom-right-radius: 12px;
			border-bottom-left-radius: 12px;
			margin-left: auto;
			padding: 2px;
		}

		.benefits-img-wrapper.third {
			width: 90px;
			height: 90px;
			min-width: 90px;
			border-top: 2px solid #000;
			border-bottom: 2px solid #000;
			border-radius: 12px;
			padding: 2px;
		}

		.benefits-img-wrapper.upper {
			width: 90px;
			height: 90px;
			min-width: 90px;
			border-top: 2px solid #000;
			border-top-left-radius: 12px;
			border-top-right-radius: 12px;
			margin-top: 0;
		}

		.benefits-content-wrapper {
			height: auto;
			grid-column-gap: 6px;
			grid-row-gap: 6px;
		}
	}
</style>
