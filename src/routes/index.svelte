<script>
  import Navigation from "../components/Navigation.svelte";
  import Hero from "../components/Hero.svelte";
  import Services from "../containers/Services.svelte";
  import Contact from "../components/Contact.svelte";
  import services from "./_services.js";
</script>

<style>
  .container {
    margin: 2rem auto 3rem auto;
    max-width: 1200px;
    padding: 2rem;
    background-color: var(--white);
    -webkit-box-shadow: 0px 4px 12px -1px rgba(0, 0, 0, 0.45);
    -moz-box-shadow: 0px 4px 12px -1px rgba(0, 0, 0, 0.45);
    box-shadow: 0px 4px 12px -1px rgba(0, 0, 0, 0.45);
    border-radius: 1rem;
  }
</style>

<svelte:head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta http-equiv="X-UA-Compatible" content="ie=edge" />
  <title>Flexbox - Freelancer Website</title>
  <link
    rel="stylesheet"
    href="https://necolas.github.io/normalize.css/8.0.1/normalize.css" />
  <link
    href="https://fonts.googleapis.com/css?family=Krub:400,700"
    rel="stylesheet" />
  <link
    rel="stylesheet"
    href="https://use.fontawesome.com/releases/v5.5.0/css/all.css"
    integrity="sha384-B4dIYHKNBt8Bc12p+WXckhzcICo0wtJAoU8YZTY5qE0Id1GSseTk6S+L3BlXeVIU"
    crossorigin="anonymous" />
  <link rel="stylesheet" href="css/style.css" />
</svelte:head>

<Navigation />
<Hero />
<div class="container">
  <Services {services} />
  <Contact />
</div>
