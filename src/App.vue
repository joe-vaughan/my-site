<template>
  <div class="wrapper">
    <SiteIntro/>
  </div>
</template>

<script>

import SiteIntro from './components/SiteIntro.vue';

export default {
  name: 'App',
  components: {
    SiteIntro
  }
}
</script>

<style>

@import url('https://fonts.googleapis.com/css2?family=Lunasima:wght@400;700&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');

* {
  margin: 0;
  border: 0;
  padding: 0;
}

.wrapper {
  margin-top: 2.5vh;
  margin-left: 5vw;
  margin-right: 25vw;
}

ul {
  margin-left: 2.5vw;
}

body {
  font-family: 'Lunasima', sans-serif;
}

h1 {
  font-size: 3rem;
  margin-bottom: 1rem;
  letter-spacing: -0.1rem;
}

.prose {
  font-size: 1.5rem;
  letter-spacing: -0.05rem;
  line-height: 1.5;
  margin-bottom: 1rem;
}

.emphasis {
  font-weight: 600;
}

a {
  color: blue;
  text-decoration: none;
}

a:hover {
  text-decoration: underline
}

</style>
