<script>
    let count =$state(0)
  let double = $derived(count * 2);
</script>

<button onclick={() => count++}>
    clicks: {count}
</button>
<span> doubled is {double}</span>

<style>
    button{
    background-color: rgb(224, 224, 224);
    border-radius: 10px;
    border: solid 0.5px whitesmoke;
    padding: 0.5rem;
    box-shadow: -4px 3px 8px rgb(158, 158, 158);
    cursor: pointer;
}
</style>