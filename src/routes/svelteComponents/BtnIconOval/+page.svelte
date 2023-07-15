<script>
//@ts-nocheck
import {P,Ul,Li,HdgWithIcon,BtnIconOval,Comment} from '../../../lib/cmp/index.js';
</script>


<br/>
<HdgWithIcon >BtnIconOval</HdgWithIcon>

<P>A small round button with just an icon and click prop.</P>


<Ul title ='Props'>
  <Li>export let icon = '⚙️';</Li>
  <Li>export let bgColor = 'bg-gray-700';</Li>
  <Li>export let clk = ()=>console.log('clicked');</Li>
  <Li>export let textSize = 'text-2xl';</Li>
</Ul>

<HdgWithIcon icon= '🧱' >Example</HdgWithIcon>

<div class='flex justify-center bg-gray-900 p-1 m-1 w-full'>
<BtnIconOval icon='📜' clk={()=>console.log('clicked Template')} />
<BtnIconOval icon='🧱' clk={()=>console.log('clicked Wall')} />
<BtnIconOval icon='📢' clk={()=>console.log('clicked Speaker')} />
<BtnIconOval icon='📐' clk={()=>console.log('clicked Scale')} />
<BtnIconOval icon='🎨' clk={()=>console.log('clicked Theme')} />
</div>

<Comment>The BtnIconRound is another such component.</Comment>