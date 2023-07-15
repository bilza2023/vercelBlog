<script>
import SvltCompsNav from './SvltCompsNav.svelte';
import Footer from '$lib/cmp/Footer.svelte';
import PageWrapper from '$lib/cmp/PageWrapper.svelte';

</script>


<PageWrapper>
<SvltCompsNav />

<slot></slot>


<Footer />
</PageWrapper>
