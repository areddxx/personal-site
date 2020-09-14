<template>
  <nav>
    <h1>
      <NuxtLink class="link" to="/">
        Austin
        <span>Redd</span>
      </NuxtLink>
    </h1>
    <ul class="navigation">
      <NuxtLink class="link" to="/work">Work</NuxtLink>
      <a href="https://github.com/areddxx" target="_blank">
        <font-awesome-icon :icon="['fab', 'github']" />
      </a>
    </ul>
  </nav>
</template>

<style lang="scss">
nav {
  display: flex;
  align-items: baseline;
  margin: 30px 0;
  width: 100%;
  justify-content: space-between;
}
h1 a {
  color: #ddd;
  font-weight: 700;
  span {
    opacity: 0.75;
  }
}
.navigation {
  display: flex;
}
.navigation a {
  text-decoration: none;
  margin-right: 15px;
  color: #dddddd;
  &:last-of-type {
    margin-right: 0;
    color: #676e95;
  }
}
</style>
