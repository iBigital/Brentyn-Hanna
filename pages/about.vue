<template>
  <div class="text-center">
    <h1 id="landing-title">So you wanna know me?</h1>
    <p id="landing-p">
      My name is Brentyn Hanna and I'm kinda a freaky lil techno wizard guy.
    </p>
    <img
      src="/public/assets/wizard-cat-cat.gif"
      alt="Car Wizard Gif"
      id="wizard"
    />
            <img
      src="/public/assets/hypno.gif"
      alt="Hypnotoad Gif"
      id="wizard"
    />
        <img
      src="/public/assets/wizard-elmo-elmo-fire.gif"
      alt="Elmo Wizard Gif"
      id="wizard"
    />
    <section>
      <p>
        I graduated in the fall of 2016 from high school with a dual enrollment
        Liberal Arts associate's degree from Mohave Community College.
      </p>
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
      <p>
        <br />
        From 2016-2018, I pursued a bachelor degree from Arizona State
        University with a major in Aerospace Engineering and a minor in
        Astrophysics. I achieved 104 credit hours towards my degree and plan on
        graduating when it is financially feasible.
      </p>
    </section>

    <section class="bg-plate">
      <div class="flex-center-responsive">
        <p>
          I keep my head grounded learning to write sensibly clean code and
          maintaining efficient hardware with minimal as possible environmental
          impact. To practice that craft, I started Bigital in 2020, a software
          company developing initially just frontend websites but these days
          I'll work on any stack!
        </p>
        <a href="https://www.ibigital.com/">
          <img src="/public/assets/logo.png" alt="Bigital's Logo" />
        </a>
      </div>
    </section>

    <section>
      <p>
        In 2022, I accepted a position working for the Federal Government on the
        Jtech-II contract in Nevada. I was sponsored for a Top Secret clearance
        and earned a CompTIA Security+ Certification but the real fun i.m.o. was
        learning and working on live radar threat systems.
      </p>

      <div class="flex-center">
        <DisplayItem
          image="icons/topsecret.png"
          alt="TopSecret.png"
          url="https://www.state.gov/"
        />
        <DisplayItem
          image="icons/SecurityPlus Logo Certified CE.png"
          alt="SecurityPlus Logo Certified CE.png"
          url="https://www.comptia.org/en-us/certifications/security/"
        />
        <DisplayItem
          image="icons/radar.png"
          alt="Mohave Community College's Logo"
        />
      </div>
    </section>

    <section class="bg-plate">
      <div class="flex-center-responsive">
        <a href="https://www.nasa.gov/">
          <img src="/public/icons/logo_nasa.png" alt="NASA's Logo" />
        </a>
        <p>
          In the future, I intend to work on crewed missions with dreams and an
          ambition to personally participate in space exploration. Regardless,
          the dream is to work at or closely with NASA or a similar non-profit
          space or science organization.
        </p>
      </div>
    </section>

    <section class="text-center">
      <p>Genuinely, thank you for visiting my site!</p>

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
#landing-p {
  margin: 20px;
}
#wizard {
  max-height: 150px;
  border-radius: 12px;
  margin: 20px;
}

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