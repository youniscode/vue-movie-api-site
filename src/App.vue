<template>
  <header>
    <router-link to="/">
      <h1>Vue<span></span>Movies</h1>
    </router-link>
  </header>
  <main>
    <router-view />
  </main>
  <footer></footer>
  <router-view />
</template>














<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Fira Sans", sans-serif;

  &::selection {
    background: transparentize(#42b883, 0.5);
  }

  body {
    background-color: #35495e;
  }

  a {
    text-decoration: none;
  }
}
</style>
