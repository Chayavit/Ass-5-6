<template>
    <div>
        <Navbar />
        <section class="home">
            <div class="image">
                <img src="images/17.jpg" alt="">
            </div>
            <div class="content">
                <h3>hi, i am {{name}}</h3>
                <span>"Be yourself no matter whatever they say."</span>
                <p>Currently studying in the Faculty of Multimedia Engineering from Bangkok University.</p>
                <router-link to="/about" class="btn"> about me <i class="fas fa-user"></i> </router-link>
            </div>
        </section>
    </div>
</template>

<script>
import Navbar from '../components/Navbar.vue';
export default {
    components: { Navbar } ,
    data() {
        return {
            name: 'Chayavit Wongharimart'
        
        }
    }
}
</script>

<style>
</style>