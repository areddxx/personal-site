<template>
  <div class="container">
    <Navigation />
    <Nuxt />
    <Footer />
  </div>
</template>

<style lang="scss">
html {
  font-family:
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}
body {
  //background-color: #F7F8FA;
  //color: #292D31;
  background-color: #292D3E;
  color: #DDD;
}

h1 {
  font-weight: normal;
}

a {
  text-decoration: none;
  color: #80cbc4;
}

.container {
  padding: 0 30px;
  min-height: 100vh;
  display: flex;
  width: 1440px;
  max-width: 100%;
  flex-direction: column;
}

main {
  padding-top: 30px;
}
</style>
