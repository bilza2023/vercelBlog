<script>
import PageNav from '$lib/cmp/PageNav.svelte';
import ToolBarBtn from '$lib/cmp/ToolBarBtn.svelte';
import { browser } from '$app/environment';
import { goto } from '$app/navigation';

</script>

<PageNav>
<ToolBarBtn  title='Home' icon='🏦'  
clk = {()=>{ if (browser){goto('/')}}}
/>
<ToolBarBtn  title='Comps' icon='🏡'  
clk = {()=>{ if (browser){goto('/svelteComponents/')}}}
/>
</PageNav>

<!-- 🏦 -->