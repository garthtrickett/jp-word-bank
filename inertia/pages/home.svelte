<script lang="ts">
  import type { InferPageProps } from '@adonisjs/inertia/types';
  import HomeController  from '#controllers/home_controller'

  type Name = InferPageProps<HomeController, 'index'>
  let { name }: Name = $props();

</script>


<svelte:head>
  <title>Homepage</title>
</svelte:head>

<div class="container">
  <p>Hello {name}</p>

  <span>
    Learn more about AdonisJS and Inertia.js by visiting the 
    <a href="https://docs.adonisjs.com/guides/inertia">AdonisJS documentation</a>.
  </span>
</div>
