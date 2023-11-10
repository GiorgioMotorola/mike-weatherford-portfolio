<template>
  
    <div class="project-links">
      <h1>Projects</h1>
      <a href="https://ff.mweatherford.rocks/" target="_blank">Fighting Frames</a>
      
        <a href="https://todo.mweatherford.rocks/" target="_blank"
          >Strikethrough - ToDo List</a
        >
        <a
          href="https://github.com/GiorgioMotorola/MediaLibrarian"
          target="_blank"
          >Media Librarian</a
        >
        <a href="https://giorgiomotorola.github.io/gni-records/" target="_blank"
          >GNI Records</a
        >
        <a
          href="https://giorgiomotorola.github.io/proxima-hotel-and-resort/"
          target="_blank"
          >Proxima Hotel Resort</a
        >
      </div>
    
  </template>
  
  <script>
  export default {
    name: 'ProjectLinks',
  }
  </script>
  
  <style scoped>

  .project-links {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 10px;
    margin-right: 35px;
  }

  .project-links h1 {
    color: #213555;
    border-bottom: solid;
    margin-bottom: 10px;
  }

  .project-links a {
    text-decoration: none;
    font-weight: 900;
    color: #1F1717;
    font-size: 18px;
    cursor: pointer;
    will-change: transform;
    transition: transform 450ms;
  }

  .project-links a:hover {
    transition: transform 150ms;
    transform: translateY(-5px);
  }

  @media screen and (max-width: 1300px) {
    .project-links {
      margin-bottom: 35px;
    }
  }

  @media screen and (max-width: 650px) {
    .project-links {
      background-color: #ffffff;
    }

    .project-links a:hover {
      transition: none;
      transform: none;
    }
  }

</style>

  