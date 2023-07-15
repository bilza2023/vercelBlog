<script>
import {PageWrapper,HdgWithIcon,Card} from '$lib/cmp';
const cardsData = [
    { title: 'Svelte Components', url: '/svelteComponents' , icon :"🧰" },
    { title: 'Svelte Examples', url: '/svelteExamples' ,icon :"🌟"},
  ];
</script>

<PageWrapper>
<br/>
<HdgWithIcon>Bilal's Blog</HdgWithIcon>
<br/>
<div class="flex justify-center gap-2 flex-wrap">
  {#each cardsData as cardData, index}
    <div class= 'w-3/12'>
      <Card
        title={cardData.title}
        url={cardData.url}
        icon={cardData.icon}
        titleCharsCount={15}
      />
    </div>
  {/each}
</div>


</PageWrapper>
