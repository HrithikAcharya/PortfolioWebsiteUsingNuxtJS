<template>
    <nav>
      <ul>
        <li class = "transition ease-in-out delay-150 hover:scale-125 hover:bg-black-500 duration-300"><nuxt-link to="/">Home</nuxt-link></li>
        <li class = "transition ease-in-out delay-150 hover:scale-125 hover:bg-black-500 duration-300"><nuxt-link to="#about">About Me</nuxt-link></li>
        <li class = "transition ease-in-out delay-150 hover:scale-125 hover:bg-black-500 duration-300"><nuxt-link to="#skills">Skills</nuxt-link></li>
        <li class = "transition ease-in-out delay-150 hover:scale-125 hover:bg-black-500 duration-300"><nuxt-link to="#projects">Projects</nuxt-link></li>
        <li class = "transition ease-in-out delay-150 hover:scale-125 hover:bg-black-500 duration-300"><nuxt-link to="#contact-info">Contact</nuxt-link></li>
      </ul>
    </nav>
  </template>
  
  <style scoped>
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
  nav {
    background: #333;
    color: #fff;
    padding: 1rem;
  }
  ul {
    list-style: none;
    display: flex;
    justify-content: space-around;
  }
  </style>