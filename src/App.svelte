<script>
	let people = [{name: "yoshi", age: 81},
	{name: "parth", age: 19}];
</script>

<main>
	<h1>Hello {people[0].name}!</h1>
	<p>You are {people[0].age} years old</p>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>