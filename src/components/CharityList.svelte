<script>
    export let charities;
</script>
<div>
    <h2>Daftar Charity</h2>
    {#if charities !== undefined}
        <ul>
            {#each charities as charities }
                <li>{charities.title} - {charities.category}</li>
            {/each}
        </ul>
    {:else}
        <h5>Data Belum Tersedia</h5>
    {/if}    
</div>