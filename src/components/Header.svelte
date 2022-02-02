<script>
    let name = "world";
    function assign() {
        name = "test";
    }
    export let age = 21
    export let world = "world"
</script>

<h1 class={age < 85 ? 'active' : ''}>{name}</h1>
<button on:click={assign}>assign</button>
<img src="" alt={world} />
<input type="text" bind:value={name} />
  
<style>
h1 {
    color: red;
}
.active {
    color: blue;
}
</style>