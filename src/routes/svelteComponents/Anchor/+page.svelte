<script>
//@ts-nocheck
import {P,Ul,Li,HdgWithIcon,Anchor} from '../../../lib/cmp/index.js';
</script>


<br/>
<HdgWithIcon >Anchor</HdgWithIcon>

<P>A full width anchor which takes a slot. Will be improved.</P>


<Ul title ='Props'>
  <Li>export let href = '';</Li>
  <Li>slot: Takes a slot</Li>
</Ul>

<HdgWithIcon icon= '🧱' >Example</HdgWithIcon>
  <div class='flex justify-center w-full'>
      <Anchor href='https://google.com'>
        <h1>The Slot</h1>
      </Anchor>
  </div>