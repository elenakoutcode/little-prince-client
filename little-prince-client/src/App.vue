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

  // Font Sizes
  --fs-2: 0.5rem; /* 8px */
  --fs-3: 0.75rem; /* 12px */
  --fs-4: 0.875rem; /* 14px */
  --fs-5: 1rem; /* 16px */
  --fs-6: 1.125rem; /* 18px */
  --fs-7: 1.5rem; /*24px*/
  --fs-8: 1.875rem; /* 30px */
  --fs-9: 2.25rem; /* 36px */

  --fs-3-2: clamp(0.5rem, 0.4167rem + 0.3704vw, 0.75rem); /* 12-8 */
  --fs-4-3: clamp(0.75rem, 0.7083rem + 0.1852vw, 0.875rem); /* 14-12 */
  --fs-5-3: clamp(0.75rem, 0.6667rem + 0.3704vw, 1rem); /* 16-12 */
  --fs-6-4: clamp(0.875rem, 0.7917rem + 0.3704vw, 1.125rem); /* 18-14 */
  --fs-7-5: clamp(1rem, 0.8333rem + 0.7407vw, 1.5rem); /* 24-16 */
  --fs-8-6: clamp(1.125rem, 0.875rem + 1.1111vw, 1.875rem); /* 30-18 */
  --fs-9-7: clamp(1.5rem, 1.25rem + 1.1111vw, 2.25rem); /* 36-24 */

  // Space Sizing
  --size-2: 0.25rem; /* 4px */
  --size-3: 0.5rem; /* 8px */
  --size-4: 0.75rem; /* 12px */
  --size-5: 1rem; /* 16px */
  --size-6: 1.5rem; /* 24px */
  --size-7: 2rem; /* 32px */
  --size-8: 3rem; /* 48px */
  --size-9: 4rem; /* 64px */
  --size-10: 6rem; /* 96px */
  --size-11: 8rem; /* 128px */
  --size-12: 12rem; /* 192px */
  --size-13: 16rem; /* 256px */
  --size-14: 24rem; /* 384px */
  --size-15: 32rem; /* 512px */
  --size-16: 40rem; /* 640px */
  --size-17: 48rem; /* 768px */

  --size-4-3: clamp(0.5rem, 0.4167rem + 0.3704vw, 0.75rem); /* 12-8 */
  --size-5-3: clamp(0.5rem, 0.3333rem + 0.7407vw, 1rem); /* 16-12 */
  --size-6-4: clamp(0.75rem, 0.5rem + 1.1111vw, 1.5rem); /* 24-12 */
  --size-7-5: clamp(1rem, 0.6667rem + 1.4815vw, 2rem); /* 32-16 */
  --size-8-6: clamp(1.5rem, 1rem + 2.2222vw, 3rem); /* 48-24 */
  --size-9-7: clamp(1rem, 0rem + 4.4444vw, 4rem); /* 64-32 */
  --size-10-8: clamp(3rem, 2rem + 4.4444vw, 6rem); /* 96-48 */
  --size-11-9: clamp(4rem, 2.6667rem + 5.9259vw, 8rem); /* 128-64 */
  --size-12-10: clamp(4rem, 2.6667rem + 5.9259vw, 8rem); /* 192-96 */
  --size-13-11: clamp(8rem, 5.3333rem + 11.8519vw, 16rem); /* 256-128 */
  --size-14-12: clamp(12rem, 8rem + 17.7778vw, 24rem); /* 384-192 */
  --size-15-13: clamp(16rem, 10.6667rem + 23.7037vw, 32rem); /* 512-256 */
  --size-16-14: clamp(24rem, 18.6667rem + 23.7037vw, 40rem); /* 640-384 */
  --size-17-15: clamp(32rem, 26.6667rem + 23.7037vw, 48rem); /* 768-512 */
}

// BASE

body {
  min-height: 100vh;
  text-rendering: optimizeSpeed;
  line-height: 1;
}

html {
  font-size: 10px;
  font-family: 'Roboto', sans-serif;
}

/* Make images easier to work with */
img,
picture {
  max-width: 100%;
  display: block;
}

a {
  text-decoration: none;
}

p {
  font-size: 1.6rem; /* 16px */
}

ul {
  list-style: none;
}
</style>
