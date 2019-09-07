<script>
  import Service from "../components/Service.svelte";
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
    <Service />
  </div>
</main>
