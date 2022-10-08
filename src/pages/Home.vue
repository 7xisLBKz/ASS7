<template>
<div>
  <Navbar />
  <section class="home">

    <div class="image">
        <img src="images/profile.png" alt="">
    </div>

    <div class="content">
        <h3>hi, i am {{name}}</h3>
        <span>{{motto}}</span>
        <p>{{content}}</p>
        <a href="about.html" class="btn"> about me <i class="fas fa-user"></i> </a>
    </div>

</section>
</div>
</template>

<script>
import Navbar from '../components/Navbar.vue'
export default {
  components: { Navbar }, 
  data() {
        return {
          name: 'Yupharat pheng-aun',
          motto: 'Belive the Impossible is Possible.',
          content: 'More 5 Years of Experienced Developer with Front-end and Back-end .NET programming in the information technology and service industry. Skilled in HTML, CSS, Javascript, Angular, React, MVC, C# and ORACLE, SQL database tools. A strong engineering professional with a Bachelor of Engineering (BE) focused on Computer Engineering from Bangkok University.',
        }
    }
}
</script>

<style>

</style>