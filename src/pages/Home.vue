<template>
 <div>
    <navbar />
    <section class="home">

<div class="image">
    <img src="images/profile.png" alt="">
</div>

<div class="content">
    <h3>{{name}}</h3>
    <span>{{motto}}</span>
    <p>{{content}}</p>
    <a href="about.html" class="btn"> about me <i class="fas fa-user"></i> </a>
</div>

</section>
 </div>
</template>

<script>
import Navbar from '../components/Navbar.vue';
export default {
    components: { Navbar },
    data() {
        return {
            name: 'Theranan Pornsawanwattana',
            motto: 'You only live once',
            content: 'Hello, My Name Is Theranan Pornsawanwattana. My Nickname is Dome. Now I am studying in Multimedia & Entertainment Engineering At Bangkok University.',
        }
    }
}
</script>

<style>

</style>