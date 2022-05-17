<sevlte:head>
    <title>Home</title>
</sevlte:head>

<script lang="ts">
    let count = 0;

    function increment() {
        count++;
    }
</script>

<p>{count}</p>
<button on:click={increment}>Inc</button>
