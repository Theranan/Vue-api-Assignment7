<template>
    <div>
      <navbar />
      <h1 class="heading"> MY <span>Experience</span> </h1>
      <footer class="content margin-auto">
        <article class="text-center">
          <section>
            <span>"{{ motto2 }}"</span>
          </section>
          <section>
            <span>--- {{ author }} ---</span>
          </section>
          <hr />
          <div v-for="e in experiences" :key="e.title">
            <section class="title">
              <span>{{ e.title }}</span>
            </section>
  
            <article class="skill-menu margin-auto">
              <ul class="ul-navbar">
                <li class="menu-list">
                  <a href="index.html">{{ e.subtitle }}</a>
                </li>
                <li class="menu-list">
                  <a href="Experiences.html">{{ e.subtitle2 }}</a>
                </li>
              </ul>
            </article>
          </div>
        </article>
      </footer>
    </div>
  </template>
  
  <script>
  import Navbar from "../components/Navbar.vue";
  import axios from "axios";
  //https://6341701f16ffb7e275d1359a.mockapi.io/project/v1/Theranan
  export default {
    components: { Navbar },
    methods: {
      async fetchExperience() {
        try {
          let res = await axios.get(
            "https://6341701f16ffb7e275d1359a.mockapi.io/project/v1/Theranan"
          );
          this.experiences = res.data;
        } catch (error) {}
      },
    },
    data() {
      return {
        motto2: "Go High or Go Home",
        author: "Me",
        experiences: [],
      };
    },
    beforeMount() {
      this.fetchExperience();
    },
  };
  </script>
  
  <style>
  </style>