<script lang="ts">
	import { steps } from '$sharedData';
	// import {  } from '$widgets';
	// import {  } from '$entities';

	
</script>

<div id="process" class="process">
	<div class="div-solutions_3col">
		<div class="div-solutions_text-lower">
			<div class="heading-2">
				<div class="clients-title block-process">Proces <br />krok po kroku</div>
			</div>
			<div class="div-text-size-regular-2">
				<div class="process-left-text">
					Będę Ci w pełni towarzyszył krok po kroku w tworzeniu i realizacji animacji lub
					gamifikacji. Mogę pomóc od fazy rozwoju do modyfikacji istniejącego rozwiązania i zapewnić
					dalsze wsparcie i rozwój.
				</div>
			</div>
		</div>

		<div class="divw-node-c77c76b5-e350-c40b-5615-101986df68c2-5611c371">
			{#each steps as { title, desc }}
				<div class="div-solutions_benefit-item-2">
					<div class="_64108b93e9fd6c4072053920_frame2012-svg">
						<img
							src="images/service.svg"
							loading="lazy"
							alt=""
							class="vectors-wrapper-10 h-6 w-18"
						/>
					</div>
					<div class="div-solution_benefit-text-2">
						<div class="heading-3-audience-traits">{title}</div>
						<div class="div-text-size-regular-4 flex flex-col">
							{#each desc as text}
								<div class="flex flex-row">
									<img
										src="images/step.svg"
										loading="lazy"
										alt=""
										class="step-item h-5 w-5 mr-2"
									/>
									<p class="error-6fedea72-2553-77c0-fd94-8b2bfb30fd8c mb-3">
										{text}
									</p>
								</div>
							{/each}
						</div>
					</div>
				</div>
			{/each}
		</div>
	</div>
</div>

<style lang="postcss">
	.step-item {
	grid-column-gap: 0px;
	grid-row-gap: 0px;
	object-fit: cover;
	justify-content: center;
	align-items: center;
	display: flex;
}

	.vectors-wrapper-10 {
	grid-column-gap: 0px;
	grid-row-gap: 0px;
	object-fit: cover;
	justify-content: center;
	align-items: center;
	display: flex;
}

@media screen and (max-width: 479px) {
.step-item {
		width: 22px;
	}
	.vectors-wrapper-10 {
		width: 22px;
	}
}

</style>
