<template>
  <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
  <div>
    <IconsFolder />
    <div class="container">
      <AboutMe />
    </div>
      <ProjectLinks />
    
  </div>
</template>

<script>
import IconsFolder from './components/IconsFolder.vue'
import AboutMe from './components/AboutMe.vue'
import ProjectLinks from './components/ProjectLinks.vue'

export default {
  name: 'App',
  components: {
    IconsFolder,
    AboutMe,
    ProjectLinks,
  },
}
</script>



<style scoped>

  * {
    margin: 0%;
    font-family: 'Roboto', sans-serif;
  }

  body {
    background-color: #FCF5ED;
  }

  .container {
    display: flex;
    flex-direction: row;
    height: 95vh;
    width: 90%;
    height: auto;
    margin: 0 auto;
    margin-top: 10vh;
  }

  @media screen and (max-width: 1300px) {
    .container {
      flex-direction: column;
      width: 90%;
    }
  }

  @media screen and (max-width: 970px) {
    .container {
      flex-direction: column;
      width: 90%;
    }
  }

  @media screen and (max-width: 790px) {
    .container {
      width: 95%;
    }
  }

  @media screen and (max-width: 650px) {
    body {
      background-color: #FCF5ED;
    }

    .container {
      border-style: none;
      box-shadow: none;
      background-color: #FCF5ED;
      margin: 0;
    }
  }

</style>