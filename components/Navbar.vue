<template>
  <section class="container-1">
    <nav id="nav">
      <NuxtLink to="/" class="logo">Nextworld</NuxtLink>
      <div class="nav-list">
        <NuxtLink to="/">Home</NuxtLink>
        <NuxtLink to="/">About</NuxtLink>
        <NuxtLink to="/">Destinations</NuxtLink>
        <NuxtLink to="/">Our Blog</NuxtLink>
      </div>
      <div class="login">
        <NuxtLink to="/">Sign Up</NuxtLink>
        <NuxtLink to="/">Login</NuxtLink>
      </div>
      <div class="hamburger">
        <span class="bar"></span>
        <span class="bar"></span>
        <span class="bar"></span>
      </div>
    </nav>
  </section>
</template>

<!-- <script>
let nav = new Vue({
  el: '#nav',
  data: {
    navOpen: false,
  },
});
</script> -->

<!-- <script>
export default {
  data() {
    return {
      name: 'Alexa',
    };
  },
  methods: {
    mobileMenu(e) {
      alert(`Hi, im ${this.name}!`);

      if (e) {
        alert(event.target.classList);
      }
    },
  },
};
</script> -->

<!-- <script setup>
const hamburger = document.querySelector('.hamburger');
const navMenu = document.querySelector('.nav-list');
const navLink = document.querySelectorAll('.nav-list a');
const navLogin = document.querySelector('.login');
const navLog = document.querySelectorAll('.login a');

hamburger.addEventListener('click', mobileMenu);
navLink.forEach((n) => n.addEventListener('click', closeMenu));
navLog.forEach((n) => n.addEventListener('click', closeMenu));

function mobileMenu() {
  hamburger.classList.toggle('active');
  navMenu.classList.toggle('active');
  navLogin.classList.toggle('active');
}

function closeMenu() {
  hamburger.classList.remove('active');
  navMenu.classList.remove('active');
  navLogin.classList.remove('active');
}
</script> -->
