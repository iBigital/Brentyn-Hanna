<template>
  <div class="text-center">
    <h1 id="landing-title">About</h1>
    <p>
      My name is Brentyn Hanna and I engineer creative tools and software
      solutions!
    </p>

    <section>
      <div class="flex-center">
        <DisplayItem
          image="icons/mcc_logo.png"
          alt="Mohave Community College's Logo"
          url="https://www.mohave.edu/"
          id="school-logos"
        />
        <DisplayItem
          image="icons/asu_logo.png"
          alt="Arizona State University's Logo"
          url="https://www.asu.edu/"
          id="school-logos"
        />
      </div>
      <br />
      <p>
        I graduated in the fall of 2016 from highschool with a dual enrollment
        Liberal Arts associates degree from Mohave Community College. 
        <br> <br>
        From 2016-2018, I persued a bachelors from Arizona State University with a major in Aerospace Engineering
        and a minor in Astrophysics. I did not complete my bachelors (16 credit hours short) but 
        I plan on continuing perusing my degree when it is financially feasible. 
      </p>
    </section>

    <section class="bg-plate">
      <div class="flex-center-responsive">
        <a href="https://www.nasa.gov/">
          <img src="icons/logo_nasa.png" alt="NASA's Logo" />
        </a>
        <p>
          In the future, I intend to become an aerospace engineer and work on
          crewed missions with dreams and an ambition to personally participate.
          I would like to work at or closely with NASA or a similar non-profit
          space or science organization.
        </p>
      </div>

      <br />

      <p>
        I keep my head grounded learning to write sensibly clean code and
        maintaining efficient hardware with minimal as possible environmental
        impact. As of late my volunteering efforts have been minimal, but
        previously I'd give time helping my community through programs such as
        Key Club and animal shelter kennels.
      </p>
    </section>

    <section class="text-center">
      <p>Genuinely, thank you for visting my site!</p>

      <p>Novel, alien, or mysterious problems? I would love to help!</p>
      <br />
      <img
        src="../assets/strange_meeting.png"
        alt="Phil, Bigital's Logo, having wide eyes at meeting strange glowing rabbits in a blue alien place. Socks flying rocket. 'Your Next Fullstack Expert' floats above."
      />
    </section>
  </div>
</template>

<style scoped>
.flex-center-responsive {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.flex-center-responsive > p {
  flex-shrink: 100;
}
.flex-center-responsive > a > img {
  width: 100%;
  max-width: 200px;
}

@media screen and (min-width: 768px) {
  .flex-center-responsive {
    text-align: left;
  }
}
</style>