<svelte:head>
  <title>Single Price Grid Component</title>
</svelte:head>

<script>
  import Button from './Button.svelte';
</script>

<main class="panels">
  <section class="panel panel--light panel--wide">
    <h2 class="panel__title">Join our community</h2>
  
    <h3 class="panel__subtitle">30-day, hassle-free money back guarantee</h3>
  
    <p class="panel__text">
      Gain access to our full library of tutorials along with expert code reviews.
      Perfect for any developers who are serious about honing their skills.
    </p>
  </section>

  <section class="panel panel--dark">
    <h2 class="panel__title">Monthly Subscription</h2>
    
    <div class="flex-container">
      <p class="panel__price">$29</p>
      <p class="panel__label">per month</p>
    </div>
    
    <p class="panel__text">Full access for less than $1 a day</p>
    
    <Button>
      <h2 slot="content">Sign Up</h2>
    </Button>
  </section>
  
  <section class="panel">
    <h2 class="panel__title">Why Us</h2>
    <ul class="panel__ul">
      <a href="."><li class="panel__item">Tutorials by industry experts</li></a>
      <a href="."><li class="panel__item">Peer &amp; expert code review</li></a>
      <a href="."><li class="panel__item">Coding exercises</li></a>
      <a href="."><li class="panel__item">Access to our GitHub repos</li></a>
      <a href="."><li class="panel__item">Community forum</li></a>
      <a href="."><li class="panel__item">Flashcard decks</li></a>
      <a href="."><li class="panel__item">New videos every week</li></a>
    </ul>
  </section>

</main>
