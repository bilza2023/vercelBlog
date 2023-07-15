<script>
//@ts-nocheck
import {P,Ul,Li, HdgWithIcon , PageNav,PageNavBtn } from '../../../lib/cmp';
</script>


<br/>
<HdgWithIcon >NavBar</HdgWithIcon>

<P>This is main Navbar, there is another nav bar called "PageNav" which has larger buttons.</P>


<Ul title ='Props'>
  <Li>export let bgColor = 'bg-gray-700';</Li>
  <Li>PageNavBtn: Mostly used with this component.</Li>
</Ul>

<HdgWithIcon icon= '🧱' >Example</HdgWithIcon>

<PageNav>
<PageNavBtn  title='Wall' icon ='🧱' url='https://google.com'   />
<PageNavBtn  title='Broadcast' icon ='📢' url='https://google.com'   />
<PageNavBtn  title='Settings' icon ='📐' url='https://google.com'   />
<PageNavBtn  title='Theme' icon ='🎨' url='https://google.com'   />
</PageNav>