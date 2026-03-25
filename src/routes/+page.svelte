  
<script>
 
  import ClickCounters from "$lib/components/ClickCounters.svelte";
  import ProgressiveSum from "$lib/components/ProgressiveSum.svelte";

  let count= $state(5)
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>

<ClickCounters initialCount={count}/>
<p> count from parent is {count}</p>

<style>
h1{
    color:brown;

}


</style>