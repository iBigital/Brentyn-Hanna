<template>
  <section class="flex-center-responsive">
    <div id="screenshot_image">
      <a :href="url">
        <img :src="image" :alt="alt" />
      </a>
    </div>
    <div id="info">
      <h3>{{ title }}</h3>
      <p>{{ description }}</p>
      <div class="flex-center-responsive">
        <a v-if="url" :href="url" class="btn"> Website </a>
        <a v-if="github" :href="github" class="btn"> Github </a>
        <a v-if="githubAPI" :href="githubAPI" class="btn"> API Github </a>
        <a v-if="thanksURL" :href="thanksURL" class="btn">
          {{ thanksPerson }}
        </a>
      </div>
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
    url: {
      type: String,
      default: false,
      required: false,
    },
    github: {
      type: String,
      default: false,
      required: false,
    },
    githubAPI: {
      type: String,
      default: false,
      required: false,
    },
    thanksPerson: {
      type: String,
      default: false,
      required: false,
    },
    thanksURL: {
      type: String,
      default: false,
      required: false,
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
  box-shadow: 0px 0px 10px 0px rgba(0, 0, 0, 0.2);
  display: flex;
  flex-direction: row;
  color: #000000;
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
section:hover > div > div > a, section:active > div > div > a {
  background-color: var(--color-neutral);
}

#flip-it {
  flex-direction: row-reverse;
}

@media screen and (min-width: 800px) {
  section > div > h3 {
    align-items: flex-start !important;
    align-self: flex-start !important;
  }
  #info {
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
  width: 100%;
  max-width: 350px;
  height: auto;
  max-height: 350px !important;
  padding: 0;
  margin: 0;
}
#screenshot_image {
  object-fit: cover;
  flex-grow: 1;
  padding: 0;
  margin: 0 1rem;
}
p {
  text-align: left;
  font-size: 1.2rem;
  margin: 1.5rem 0;
  color: var(--color-neutral-dark);
}
.btn {
  margin: 0.5rem 4rem;
  padding: 0.5rem 1rem;
  border-radius: 5px;
  background-color: var(--color-primary);
  color: var(--color-special);
  width: 50%;
  min-width: 200px;
  color: #000000;
  text-decoration: none;
  text-align: center;
}
.btn:hover, .btn:active {
  background-color: var(--color-neutral-dark);
  color: var(--color-neutral);
}
</style>