<template>
  <router-view />
</template>

<style lang="scss">
// RESET
*,
*::before,
*::after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

// Properties

:root {
  --color-primary: hsla(179, 100%, 24%, 1);
  --color-white: #ffffff;
}

// BASE
html {
  font-size: 10px;
  font-family: 'Roboto', sans-serif;

  // scroll-bahavior: smooth;
}

img {
  /* All images should be 100% of their parent container */
  width: 100%;
  max-width: 100%;
}

a {
  text-decoration: none;
}

p {
  font-size: 1.6rem; /* 16px */
}
</style>
