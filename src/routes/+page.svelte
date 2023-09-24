<main>
	<div class="container">
		<img class="logo" src="/title.png" alt="title" draggable="false" />
		<br />
		<span style="font-size: 38px; font-weight: bold;">Push the boundaries of the imaginable</span>
        <br>
        <a style="background-color: #00b06f; border: none; color: white;" class="button" href="https://www.roblox.com/games/start?placeId=12519560096">
			<img src="/icons/play-solid.svg" width="19" alt="book" />
			Play
		</a>
        <a style="background-color: #5561f5; border: none; color: white;" class="button" href="discord.gg/invite/YHtthk2dYX">
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
