<template>
	<section class="hero is-small is-primary is-relative">
		<div class="hero-body">
			<div class="">
				<p class="title block mb-6">
					Yui
				</p>
				<p class="subtitle">
					A multiplayer
					<span class="has-text-weight-bold"
						>"Guess the Anime Song Quiz"</span
					>
					quiz. to compete against your friends, and others
				</p>
			</div>
		</div>
		<img src="@/assets/svg/bottom.svg" alt="image" />
	</section>
</template>

<style lang="scss">
.subtitle {
	max-width: 60ch;
	line-height: 2rem !important;
}
img {
	width: 100%;
	height: 100%;
	object-fit: contain;
	object-position: center;
}
</style>
