<template>
  <main>
    <h1>UI developer & designer, based in Niwot, Colorado. Currently working at ToolStudios.</h1>
    <a href="mailto:hello@austinredd.com" class="contact-intro">Get in touch</a>
  </main>
</template>

<script>
export default {
  data () {
    return {
      title: 'Austin Redd | Developer & Designer'
    }
  },
  head () {
    return {
      title: this.title,
      meta: [
        // hid is used as unique identifier. Do not use `vmid` for it as it will not work
        {
          hid: 'description',
          name: 'description',
          content: 'Developer & Designer'
        }
      ]
    }
  }
}
</script>

<style lang="scss">
  h1 {
    max-width: 100%;
    width: 700px;
    line-height: 1.5;
  }
  .contact-intro {
    font-size: 26px;
    margin-top: 45px;
    text-decoration: none;
  }
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
  width: 1000px;
  max-width: 100%;
  flex-direction: column;
  margin: 0 auto;
}

main {
  padding-top: 30px;
}
</style>
