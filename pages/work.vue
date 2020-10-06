<template>
  <main>
    <h1>A few sites I've built, designed, & maintained.</h1>

    <section class="projects">
      <h2>Professional Projects</h2>
      <div class="project-item">
        <a target="_blank" href="https://www.moonmotherhemp.com/">Moon Mother Hemp</a>
        <p>
          Custom Woocommerce Theme
          <span>Built @ToolStudios.</span>
        </p>
      </div>
      <div class="project-item">
        <a target="_blank" href="https://goldenaluminum.com/">Golden Aluminum</a>
        <p>
          Website Design
          <span>Built @ToolStudios.</span>
        </p>
      </div>
      <div class="project-item">
        <a target="_blank" href="https://www.grassrootscannabis.com/">Grassroots Cannabis</a>
        <p>
          Design & Custom Woocommerce Theme
          <span>Built @ToolStudios.</span>
        </p>
      </div>
      <div class="project-item">
        <a target="_blank" href="https://greenhouseil.com/">Greenhouse Dispensaries</a>
        <p>
          Website Design
          <span>Built @ToolStudios.</span>
        </p>
      </div>
      <div class="project-item">
        <a target="_blank" href="https://myherbology.com/">Herbology Dispensaries</a>
        <p>
          Website Design
          <span>Built @ToolStudios.</span>
        </p>
      </div>
      <div class="project-item">
        <a target="_blank" href="https://trulieve.com/">Trulieve</a>
        <p>
          DevOps // Design Support // Dev Support
          <span>Built @ToolStudios.</span>
        </p>
      </div>
      <div class="project-item">
        <a target="_blank" href="https://bondroadcannabis.com/">Bond Road Cannabis</a>
        <p>
          Custom WordPress Theme
          <span>Built @ToolStudios.</span>
        </p>
      </div>
      <div class="project-item">
        <a target="_blank" href="https://thesolartrees.com/">The Solar Trees</a>
        <p>
          Design & Custom WordPress Theme
          <span>Built @ToolStudios.</span>
        </p>
      </div>
      <div class="project-item">
        <a target="_blank" href="https://www.kolapartners.com/">Kola Partners</a>
        <p>
          WordPress Theme
          <span>Built @ToolStudios.</span>
        </p>
      </div>
    </section>
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
  margin-bottom: 60px;
}
h2 {
  margin-bottom: 15px;
}
.projects {
  margin-bottom: 45px;
}
.project-item {
  padding-bottom: 15px;
  &::after {
    display: block;
    width: 150px;
    background-color: white;
    height: 1px;
    margin-top: 15px;
    content: '';
    opacity: .1;
  }
  &:last-of-type {
    &::after {
      display: none;
    }
  }
  a {
    font-size: 18px;
    margin-bottom: 7px;
    display: inline-block;
    &:hover {
      text-decoration: underline;
    }
  }
  span {
    opacity: 0.6;
    margin-left: 7px;
    @media screen and (max-width: 700px) {
      display: block;
      margin-left: 0;
      margin-top: 3px;
    }
  }
}
</style>
