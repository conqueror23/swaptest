<template>
  <nav>
    <nuxt-link to="/">Home</nuxt-link>
    <nuxt-link to="/jobs">Jobs</nuxt-link>
    <svg
      xmlns="http://www.w3.org/2000/svg"
      x="0px"
      y="0px"
      width="48"
      height="48"
      viewBox="0 0 24 24"
      style=" fill:#000000;"
    >
      <path d="M2 11H22V13H2zM2 5H22V7H2zM2 17H22V19H2z" />
    </svg>
  </nav>
</template>

<script>
export default {};
</script>

<style>
nav {
  background: #34495e;
  display: flex;
}
nav a {
  float: left;
  padding: 1em 1em;
  margin-left: 1em;
  text-decoration: none;
  background: red;
  border-radius: 10%;
}
svg {
  margin-left: 80%;
  float: right;
  /* display: none; */
}
</style>
