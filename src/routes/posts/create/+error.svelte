<script>
	import { page } from '$app/stores';
</script>

<h5>Tipo de error: {$page.Error?.message}</h5>
<pre>
    {JSON.stringify($page, null, 2)}
</pre>
