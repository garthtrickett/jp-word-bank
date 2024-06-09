<script lang="ts">
export let name: string 
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
