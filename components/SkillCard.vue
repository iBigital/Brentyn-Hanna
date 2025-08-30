<template>
  <section class="flex-center-responsive">
    <div>
      <a :href="url">
        <img :src="image" :alt="alt"  />
      </a>
    </div>
    <div id="text">
      <h3>{{ title }}</h3>
      <p>{{ description }}</p>
    </div>
  </section>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      default: "Extended Card",
    },
    description: {
      type: String,
      default: "This is a extended card",
    },
    image: {
      type: String,
      default: "icons/cog.svg",
    },
    alt: {
      type: String,
      default: "Loading Cog",
    },
  },
};
</script>

<style scoped>
section {
  width: 100%;
  max-width: 1000px;
  height: 100%;
  background-color: var(--color-neutral);
  border-radius: 10px;
  box-shadow: 0px 0px 10px 0px rgba(0, 0, 0, 0.35);
  display: flex;
  flex-direction: row;
  color: #000;
  background-color: var(--color-neutral);
  margin: 2rem auto;
}
section:hover, section:active {
  box-shadow: 0px 0px 10px 0px rgba(0, 0, 0, 0.5);
  background-color: var(--color-special);
  animation: fadeIn 0.5s ease-in-out;
  color: var(--color-neutral);
}
section:hover > div > p, section:active > div > p {
  color: var(--color-neutral) !important;
}

#flip-it {
  flex-direction: row-reverse;
}

@media screen and (min-width: 800px) {
  section > div > h3 {
    align-items: flex-start !important;
    align-self: flex-start !important;
  }
  #text {
    margin-left: 2rem;
  }
}

@media screen and (max-width: 800px) {
  section {
    flex-direction: column;
  }
  #flip-it {
    flex-direction: column;
  }
  p {
    text-align: center !important;
  }
}

div {
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 0;
  margin: 0;
}

img {
  width: 140px;
  height: auto;
  padding: 0;
  margin: 0;
}
p {
  text-align: left;
  font-size: 1.2rem;
  margin: 1.5rem 0;
  color: var(--color-neutral-dark);
}
</style>