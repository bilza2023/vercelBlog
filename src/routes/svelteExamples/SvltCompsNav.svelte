<script>
import NavSec from '$lib/cmp/NavSec.svelte';
import ToolBarBtn from '$lib/cmp/ToolBarBtn.svelte';
import { browser } from '$app/environment';
import { goto } from '$app/navigation';

</script>

<NavSec>
<ToolBarBtn  title='Home' icon='🏦'  
clk = {()=>{ if (browser){goto('/')}}}
/>
<ToolBarBtn  title='Examples' icon='🏡'  
clk = {()=>{ if (browser){goto('/svelteExamples/')}}}
/>
</NavSec>

<!-- 🏦 -->