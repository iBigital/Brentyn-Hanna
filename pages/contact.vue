<template>
  <div>
    <section class="text-center bg-plate">
      <h1>Contact Anytime</h1>
      <div class="flex-center-responsive">
        <ContactCard />
        <div class="contact-side-plate">
          <h3>Need help?</h3>
          <p>
            Pro tip: just ask! <br />From small to large, I am willing to hear
            out your troubles.
          </p>
          <p>
            Send a message with relevant details including project, timeline,
            and budget if relevant.
          </p>
        </div>
      </div>
    </section>

    <section class="text-center">
      <h2>Keep up with my socials!</h2>
      <div class="flex-center">
        <DisplayItem
          image="icons/logo_linkedin.png"
          alt="LinkedIn's Logo"
          url="https://www.linkedin.com/in/brehtyn/"
        />
        <DisplayItem
          image="icons/logo_github.png"
          alt="AGithub's Logo"
          url="https://github.com/Brehtyn"
        />
        <DisplayItem
          image="icons/logo_instagram.png"
          alt="Instagram's Logo"
          url="https://www.instagram.com/brehtyn/"
        />
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

.flex-center, .flex-center > a {
  margin:1rem;
}

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