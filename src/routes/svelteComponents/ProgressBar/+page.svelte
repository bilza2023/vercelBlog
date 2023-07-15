<script>
//@ts-nocheck
import {P,Ul,Li,HdgWithIcon,ProgressBar} from '../../../lib/cmp/index.js';
</script>


<br/>
<HdgWithIcon >ProgressBar</HdgWithIcon>

<P>A simple progress bar which counts numbers / questions.</P>


<Ul title ='Props'>
  <Li>export let total;</Li>
  <Li>export let current;</Li>
</Ul>

<HdgWithIcon icon= '🧱' >Example</HdgWithIcon>
<ProgressBar total=12 current=6 />