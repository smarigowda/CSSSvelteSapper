<style>
  .main-navigation {
    max-width: 1200px;
    margin: 0 auto;
    padding: 1rem 0;

    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .main-navigation a {
    color: var(--dark);
    text-decoration: none;
    font-size: 1.4rem;
    margin-bottom: 1.4rem;
  }
  @media (min-width: 768px) {
    .main-navigation {
      flex-direction: row;
      justify-content: space-between;
    }
  }
  @media (min-width: 768px) {
    .main-navigation a {
      margin-bottom: 0;
    }
  }
</style>

<nav class="main-navigation">
  <a href="#">Home</a>
  <a href="#">About Us</a>
  <a href="#">Clients & Work</a>
  <a href="#">Contact Us</a>
</nav>
