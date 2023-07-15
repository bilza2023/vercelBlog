<script>
  //@ts-nocheck
  import { P, HdgWithIcon, Card,Range } from '../../../lib/cmp/index.js';

  let numberOfCards ={ no: 2 };

  const cardsData = [
    { title: 'Titlex', url: 'https://google.com' },
    { title: 'The Title2w', url: 'https://google.com' },
    { title: 'The Title32', url: 'https://google.com' },
    { title: 'The Title48', url: 'https://google.com' },
    { title: 'The Title52', url: 'https://google.com' },
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
<Range bind:value={numberOfCards.no} /> 
</div>

<div class="flex justify-center gap-2 flex-wrap">
  {#each cardsData as cardData, index}
    <div class={`w-${numberOfCards.no}/12`}>
      <Card
        title={cardData.title}
        url={cardData.url}
        icon="🧱"
        titleCharsCount={15}
      />
    </div>
  {/each}
</div>
