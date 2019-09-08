<style lang="scss">
  .hero {
    position: relative;
    height: 450px;
    background-image: url(../img/hero.jpg);
    display: flex;
    align-items: center;
    justify-content: center;
    &::after {
      content: "";
      background-color: rgba(0, 0, 0, 0.7);
      display: block;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0%;
      position: absolute;
    }
  }
  .hero-content {
    color: var(--white);
    z-index: 1;
    text-align: center;
    & i {
      font-size: 3rem;
      color: var(--primary);
    }
  }
</style>

<div class="hero">
  <div class="hero-content">
    <h1>Freelance Web Developer</h1>
    <p>
      <i class="fas fa-map-marker-alt" />
      Guadalajara, Jalisco
    </p>
    <a class="button" href="#">Contact Us Here</a>
  </div>
</div>
