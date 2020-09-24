<script>
    export let charities;
</script>
<div>
    <h2>Daftar Charity</h2>
    {#if charities !== undefined}
        <ul>
            {#each charities as char }
                <li>{char}</li>
            {/each}
        </ul>
    {:else}
        <h5>Data Belum Tersedia</h5>
    {/if}    
</div>