<script>
	let count = 0;

	function handleClick() {
	  count += 1;
	}

	console.log("hello");
</script>

<style>
	button {
	  background: #ff3e00;
	  color: white;
	  border: none;
	  padding: 10px 12px;
	  border-radius: 3px;
	}
</style>

<button on:click={handleClick}>
  Click
</button>