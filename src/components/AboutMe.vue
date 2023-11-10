<template>
    <div class="about-me">
      <img src="../assets/dev-img.jpg" alt="An image of me." />
      <div class="text">
      <h1 id="hello"><span>Hello!</span></h1>
      <h1 id="mike">I'm Mike. </h1>
      <h2><span>
        I am a software developer with an insatiable
          curiosity and a strong passion for learning and creating. My journey
          started with the University of Helsinki's Java MOOC, and I've since
          successfully completed the Software Development and Web Development
          courses offered by the state-funded coding bootcamp Code: You. Along
          the way, I've crafted projects using a variety of languages and
          technologies such as HTML, CSS, JavaScript, C#, SQL, and Vue.js. I'm
          eager to collaborate and look forward to working with you! </span>
      </h2>
    </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'AboutMe',
  }
  </script>
  
  <style scoped>

  .about-me {
    padding-top: 90px;
    display: flex;
    padding-right: 200px;
    padding-left: 200px;
    gap: 100px;
  }

  .about-me img {
    width: 800px;
    height: 400px;
    border-style: double;
    border-color: #213555;
    border-width: 10px;
    margin-right: 5%;
  }

  .about-me h2 {  
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: left;
    font-size: 20px;
    white-space: pre-line;
    color: #213555;
  }

  .text {
    border-bottom: 1px solid #606060; 
  }

  #hello {
    font-size: 25px;
    color: rgb(104, 104, 105);
    border-bottom: 1px solid #606060; 
    line-height: 0.1em;
    margin: 5px 0 20px; 
  }

  #mike {
    font-size: 50px;
    color: #CE5A67;
  }

  #hello span {
    background:#fff; 
    padding:0 10px; 
  }

  @media screen and (max-width: 1760px) {
    .about-me h2 {
      font-size: 17px;
    }

    .about-me {
      padding-right: 50px;
      padding-left: 50px;
    }
  }

  @media screen and (max-width: 1360px) {
    .about-me {
      flex-direction: column;
    }
    .about-me img {
      width: 400px;
      display: block;
      margin-left: auto;
      margin-right: auto;
    }
  }

  @media screen and (max-width: 970px) {
    .about-me img {
      width: 400px;
    }
  }

  @media screen and (max-width: 790px) {
    .about-me h2 {
      font-size: 19px;
    }
  }

  @media screen and (max-width: 650px) {
    .about-me img {
      width: 300px;
      height: 300px;
    }

    .about-me h2 {
      font-size: 15px;
      white-space: normal;
      padding-top: 1px;
    }

    .about-me {
      margin: 0%;
      padding: 10px;
      background-color: #ffffff;
    }

    .about-me img:hover {
      transition: none;
      transform: none;
    }
  } 
</style>

  