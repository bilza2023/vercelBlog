<script>
//@ts-nocheck
import {P,Ul,Li,HdgWithIcon,Tf} from '../../../lib/cmp';
const state = { flag : true};
</script>


<br/>
<HdgWithIcon >Tf</HdgWithIcon>

<P>The Tf (True or False) component takes in an object and one of its boolean property. Once it is attached to that boolean prop we can manipulate that. It is used along with FormRow monstly.</P>


<Ul title ='Props'>
    <Li>export let bool_prop;//prop name as string</Li>
    <Li>export let obj;</Li>
</Ul>

<HdgWithIcon icon= '🧱' >Example</HdgWithIcon>
<div class='flex mx-10 justify-center'>
<Tf obj={state} bool_prop={'flag'} />
</div>