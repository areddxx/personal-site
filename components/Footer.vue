<template>
  <div class="footer">
    <NuxtLink class="link" to="/">Austin Redd</NuxtLink>
    <div class="social-links">
      <a href="https://dribbble.com/areddxx" target="_blank">
        <font-awesome-icon :icon="['fab', 'dribbble']" />
      </a>
      <a href="https://twitter.com/areddxx" target="_blank">
        <font-awesome-icon :icon="['fab', 'twitter']" />
      </a>
      <a href="https://instagram.com/areddxx" target="_blank">
        <font-awesome-icon :icon="['fab', 'instagram']" />
      </a>
    </div>
  </div>
</template>

<style lang="scss">
.footer {
  margin: 30px 0;
  display: flex;
  justify-content: space-between;
  margin-top: auto;
  a {
    color: #676E95;
  }
}
.social-links a {
  margin-right: 15px;
}
.social-links a:last-of-type {
  margin-right: 0;
}
</style>
