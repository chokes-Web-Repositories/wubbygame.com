<main>
	<div class="container">
		<img class="logo" src="/title.png" alt="title" draggable="false" />
		<br />
		<span style="font-size: 38px; font-weight: bold;">Push the boundaries of the imaginable</span>
		<br />
		<a
			style="background-color: #00b06f; border: none; color: white;"
			class="button"
			href="https://www.roblox.com/games/start?placeId=12519560096"
		>
			<img src="/icons/play-solid.svg" width="19" alt="book" />
			Play
		</a>
		<a
			style="background-color: #5561f5; border: none; color: white;"
			class="button"
			href="discord.gg/invite/YHtthk2dYX"
		>
			<img src="/icons/discord.svg" width="19" alt="book" />
			Discord
		</a>
		<a class="button" href="//www.roblox.com/games/12519560096">
			<img src="/icons/image-solid.svg" width="16" alt="book" />
			View game details
		</a>
		<a class="button" href="//wiki.wubbygame.com">
			<img src="/icons/book-solid.svg" width="19" alt="book" />
			Wiki
		</a>
		<a class="button" href="//forums.wubbygame.com">
			<img src="/icons/book-solid.svg" width="19" alt="book" />
			Forums
		</a>
	</div>
</main>

<style lang="scss">
	/* the funny animated dots */
	@keyframes move {
		0% {
			background-position: 0 0;
		}
		100% {
			background-position: 0 -20px;
		}
	}

	:root {
		overflow: hidden;
		margin: 0;
		padding: 0;
		width: 100%;
	}

	:root::before {
		font-family: 'Figtree', serif;
		background-color: #191919;
		color: white;
		position: relative;
		overflow: hidden;
		display: flex; /* Add this */
		flex-direction: column; /* Add this */
		justify-content: center; /* Add this */
		align-items: center; /* Add this */
		height: 100%; /* Add this */
	}
	:root::before {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100%;
		position: relative;
		overflow: hidden;
		color: #ffffff;

		content: '';
		position: absolute;
		width: 300%;
		height: 300%;
		top: -100%;
		left: -100%;
		z-index: -1;
		background-image: radial-gradient(#2c2c2c 1.7px, transparent 1px);
		background-size: 20px 20px;
		animation: move 1s linear infinite;
		transform: rotate(5deg);
	}

	:root {
		font-family: 'Figtree';
		background-color: rgb(24, 24, 24);
		color: white;
	}

	.logo {
		max-width: 100%;
		height: auto;
	}

	.container {
		position: absolute;
		text-align: center;
		top: 50%;
		left: 50%;
		transform: translate(-50%, -50%);
	}

	.button {
		font-family: 'Figtree';
		background-color: transparent;
		border: 1px solid #bdbebe;
		color: hsla(0, 0%, 100%, 0.7);
		margin: 5px;
		padding: 10px 20px;
		border-radius: 8px;
		vertical-align: middle;
		text-decoration: none;
		font-size: 18px;
		display: inline-block;
		transition: background-color 0.3s, color 0.3s;

		&:hover {
			border: 1px solid #ffffff;
		}

		& img {
			vertical-align: middle;
		}
	}
</style>
