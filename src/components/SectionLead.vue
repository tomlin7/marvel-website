<script setup></script>

<template>
  <div>
    <h1>Marvel</h1>
    <p>Welcome to the Universe</p>
  </div>
  <p>
    The Marvel universe is a vast and wondrous place, full of iconic characters, epic battles, and unforgettable storylines.
    From the humble beginnings of Stan Lee's first comic book creations to the modern-day blockbusters that dominate the box
    office, Marvel has consistently pushed the boundaries of what's possible in the world of superheroes. With a diverse cast
    of characters that includes the likes of Iron Man, Captain America, Black Widow, and the Hulk, there's something for
    everyone in the Marvel universe. Whether you're a lifelong fan or just discovering the magic of Marvel, the intricate web
    of interconnected stories and characters is sure to captivate and inspire. With new movies, TV shows, and comic books
    being released all the time, the Marvel universe is constantly evolving and expanding, offering endless opportunities for
    fans to engage with their favorite characters and storylines.
  </p>
</template>

<style scoped>
div {
  margin: 3em 2em;
  padding: 1em 2em;

  display: flex;
  flex-direction: column;
  align-items: center;

  /* border: 1px solid blue; */

  h1 {
    font-size: 7rem;
    line-height: 8rem;
    font-weight: 900;
    color: var(--c-red);
  }

  p {
    font-size: 1.4rem;
    line-height: 2rem;
    font-weight: 600;
    color: var(--color-text);
  }
}

p {
  font-size: 1.1rem;
  line-height: 1.8rem;
  margin: 0 2em;
  padding: 0.5em 0.1em;
  text-align: justify;
  font-weight: 500;
  color: var(--color-text-bright);
}
</style>
