<script>
//@ts-nocheck
import {P,Ul,Li,HdgWithIcon,Card} from '../../../lib/cmp/index.js';
</script>


<br/>
<HdgWithIcon >Card</HdgWithIcon>

<P>A Card which will take full width unless restricted / placed in flex box. It is to be used with flex-box system.</P>


<Ul title ='Props'>
  <Li>export let icon="📜";</Li>
  <Li>export let title='The Title';</Li>
  <Li>export let url;</Li>
  <Li>export let titleCharsCount = 20;</Li>
</Ul>

<HdgWithIcon icon= '🧱' >Example</HdgWithIcon>
  <br/>
  <div class='flex justify-center w-full'>
    <div class='w-3/12'>
        <Card  url='https://google.com'/>
    </div>      
  </div>