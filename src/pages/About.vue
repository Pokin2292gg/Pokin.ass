<template>
    <div>
        <Navbar />

        <section class="about">

            <h1 class="heading"> about <span>me</span> </h1>

            <div class="row">

                <div class="info-container">

                    <h1>personal info</h1>

                    <div class="box-container">

                        <div class="box">
                            <h3> <span>name : </span> Pokin Kittiyapinit </h3>
                            <h3> <span>age : </span> 19 </h3>
                            <h3> <span>email : </span> SasNarok@bumail.net </h3>
                            <h3> <span>address : </span> Thailand  </h3>
                        </div>

                        <div class="box">
                            <h3> <span>Commission : </span> Open </h3>
                            <h3> <span>skill : </span> sleep </h3>
                            <h3> <span>experience : </span> 19 years </h3>
                            <h3> <span>language : </span> thai </h3>
                        </div>

                    </div>

                    <a href="/profilewithcss/files/resume.pdf" class="btn"> download CV <i class="fas fa-download"></i>
                    </a>

                </div>

                <div class="count-container">

                    <div class="box">
                        <h3>1</h3>
                        <p>years of experience</p>
                    </div>

                    <div class="box">
                        <h3>3+</h3>
                        <p>happy clients</p>
                    </div>

                    <div class="box">
                        <h3>1</h3>
                        <p>project completed</p>
                    </div>

                    <div class="box">
                        <h3>1</h3>
                        <p>Certificates</p>
                    </div>

                </div>

            </div>

        </section>

        <!-- about section ends -->

        <!-- skills section starts  -->

        <section class="skills">

            <h1 class="heading"> <span>my</span> skills </h1>

            <div class="box-container">
                <div class="box">
                    <img src="images/icon-1.png">
                    <h3>Photoshop</h3>
                </div>
                <div class="box">
                    <img src="images/icon-2.png">
                    <h3>Procreate</h3>
                </div>
                <div class="box">
                    <img src="images/icon-3.png">
                    <h3>photography</h3>
                </div>
                <div class="box">
                    <img src="images/icon-4.png">
                    <h3>Vegus Pro</h3>
                </div>
                <div class="box">
                    <img src="images/icon-5.png">
                    <h3>Maya</h3>
                </div>
                <div class="box">
                    <img src="images/icon-6.png">
                    <h3>Live2d Cubism</h3>
                </div>
            </div>

        </section>

        <!-- skills section ends -->

        <!-- education section starts  -->

        <section class="education">

            <h1 class="heading"> <span>my</span> experience </h1>

            <div class="box-container">

                <div class="box">
                    <i class="fas fa-briefcase"></i>
                    <span>2021 - 2022</span>
                    <h3>Start Study at Bangkok University</h3>
                    <p>Still Study
                        </p>
                </div>

                
            </div>

        </section>
    </div>
</template>

<script>
import Navbar from "../components/Navbar.vue";
export default {
    components: { Navbar }
}
</script>

<style>

</style>