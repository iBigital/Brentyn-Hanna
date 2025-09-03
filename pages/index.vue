<template>
  <div>
    <section class="text-center">
      <h1 id="landing-title">Empathetic Problem Solver</h1>
      <p>Innovative solutions for those who need them.</p>
      <br />
      <br />
      <div class="flex-center-responsive landing">
        <div class="flex-column">
          <p>
            My name is Brentyn and I love to get into the technical details!
          </p>
          <NuxtLink to="/contact">
            <button class="btn-CTA"><span> Get In Touch </span></button>
          </NuxtLink>
        </div>
        <img
          src="../assets/flying.gif"
          alt="Bigital's mascot and logo phil flying a biplane with his passenger & sidekick Socks. Some clouds"
        />
      </div>
    </section>

    <section class="bg-plate">
      <h2>What I Do :</h2>
      <p>
        Deploys smart solutions from installing
        specialized hardware to implementing custom software. Fundamentally, I
        enjoy solving technical problems and helping people.
      </p>
      <div class="flex-center-responsive">
        <StandardCard
          title="Software Engineer"
          image="icons/desktop.svg"
          alt="A mac computer"
          description="Can bring applications to life from design, programming, to providing solutions like hosting and network management."
        />
        <StandardCard
          title="People Person"
          image="icons/compassion.png"
          alt="A pair of hands holding each other that forms a heart"
          description="Listens to needs and considerations deeply to create an effective solution that is fit as functional."
        />
        <StandardCard
          title="Hardware Guru"
          image="icons/hardware.png"
          alt="A microcontroller"
          description="Sets up IT infrastructure or racks of equipment: PCs, servers, switches, antennas, scientific equipment, gaming, etc."
        />
      </div>
    </section>

    <section class="text-center">
      <h3>Community above all else.</h3>
      <img
        src="../assets/table_relief.png"
        alt="Bigital's mascot and logo phil finishing giving aid to Brown on a table while a crowd gathers."
        id="table-relief"
      />
      <p>
        Helping others is imperative, no matter where.
        <br />
        To give back, I give time and discounts to charitable organizations. Ask me about more! 
      </p>
    </section>

    <section class="text-center">
      <h2> My Work Examples </h2>
      <p>Explore a small sample of projects I have worked on.</p>
      <div>
        <ExtendedCard
          title="Bigital"
          description="My company: a web design and development company that creates beautiful, functional websites and applications."
          image="screenshots/bigital.png"
          alt="Screenshot of Bigital's website."
          url="https://ibigital.com/"
        />
        <ExtendedCard
          id="flip-it"
          title="Quantum ERP Solutions"
          description="Partners with Software Companies to provide implementation, customization, and automation built Wordpress and CSS."
          image="screenshots/quantumerp.png"
          alt="Screenshot of Quantum ERP Solutions's website."
          url="https://quantumerpsolutions.com/"
        />
        <ExtendedCard
          title="Todo Simply"
          description="Todo list made with React, Node, and MongoDB. Special thanks to Daniel Ventura."
          image="screenshots/todosimply.jfif"
          alt="Screenshot of Todo Simply's App."
          github="https://github.com/Dvent1123/task-manager-client"
          githubAPI="https://github.com/Dvent1123/task-manager-api"
          thanksPerson="Daniel Ventura"
          thanksURL="https://www.venturadaniel.com/"
        />
        <p>
          If you'd like to see more, check out my
          <NuxtLink to="/skills"> skills page </NuxtLink>
          or my
          <a href="/assets/01resume_BrentynHanna.pdf" target="_blank"> resume pdf</a>.
        </p>
      </div>
    </section>

    <section class="text-center">
      <h3>Open source all the way.</h3>
      <img
        src="../assets/launch_prep.png"
        alt="Bigital's mascot and logo phil utilizing Brown's expertise to launch a rocket."
      />
      <p>
        I strongly believe in the power of collaboration and many things I do
        wouldn't be possible without massive contribution to open source
        projects and knowledge.
        <br />
        <br />
        To see the code running this page (and other services), click here:
        <br />
        <a href="https://github.com/Brehtyn?tab=repositories"> Github Repos </a>
      </p>
    </section>

    <section class="text-center bg-plate">
      <br />
      <h2 class="text-center">Still curious to learn more?</h2>
      <p>I know I always am.</p>
      <p>
        If you would like to learn more about me or my work, please feel free to
        ask or visit my
        <NuxtLink to="/about">about page.</NuxtLink>
        <br />
      </p>
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
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.bg-plate > p {
  padding: 1rem;
}
.bg-plate > h1,
h2,
h3,
h4,
h5,
h6 {
  padding: 1rem;
  padding-bottom: 0;
}

#landing-title {
  font-size: clamp(2.5rem, 5vw, 3.5rem);
  font-weight: bold;
  background: var(--color-changing);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
#table-relief {
  width:100%;
  max-width: 800px;
}

.landing > img {
  width: 60%;
  height: auto;
  object-fit: contain;
}
.landing > .flex-column {
  padding: 1rem;
  align-self: center;
  justify-content: center;
  margin-right: 2rem;
}
.landing > .flex-column > p {
  padding: 1rem;
  font-size: 1.2rem;
  text-align: left;
}
.landing > .flex-column > a > button {
  margin-top: 2rem;
}

@media screen and (max-width: 768px) {
  .landing {
    flex-direction: column-reverse;
  }
  .landing > .flex-column > p {
     text-align: center;
     margin-left: 2rem;
}
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