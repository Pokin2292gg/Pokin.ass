<template>
    <div>
        <Navbar />
        <section class="home">
            <div class="image">
                <img src="images/Profile.jpg" alt="">
            </div>
            <div class="content">
                <h3>hi, i am Pokin Kittiyapinit</h3>
                <span>Learning by Dog.</span>
                <p>I From Thailand</p>
                <a href="about.html" class="btn"> about me <i class="fas fa-user"></i> </a>
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