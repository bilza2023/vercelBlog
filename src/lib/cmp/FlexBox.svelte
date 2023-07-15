<script>
  //@ts-nocheck
  export let gap = 2;
  export let data = {};
  export let cardsWidth = 3;
</script>

<div class={`flex justify-center gap-${gap} flex-wrap`}>
  {#each data as d, index}
    <div class={`w-${cardsWidth}/12`}>
      <slot  name="card" d={d}  />
    </div>
  {/each}
</div>
