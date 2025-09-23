<script>
  import { injectAnalytics } from "@vercel/analytics/sveltekit";

  injectAnalytics();

  let { children } = $props();
</script>

{@render children()}


<style>
</style>
