<script>
  import Service from "../components/Service.svelte";
  export let services;
</script>

<style>
  h2 {
    text-align: center;
  }
  @media (min-width: 768px) {
    .services-container {
      display: flex;
      justify-content: space-between;
    }
  }
</style>

<main class="services">
  <h2>My Services</h2>
  <div class="services-container">
    {#each services as service}
      <Service {service} />
    {/each}
  </div>
</main>
