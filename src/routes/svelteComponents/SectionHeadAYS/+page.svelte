<script>
//@ts-nocheck
import {P,Ul,Li,HdgWithIcon,SectionHeadAYS} from '../../../lib/cmp/index.js';
</script>


<br/>
<HdgWithIcon >SectionHeadAYS</HdgWithIcon>

<P>A Header that show or hide the contained div. It is just like SectionHead with a "AreYouSure" /del button</P>


<Ul title ='Props'>
  <Li>export let title;</Li>
  <Li>export let icon = "\u2699";</Li>
  <Li>export let deleteFn = ()=>console.log('Hello');</Li>
  <Li>export let visible = false;</Li>
</Ul>

<HdgWithIcon icon= '🧱' >Example</HdgWithIcon>

<SectionHeadAYS title='The Title of the Section' icon='🏦'>
<h1>The Section content</h1>
</SectionHeadAYS>