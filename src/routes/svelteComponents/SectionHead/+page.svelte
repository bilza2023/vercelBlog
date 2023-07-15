<script>
//@ts-nocheck
import {P,Ul,Li,HdgWithIcon,SectionHead} from '../../../lib/cmp/index.js';
</script>


<br/>
<HdgWithIcon >SectionHead</HdgWithIcon>

<P>A Header that show or hide the contained div.</P>


<Ul title ='Props'>
  <Li>export let title;</Li>
  <Li>export let icon = "\u2699";</Li>
  <Li>export let visible = false;</Li>
</Ul>

<HdgWithIcon icon= '🧱' >Example</HdgWithIcon>

<SectionHead title='The Title of the Section' icon='🏦'>
<h1>The Section content</h1>
</SectionHead>