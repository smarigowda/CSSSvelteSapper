<style>
  .service {
    display: flex;
    flex-direction: column;
    align-items: center;
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
  }
  .icons i {
    font-size: 2rem;
  }
  @media (min-width: 768px) {
    .service {
      flex: 0 0 calc(33.3% - 1rem);
    }
  }
</style>

<div class="service">
  <h3>Web Design</h3>
  <div class="icons">
    <i class="fas fa-pen-nib" />
  </div>
  <p>
    Blanditiis omnis dolorum nihil, dolor dolore corporis, ducimus vero officia
    beatae reiciendis velit quos quis deserunt placeat laboriosam necessitatibus
    saepe iure eaque?
  </p>
</div>
<div class="service">
  <h3>App Development</h3>
  <div class="icons">
    <i class="fab fa-android" />
    <i class="fab fa-apple" />
  </div>
  <p>
    Blanditiis omnis dolorum nihil, dolor dolore corporis, ducimus vero officia
    beatae reiciendis velit quos quis deserunt placeat laboriosam necessitatibus
    saepe iure eaque?
  </p>
</div>
<div class="service">
  <h3>Social Media</h3>
  <div class="icons">
    <i class="fab fa-twitter" />
    <i class="fab fa-facebook" />
  </div>
  <p>
    Blanditiis omnis dolorum nihil, dolor dolore corporis, ducimus vero officia
    beatae reiciendis velit quos quis deserunt placeat laboriosam necessitatibus
    saepe iure eaque?
  </p>
</div>
