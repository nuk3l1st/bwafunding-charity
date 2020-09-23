<script>
    export let charities;
</script>
<div>
    <h2>Daftar Charity</h2>
    {#if charities !== undefined}
        <pre>{charities}</pre>
        <ul>
            <li>Charity 1</li>
            <li>Charity 2</li>
            <li>Charity 3</li>
        </ul>
    {:else}
        <h5>Data Belum Tersedia</h5>
    {/if}    
</div>