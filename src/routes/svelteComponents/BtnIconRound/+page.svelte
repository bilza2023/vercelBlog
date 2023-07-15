<script>
//@ts-nocheck
import {P,Ul,Li,HdgWithIcon,BtnIconRound,BtnIconOval,Comment} from '../../../lib/cmp/index.js';
</script>


<br/>
<HdgWithIcon >BtnIconRound</HdgWithIcon>

<P>A small round button with just an icon and click prop.</P>


<Ul title ='Props'>
  <Li>export let icon = '📜';</Li>
  <Li>export let bgColor = 'bg-gray-700';</Li>
  <Li>export let size = '2'; //1-to-4</Li>
  <Li>export let borderColor = 'border-white';</Li>
  <Li>export let borderWidth = 'border-1';</Li>
  <Li>export let clk = ()=>console.log('clicked');</Li>
</Ul>

<HdgWithIcon icon= '🧱' >Example</HdgWithIcon>

<div class='flex justify-center bg-gray-900 p-1 m-1 w-full'>
<BtnIconRound icon='📜' clk={()=>console.log('clicked Template')} />
<BtnIconRound icon='🧱' clk={()=>console.log('clicked Wall')} />
<BtnIconRound icon='📢' clk={()=>console.log('clicked Speaker')} />
<BtnIconRound icon='📐' clk={()=>console.log('clicked Scale')} />
<BtnIconRound icon='🎨' clk={()=>console.log('clicked Theme')} />
</div>

<br/>
<div class='flex justify-center'>
<BtnIconOval  icon='📢' clk={()=>console.log('clicked oval button')}/>
</div>
<Comment>The BtnIconOval is here for comparison</Comment>