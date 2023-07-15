<script>
//@ts-nocheck
import {P,Ul,Li,HdgWithIcon,BtnWIcon , BtnWIconSm,Comment} from '../../../lib/cmp/index.js';
</script>


<br/>
<HdgWithIcon >BtnWIcon</HdgWithIcon>

<P>A button which once clicked gives you some seconds to re-consider.</P>


<Ul title ='Props'>
  <Li>export let icon = '📜';</Li>
  <Li>export let clk = ()=>console.log('clicked');</Li>
  <Li>export let bgColor = 'bg-blue-800';</Li>
  <Li>export let title = 'The Title';</Li>
  <Li>Does not use slot.</Li>
</Ul>

<HdgWithIcon icon= '🧱' >Example</HdgWithIcon>

<BtnWIcon icon= '📜' title='The Content' />
<br/>

<BtnWIconSm icon= '📜' title='The Content' />

<Comment>The BtnWIconSm is being displayed for comparison.</Comment>