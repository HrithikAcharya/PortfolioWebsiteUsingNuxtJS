<template>
   <a :href="link" target="_blank">
    <div class="project-card">
      <h4 class="text-xl font-extrabold text-gray-900 md:text-xl lg:text-xl dark:text-white">{{ title }}</h4>
      <p class="text-justify">{{ description }}</p>
    </div>
  </a>
  </template>
  
  <script>
  export default {
    props: ['title', 'description', 'link']
  }
  </script>
  
  <style scoped>
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
  .project-card {
    padding: 1.5rem;
    margin: 1rem 0;
  }
  .project-card:hover {
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    padding: 1.5rem;
    margin: 1rem 0;
  }
  </style>