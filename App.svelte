<script>
 import Button from "./Button.svelte";
 let val1 = 0;
 let val2 = 0;
 let val3 = 0;
</script>

<style>
  main {
    font-family: sans-serif;
    text-align: center;
  }
  .row {
    width: 100%;
    display: flex;
    flex-direction: row;
    justify-content: center;
    margin: 10px;
  }
  .block {
    width: 120px;
  }
</style>

<main>
<div class="row" >
<div class="block"><p>val1: {val1}</p> </div>
<div class="block"><Button /></div>
</div>

<div class="row" >
<div class="block"><p>val2: {val2}</p> </div>
<div class="block"><Button /></div>
</div>

<div class="row" >
<div class="block"><p>val3: {val3}</p> </div>
<div class="block"><Button /></div>
</div>

	
</main>