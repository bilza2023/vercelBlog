<script>
//@ts-nocheck
import Ul from '../../../lib/UiOl/Ul.svelte';
import Li from '../../../lib/UiOl/Li.svelte';
import HdgWidthIcon from '../../../lib/cmp/HdgWithIcon.svelte';
import Img from '../../../lib/cmp/Img.svelte';
import P from '../../../lib/cmp/P.svelte';

</script>


<br/>
<HdgWidthIcon >HdgWidthIcon</HdgWidthIcon>

<P>Normally use as page main heading. Also used to show sections on a page. This is my go to Component when I need a heading.</P>


<Ul title ='Props'>
  <Li>export let title = 'Title With Icon';</Li>
  <Li>export let icon = '📜';</Li>
  <Li>export let bgColor = 'bg-blue-800';</Li>
</Ul>


<Img url='/images/HdgWithIcon.png' />

