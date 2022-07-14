<template>
  <div>
    <section class="text-center">
      <h1 id="landing-title">Empathetic Problem Solver</h1>
      <p>Innovative software and hardware solutions for those who need them.</p>
      <br /> <br /> 
      <div class="flex-center-responsive landing">
        <div class="flex-column">
          <p>
            My name is Brentyn and my portfolio website is under construction.
          </p>
          <NuxtLink to="/contact">
            <button class="btn-CTA"><span> Connect Now </span></button>
          </NuxtLink>
          <button class="btn-CTA"><span> View as Bunny </span></button>
        </div>
        <img
          src="../assets/high_flying.png"
          alt="Bigital's mascot and logo phil flying a biplane with his passenger & sidekick Socks. Some clouds"
        />
      </div>
    </section>

    <section class="bg-plate">
      <h2>What I Do :</h2>
      <p>
        Designing smart solutions for complex problems, from installing hardware to implementing software. Fundamentally, I enjoy solving people's problems.
      </p>
      <div class="flex-center-responsive">
        <StandardCard
          title="Software Dev"
          image="icons/desktop.svg"
          description="Can bring a website or app to life from design, programming, to solutions like hosting and DNS management."
        />
        <StandardCard
          title="Empathetic"
          image="icons/compassion.png"
          description="Listens to design needs and considerations deeply to create a solution that is elegantly functional."
        />
        <StandardCard
          title="Hardware Guru"
          image="icons/hardware.png"
          description="Automate systems or setup IT infrastructure: PCs, servers, switches, routers, microcomputers, gaming, etc."
        />
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
        projects.
        <br />
        <br />
        To see the code running this page (and other services), click here:
        <br>
        <a href="https://github.com/Brehtyn?tab=repositories"> Github Repos </a>
      </p>
    </section>

    <section class="text-center bg-plate">
      <p>Explore a small sample of projects I have worked on.</p>
      <div>
        <ExtendedCard
          title="Bigital"
          description="My company: a web design and development company that creates beautiful, functional websites and applications."
          image="screenshots/bigital.jfif"
          alt="Screenshot of Bigital's website."
          url="https://ibigital.com/"
        />
        <ExtendedCard
          id="flip-it"
          title="Sudsy Serenity"
          description="A relaxing and peaceful soap store utilizing Shopify, Photoshop, and CSS."
          image="screenshots/sudsyserenity.jfif"
          alt="Screenshot of Sudsy Serenity's website."
          url="https://sudsyserenity.com/"
        />
        <ExtendedCard
          title="Todo Simply"
          description="Todo list made with React, Node, and MongoDB. Special thanks to Daniel Ventura."
          image="screenshots/todosimply.jfif"
          alt="Screenshot of Todo Simply's App."
          url="https://todo-simply.com/"
          github="https://github.com/Dvent1123/task-manager-client"
          githubAPI="https://github.com/Dvent1123/task-manager-api"
          thanksPerson="Daniel Ventura"
          thanksURL="https://www.venturadaniel.com/"
        />
        <p>
          If you'd like to see more, check out my
          <NuxtLink to="/resume"> skills page </NuxtLink>
          or this 
          <NuxtLink to="/resume"> resume page. </NuxtLink>
        </p>
      </div>
    </section>

    <section class="text-center">
      <h3>Community above all else.</h3>
      <img
        src="../assets/table_relief.png"
        alt="Bigital's mascot and logo phil finishing giving aid to Brown on a table while a crowd gathers."
      />
      <p>
        Helping others is imperative, no matter where.
        <br />
        To give back, I help where I can. I'm happy to field any questions. I
        also offer upto 70% off any of my adjustable business services for
        nonprofits, charities, and other giving organizations.
      </p>
    </section>

    <section class="text-center bg-plate">
      <br />
      <h2 class="text-center">Still curious to learn more?</h2>
      <p>
        <br />
        I know I always am. 
        <br />
        If you would like to learn more about me or my work, please feel free to ask or visit my 
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
  font-size: 3rem;
  font-weight: bold;
  background: var(--color-changing);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.landing > img {
  width: 60%;
  height: auto;
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