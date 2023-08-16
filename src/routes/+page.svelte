<script>
	import welcome from '$lib/images/JenSunCloud.svg';
	import SocialIcons from '@rodneylab/svelte-social-icons';
	import './styles.css';
</script>

<svelte:head>
	<title>Jen from Modest</title>
	<meta name="links to connect with Jen from Modest" content="Jen from Modest Link Tree" />
</svelte:head>

<section>
	<h1 class="name">
		<span class="welcome">
			<picture>
				<img src={welcome} alt="Welcome" />
			</picture>
		</span>
		Jen from Modest
	</h1>
	<div class="socials">
		<span>
			<a
				href="https://www.facebook.com/modestcreativestudio/"
				target="_blank"
				rel="noopener noreferrer"
				><SocialIcons network="facebook" fgColor="#171539" bgColor="#c9974e" /></a
			>
			<a href="https://www.instagram.com/creativelymodest" target="_blank" rel="noopener noreferrer"
				><SocialIcons network="instagram" fgColor="#171539" bgColor="#c9974e" /></a
			>
			<a href="https://twitter.com/modestlytechy" target="_blank" rel="noopener noreferrer"
				><SocialIcons network="twitter" fgColor="#171539" bgColor="#c9974e" /></a
			>
			<a href="https://github.com/modestco" target="_blank" rel="noopener noreferrer"
				><SocialIcons network="github" fgColor="#171539" bgColor="#c9974e" /></a
			>
		</span>
	</div>

	<button class="linkbutton">
		<a href="https://www.patreon.com/ModestlyTechy/" target="_blank" rel="noopener noreferrer">
			Modestly Techy
		</a>
	</button>

	<button class="linkbutton">
		<a href="https://modestlycreativeco.etsy.com" target="_blank" rel="noopener noreferrer">
			Modest on Etsy
		</a>
	</button>

	<button class="linkbutton">
		<a href="https://ko-fi.com/modestlytechy/" target="_blank" rel="noopener noreferrer">
			Buy Me a Beer
		</a>
	</button>
	<button class="linkbutton">
		<a href="https://jenluchka.com" target="_blank" rel="noopener noreferrer">
			Freelance Portfolio
		</a>
	</button>
	<button class="linkbutton">
		<a href="mailto:info@modestco.ca" target="_blank" rel="noopener noreferrer"> Email Me </a>
	</button>
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	h1 {
		width: 100%;
		font-family: var(--font-heading);
	}

	.welcome {
		display: block;
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}
	.linkbutton {
		background-color: var(--color-bg-0);
		color: white;
		border: none;
		border-radius: 1rem;
		padding: 0.5rem 1rem;
		font-size: 1rem;
		font-weight: 300;
		cursor: pointer;
		margin-bottom: 0.5rem;
		transition: background-color 0.2s ease-in-out;
	}

	.linkbutton:hover {
		border: none;
		border-radius: 1rem;
		padding: 0.5rem 1rem;
		font-size: 1rem;
		font-weight: 300;
		cursor: pointer;
		transition: background-color 0.2s ease-in-out;
	}
	.name,
	.socials {
		margin-bottom: 0.5rem;
	}
</style>
