<script>
  export let service;
</script>

<style lang="scss">
  .service {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  @media (min-width: 768px) {
    .service {
      flex: 0 0 calc(33.3% - 1rem);
    }
  }
  h3 {
    text-align: center;
    color: var(--secondary);
    font-weight: 400;
    font-size: 1.6rem;
  }
  p {
    line-height: 2;
  }
  .icons {
    height: 100px;
    width: 100px;
    display: flex;
    background-color: var(--primary);
    border-radius: 50%;
    align-items: center;
    justify-content: space-evenly;
    & i {
      font-size: 2rem;
    }
  }
</style>

<div class="service">
  <h3>{service.heading}</h3>
  <div class="icons">
    {#each service.icons as icon}
      <i class={icon.classes} />
    {/each}
  </div>
  <p>{service.description}</p>
</div>
