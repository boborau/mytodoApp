<script>
     export let text;
     export let checked;
     export let removeItem;
     export let toggleDone;
</script>

<li><input bind:checked={checked} on:change={toggleDone} type="checkbox"> 
     <span class:checked={checked}>{text}</span>
     <button type="button" on:click={removeItem}>BOOYAKA BOOYAKA 619</button>
</li>

<style>
     .checked {
          text-decoration: line-through;
     }
</style>