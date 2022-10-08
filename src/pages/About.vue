<template>
    <div>
        <Navbar />

        <section class="About">

            <h1 class="heading"> MY <span>ABILITIES</span> </h1>

            <div class="row">

                <div class="info-container">

                    <h1>personal info</h1>

                    <div class="box-container">

                        <div class="box">
                            <h3> <span>name : </span> Theranan Pornsawanwattana </h3>
                            <h3> <span>age : </span> 25 </h3>
                            <h3> <span>email : </span> theranan.porn@bumail.net </h3>
                            <h3> <span>address : </span> Pathum Thani, Thailand 12000 </h3>
                        </div>

                        <div class="box">
                            
                            <h3> <span>Skill : </span> Music Mixing </h3>
                            <h3> <span>Experience : </span> 3 years </h3>
                            <h3> <span>Language : </span> Thai , English </h3>
                        </div>

                    </div>

                    

                </div>

                <div class="count-container">

                    <div class="box">
                        <h3>Experiences</h3>
                        <p>2 years (Self Study) + 1 years (Study in Studio)</p>
                    </div>

                    <div class="box">
                        <h3>Happy Clients</h3>
                        <p>5+</p>
                    </div>

                    <div class="box">
                        <h3>Project Completed</h3>
                        <p>10+</p>
                    </div>

                    <div class="box">
                        <h3>Certificates</h3>
                        <p>2</p>
                    </div>

                </div>

            </div>

        </section>

        <!-- about section ends -->

        <!-- skills section starts  -->

        <section class="skills">

            <h1 class="heading"> <span>My</span> Skills </h1>

            <div class="box-container">
                <div class="box">
                    <img src="images/icon-1.png">
                    <h3>REAPER DAW</h3>
                </div>
                <div class="box">
                    <img src="images/icon-2.png">
                    <h3>Logic Pro</h3>
                </div>
                <div class="box">
                    <img src="images/icon-3.png">
                    <h3>Ableton Live</h3>
                </div>
                <div class="box">
                    <img src="images/icon-4.png">
                    <h3>Cubase</h3>
                </div>
                <div class="box">
                    <img src="images/icon-5.png">
                    <h3>Pro Tools</h3>
                </div>
                <div class="box">
                    <img src="images/icon-6.png">
                    <h3>Adobe Audition</h3>
                </div>
            </div>

        </section>

        <!-- skills section ends -->

    </div>
</template>

<script>
import Navbar from "../components/Navbar.vue";

export default {
  components: { Navbar },
  }
  ;
</script>

<style>
</style>