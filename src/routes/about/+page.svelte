<script>
	import rainbow from '$lib/images/hearts.png';
</script>


<svelte:head>
	<title>About Jen</title>
	<meta name="description" content="About Jen from Modest" />
</svelte:head>

<div class="text-column">
	<h1>About Jen <img src={rainbow} alt="Rainbow" width="50px" /></h1>

	<p>
		Jen is a passionate designer with 15 years of experience spanning across multiple industries.
		Her corporate employment history is focused on Marketing and Graphic Design, with a diploma in
		Business. She has her own brand Modest Design Co. Jen (<em>from Modest</em>) has been building
		outside of her 9-5 since 2012. She recently rebranded MD.co to showcase how far her design
		skills have come, while bringing the brand into 2023 and beyond.
	</p>
	<p>
		Aside from working corporate positions, Jen has thoroughly enjoyed assisting small businesses
		and independent contractors with brand identities, logos, social media support, and a wide range
		of digital and print collateral over the years.
	</p>

	<p>
		Of all Jen's past experiences and accomplishments, being a mother of two humans, a large fuzzy dog, and a wife to a very supportive husband has by far been the best. She sits on the Board of Directors at a local educational institution, and is an Associate Member of the Design Professionals of Canada <a href="https://www.descan.ca" target="_blank" rel="noopener noreferrer">DesCan</a>. 
		
		She is a lover of all things design, and is always looking for new ways to express her
		creativity. She is a self-proclaimed tech expert and loves to teach others who consider
		themselves "not tech savvy" how to use modern technology.
	</p>
</div>
<div class="center">
	<p>
		If you'd like more information on Jen's design services, fill out the intake form by tapping the
		button below:
	</p>
	<button class="aboutbutton">
		<a href="https://docs.google.com/forms/d/16CI6-6b2AM3UsWR1Dz_DjNCdg30_OrkAvb3WA18phTI/edit" target="_blank" rel="noopener noreferrer"
			>Collaborate</a
		>
	</button>
	<p>Alternatively, check out the links on the main page for the other ways to connect with Jen!</p>
</div>

<style>
	.aboutbutton {
		background-color: var(--color-bg-0);
		border: none;
		border-radius: 0.5rem;
		width: 250px;
		cursor: pointer;
		display: inline-block;
		font-size: 1rem;
		font-weight: 300;
		margin: 0.5rem 0;
		padding: 0.5rem 1rem;
		text-align: center;
		text-decoration: none;
		transition: background-color 0.2s ease-in-out;
	}

	.center {
		text-align: center;
	}
</style>
