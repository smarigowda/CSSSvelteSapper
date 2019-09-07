<style>
  .hero {
    height: 450px;
    background-image: url(../img/hero.jpg);
    position: relative;

    display: flex;
    align-items: center;
    justify-content: center;
  }
  .hero::after {
    content: "";
    background-color: rgba(0, 0, 0, 0.7);
    display: block;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    position: absolute;
  }
  .hero-content {
    color: var(--white);
    position: relative;
    z-index: 1;
    text-align: center;
  }
  .hero-content i {
    font-size: 3rem;
    color: var(--primary);
  }
  .button {
    background-color: var(--secondary);
    padding: 0.5rem 3rem;
    border-radius: 5px;
    display: inline-block;
    margin-top: 0.5rem;
    font-weight: 700;
    text-decoration: none;
    text-transform: uppercase;
    font-size: 1.2rem;
    border: none;
    color: var(--white);
    transition: background-color 0.3s ease;
    cursor: pointer;
  }
  .button:hover {
    background-color: rgb(1, 123, 136);
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
