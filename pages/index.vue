<template>
    <div>
      <Navbar />
      <div class = "container text-left sm:text-left p-8 ">
        <h1 class = "mb-4 text-6xl font-extrabold text-gray-900 md:text-6xl lg:text-6xl dark:text-white ">Hrithik Acharya</h1>
      <section id="about">
        <h2 class = "mb-4 text-4xl font-extrabold text-gray-900 md:text-2xl lg:text-3xl dark:text-white">About Me</h2>
        <p class="text-justify text-balance">As an engineer with a passion for the software industry, I&apos;m dedicated to bridging the gap between hardware and software. My journey has been marked by a strong commitment to learning and professional growth. I have completed a comprehensive Software Testing course at QSpiders, where i honed my programming and testing skills. In addition, i have gained practical experience through an internship in Image Data Analysis using ML, allowing me to apply theoretical knowledge to real-world problems. Currently, i&apos;m focused on expanding my expertise in cloud computing, aiming to leverage these skills in creating innovative and efficient software solutions. My diverse educational background and hands-on experience equipped me with a unique perspective and the ability to adapt to various technological environments. I&apos;m excited about the opportunities ahead and am eager to contribute to the dynamic field of software engineering.</p>
      </section>
      <section id="skills">
        <h2 class = "mb-4 text-4xl font-extrabold text-gray-900 md:text-2xl lg:text-3xl dark:text-white">Skills</h2>
        <ul class = "list-disc list-inside">
          <li class=" text-justify text-balance">Core Java</li>
          <li class=" text-justify text-balance">Selenium Testing (Java)</li>
          <li class=" text-justify text-balance" >HTML5</li>
          <li class=" text-justify text-balance">CSS3</li>
          <li class=" text-justify text-balance">Javascript</li>
          <li class=" text-justify text-balance">MySQL</li>
          <li class=" text-justify text-balance">Python</li>
          <li class=" text-justify text-balance">NodeJS</li>
          <li class=" text-justify text-balance">Express</li>
          <li class=" text-justify text-balance">EJS</li>
          <li class=" text-justify text-balance">React</li>
        </ul>
      </section>
      <section id="projects">
        <h2 class = "mb-4 text-4xl font-extrabold text-gray-900 md:text-2xl lg:text-3xl dark:text-white" >My Projects</h2>
        <ProjectCard title="Swarm Exploration and Target Searching" description="A simulation project carried out in Webots as a minor project, which involved locating a target in a
        maze using a swarm of robots and implemented the same using hardware in a maze-like environment using DFS Algorithm." link="https://github.com/Guruprasad-G/Swarm-Exploration-and-Target-Searching" />
        <ProjectCard title="Image Data Analysis: Object Detection Using EFFICIENTDET" description="EfficientDet Architecture was used in this project to detect objects for autonomous vehicles." link="https://drive.google.com/drive/folders/1k-0Qe3wZKHXr1hniECE4xqPnRXW45TBw?usp=sharing"></ProjectCard>
        <ProjectCard title="Login Authentication System" description="This project involved developing a secure login authentication system." link="https://github.com/HrithikAcharya/HrithikAcharya.devtern" />
        <ProjectCard title="Weather App" description="This project is Simple Weather application made using React which gives weather condition of the
        various cities across the world." link="https://github.com/HrithikAcharya/ReactWeatherApp"></ProjectCard>
        <ProjectCard title="Spotify (Clone)" description="This project involved replicating the user interface of Spotify." link="https://github.com/HrithikAcharya/Spotify_Clone"></ProjectCard>
        <ProjectCard title="Tribute to Doctors" description="Article-type web pages about the doctors who perished in the second wave of COVID 19." link="https://github.com/HrithikAcharya/HrithikAcharya.TIE"></ProjectCard>
        <ProjectCard title="Portfolio website using Nuxt.js" description="This project involved building a portfolio website using Nuxt.js" link="https://github.com/HrithikAcharya/PortfolioWebsiteUsingNuxtJS"></ProjectCard>
      </section>
      </div>
      <Footer />
    </div>
  </template>
  
  <script>
  import Navbar from '~/components/Navbar.vue';
  import ProjectCard from '~/components/ProjectCard.vue';
  import Footer from '~/components/Footer.vue';
  
  export default {
    components: {
      Navbar,
      ProjectCard,
      Footer,
    }
  }
  </script>