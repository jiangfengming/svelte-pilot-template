<script lang='ts' module>
  import type { LoadFunction } from 'svelte-pilot'

  import type { Context } from '../context/types'

  export const load: LoadFunction<{}, Context> = async (props, route, ctx) => {
    ctx.setStatus(500)
  }
</script>

<svelte:head>
  <title>500 Error</title>
</svelte:head>

<h1>500 Error</h1>
