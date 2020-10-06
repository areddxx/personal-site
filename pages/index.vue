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
</style>
