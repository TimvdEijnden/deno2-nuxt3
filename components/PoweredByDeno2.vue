<template>
  <div class="deno">
    powered by deno <img alt="Deno 2 logo" src="/deno2.png"/>
  </div>
</template>

<style scoped>
.deno {
  padding-top: 2rem;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 2rem;

  img {
    height: 2rem;
  }
}

@media (prefers-color-scheme: dark) {
  .deno {
    background: black;
    color: white;
  }

  img {
    filter: invert(1);
  }
}
</style>