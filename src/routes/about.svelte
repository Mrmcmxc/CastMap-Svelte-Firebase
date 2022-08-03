<div class="about">
	<!-- Local Buddy section -->
	<h1 class="text-5xl font-bold">Developers of CastMap</h1>
	<section class="py-20">
		<div class="flex justify-between mx-auto space-x-24 max-w-7xl">
			<div id="dev" class="relative w-1/2 bg-grey-900">
				<img
					src="/images/mark3.jpg"
					width={232}
					height={232}
					alt="Other 19"
					class="absolute -top-15 -left-12"
					style="border-radius: 20px;"
				/>
				<div>
					<p class="py-4 ma font-bold">Mark Pepere <br /> BSE - Developer</p>
				</div>

				<img
					src="/images/alex.jpg"
					width={235}
					height={235}
					alt="Other 18"
					class="absolute top-32 right-16"
					style="border-radius: 20px;"
				/>
				<p class="shadowfilter py-4 font-bold" id="al">Alex Hughes <br /> BSE - Developer</p>
			</div>
			<div class="flex flex-col space-y-5 w-1/2 z-[2]">
				<h1 class="text-4xl font-bold leading-[84px]">
					<span class="character-gradient">Our Story</span>
				</h1>
				<p class="leading-7">
					The project CastMap is be about recording live data regarding areas that are being fished
					around New Zealand. This information is displayed graphically as stats and heat maps. This
					in turn engages the people fishing and supplies MPI with live data. The longer-term
					outlook for this project is that the application will be hosted on the cloud with a
					built-in SQL database to hold and analyse gathered and exiting data. Currently, we have
					discovered the Ministry of Primary Industries (MPI) conducts research annually detailing
					the current state of fish stock and adjusts quotas to suit. Some documents detail the
					stats that are publicly published. Realistically we can safely assume that the average Joe
					will not read or take much notice of these documents provided by MPI. This is a worthwhile
					project as we can help drive sustainability for the ecosystem around the shores of New
					Zealand. The hope is that this application will be turned into a cloud-based native
					application to help share and collect information that provides education for those who
					use it. While the potential for this web application goes much further the scope will be
					reduced to ensure that the project workload is acceptable for the project timelines.
				</p>
			</div>
		</div>
	</section>
</div>
<style>
	.about {
		padding-top: 10rem;
		padding-left: 5rem;
		padding-right: 5rem;
		text-align: center;
		display: block;
		margin: 20px auto;
	}
	#al {
		position: absolute;
		top: 23rem;
		right: 115px;
	}

	.ma {
		position: absolute;
		top: 14rem;
		right: 460px;
	}

	#dev {
		top: 8rem;
		z-index: 1;
	}

</style>
