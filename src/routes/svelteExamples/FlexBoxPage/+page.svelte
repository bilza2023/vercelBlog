<script>
  //@ts-nocheck
  import { P, HdgWithIcon, Card,Range,FlexBox } from '../../../lib/cmp/index.js';

  let numberOfCards = 2;

  const cardsData = [
    { title: 'The Title', url: 'https://google.com' },
    { title: 'The Title2', url: 'https://google.com' },
    { title: 'The Title3', url: 'https://google.com' },
    { title: 'The Title4', url: 'https://google.com' },
    { title: 'The Title5', url: 'https://google.com' },
    { title: 'The Title6', url: 'https://google.com' },
    { title: 'The Title7', url: 'https://google.com' },
    { title: 'The Title8', url: 'https://google.com' },
    { title: 'The Title9', url: 'https://google.com' },
    { title: 'The Title10', url: 'https://google.com' },
    { title: 'The Title11', url: 'https://google.com' },
    { title: 'The Title12', url: 'https://google.com' },
    { title: 'The Title13', url: 'https://google.com' },
    { title: 'The Title14', url: 'https://google.com' },
    { title: 'The Title15', url: 'https://google.com' }
  ];
</script>


<br/>
<HdgWithIcon>FlexBoxPage</HdgWithIcon>

<P>An example of how to display a large flexbox on a page with Card items in it.</P>

<HdgWithIcon icon='🧱'>Example</HdgWithIcon>
<!-- range -->
<div class='flex justify-center'>
<Range bind:value={numberOfCards} /> 
</div>

<FlexBox data ={cardsData}>
  <!-- <template slot="card" let:d> -->
  <Card
  
        title={"ddddd"}
        url={'hhhh'}
        icon="🧱"
        titleCharsCount={15}
  />
  <!-- </template> -->

</FlexBox>
<!-- <div class="flex justify-center gap-3 flex-wrap">
  {#each cardsData as cardData, index}
    <div class={`w-${numberOfCards}/12`}>
      <Card
        title={cardData.title}
        url={cardData.url}
        icon="🧱"
        titleCharsCount={15}
      />
    </div>
  {/each}
</div> -->
