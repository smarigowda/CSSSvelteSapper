<style lang="scss">
  h2 {
    text-align: center;
  }
  @media (min-width: 768px) {
    form {
      max-width: 800px;
      margin: 0 auto;
    }
    .form-container {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
    }
    .field {
      flex: 0 0 calc(50% - 1rem);
    }
  }
  form {
    background-color: var(--gray);
    padding: 2rem;
    border-radius: 1rem;
  }
  .submit-form {
    display: flex;
    justify-content: flex-end;
  }
  .w-100 {
    flex: 0 0 100%;
  }
  .field {
    display: flex;
    margin-bottom: 1rem;
    align-items: center;
    label {
      flex: 0 0 90px;
      color: var(--white);
    }
    input[type="text"],
    input[type="tel"],
    input[type="mail"],
    textarea {
      flex: 1;
      height: 2.4rem;
    }
  }
</style>

<section id="contact" class="contact">
  <h2>Contact Me</h2>
  <form action="#">
    <div class="form-container">
      <div class="field">
        <label>Name:</label>
        <input type="text" placeholder="Name" />
      </div>
      <div class="field">
        <label>Phone Number:</label>
        <input type="tel" placeholder="Phone Number" />
      </div>
      <div class="field w-100">
        <label>Email:</label>
        <input type="mail" placeholder="Email" />
      </div>
      <div class="field w-100">
        <label>Message:</label>
        <textarea cols="30" rows="3" />
      </div>
    </div>
    <div class="submit-form">
      <input type="submit" class="button" value="Send" />
    </div>
  </form>
</section>
