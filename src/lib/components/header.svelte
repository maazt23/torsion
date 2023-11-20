<header>
	<a href="/">Home</a>

	<div class="navbar">

		<div class="navbutton">
			<img src="blog_book.png" alt="">
			<a href="/blog">Blog</a>
		</div>

		<div class="navbutton">
			<img src="about.png" alt="">
			<a href="/about">About</a>
		</div>

		<div class="navbutton">
			<img src="contac.png" alt="">
			<a href="/contact">Contact</a>
		</div>

	</div>

</header>

<style>
	header {
		padding: 1rem;
		background: #1F1717;
		display: flex;
		flex-wrap: wrap;
		justify-content: space-between;
	}

	ul {
		margin: 0;
		list-style-type: none;
		display: flex;
		gap: 1rem;
	}

	a {
		text-decoration: none;
		color: #FCF5ED;
	}

	.navbutton{

		display: flex;
		flex-flow: row wrap;
		align-items: center;
		justify-content: center;

		gap: 0.3rem;

	}

	.navbar{

		display: flex;
		flex-flow: row wrap;
		background-color: #1F1717;
		max-height: fit-content;

		gap: 2rem;
		
	}

	img{
		max-width: 2rem;
	}
</style>