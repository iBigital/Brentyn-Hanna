<template>
  <div>
    <section class="text-center">  
      <h1>Contact Anytime</h1>
      <div class="flex-center-responsive">
        <ContactCard />
        <div class="contact-side-plate">
          <h3>Need help?</h3>
          <p>
            Pro tip: just ask! <br/>From small to large, I am willing to hear out your troubles.
          </p>
          <p>
            Send a message with relevant details including project, timeline, and
            budget to begin as soon as today!
          </p>
        </div>
      </div>
    </section>

    <section class="bg-plate text-center">
      <img
        src="../assets/drop_ship.png"
        alt="Bigital's mascot and logo phil parachuting whie socks is flying a biplane. Some clouds and crates."
      />
    </section>
  </div>
</template>

<style scoped>

@media screen and (min-width: 769px) {
  .contact-side-plate {
    max-width: 40%;
  }
}
.contact-side-plate,
.contact-side-plate > * {
  padding: 1rem;
  text-align: left;
}
.contact-side-plate > p {
  color: var(--color-neutral-dark);
  font-size: 1rem;
}
</style>