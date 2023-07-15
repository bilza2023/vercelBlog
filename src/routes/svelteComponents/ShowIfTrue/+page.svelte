<script>
//@ts-nocheck
import {P,Ul,Li,HdgWithIcon,ShowIfTrue} from '../../../lib/cmp';
let ifTrue = false;
</script>


<br/>
<HdgWithIcon >ShowIfTrue</HdgWithIcon>

<P>Show or hide its slot based on "ifTrue" variable provided.</P>


<Ul title ='Props'>
    <Li>export let ifTrue;</Li>
    <Li>slot: Takes a slot</Li>
</Ul>

<HdgWithIcon icon= '🧱' >Example</HdgWithIcon>

<div class='flex justify-center w-full'>
<button class="p-1 m-1 bg-stone-400 rounded-md"
 on:click={()=>ifTrue = !ifTrue}>True/False</button>
</div>

<ShowIfTrue {ifTrue}>
<h1 class="bg-green-900">Will be shown only when ifTrue = true</h1>
</ShowIfTrue>