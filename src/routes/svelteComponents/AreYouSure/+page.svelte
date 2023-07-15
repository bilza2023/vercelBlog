<script>
//@ts-nocheck
import {P,Ul,Li,HdgWithIcon,Img,AreYouSure} from '../../../lib/cmp/index.js';
</script>


<br/>
<HdgWithIcon >AreYouSure</HdgWithIcon>

<P>A button which once clicked gives you some seconds to re-consider.</P>


<Ul title ='Props'>
  <Li>export let deleteFn;</Li>
  <Li>export let index;</Li>
  <Li>export let triggerTime = 2000;</Li>
</Ul>

<HdgWithIcon icon= '🧱' >Example</HdgWithIcon>
<AreYouSure />