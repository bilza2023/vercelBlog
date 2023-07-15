<script>
//@ts-nocheck
import {P,Ul,Li,HdgWithIcon,FormRow} from '../../../lib/cmp/index.js';
</script>


<br/>
<HdgWithIcon >FormRow</HdgWithIcon>

  <P>This component is to create 2 columns in one row, first for title and second for content.</P>


<Ul title ='Props'>
  <Li>export let title = "Title";</Li>
</Ul>

<HdgWithIcon icon= '🧱' >Example</HdgWithIcon>

  <FormRow title='The Title' >
  <P>This is the content</P>
  </FormRow>