<script>
import SvltCompsNav from '../../lib/blogCmp/SvltCompsNav.svelte';
import Footer from '$lib/cmp/Footer.svelte';
import PageWrapper from '$lib/cmp/PageWrapper.svelte';

</script>


<PageWrapper>
<SvltCompsNav />

<slot></slot>


<Footer />
</PageWrapper>
