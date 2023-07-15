<script>
//@ts-nocheck
import {P,Ul,Li,HdgWithIcon,NavBar,NavBtn} from '../../../lib/cmp/index.js';
</script>


<br/>
<HdgWithIcon >NavBar</HdgWithIcon>

<P>This is main Navbar, there is another nav bar called "PageNav" which has larger buttons.</P>


<Ul title ='Props'>
  <Li>export let bgColor = 'bg-gray-700';</Li>
  <Li>NavBtn: Mostly used with this component.</Li>
</Ul>

<HdgWithIcon icon= '🧱' >Example</HdgWithIcon>

<NavBar>
<NavBtn  title='Wall' icon ='🧱' url='https://google.com'   />
<NavBtn  title='Broadcast' icon ='📢' url='https://google.com'   />
<NavBtn  title='App Settings' icon ='📐' url='https://google.com'   />
<NavBtn  title='Theme' icon ='🎨' url='https://google.com'   />
</NavBar>