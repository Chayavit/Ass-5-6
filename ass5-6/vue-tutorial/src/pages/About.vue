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
                            <h3> <span>name : </span> Chayavit Wongharimart </h3>
                            <h3> <span>age : </span> 21 </h3>
                            <h3> <span>email : </span> chayavit.wong@bumail.net </h3>
                            <h3> <span>address : </span> bangkok, Thailand 10900 </h3>
                        </div>

                        <div class="box">
                            <h3> <span>freelance : </span> available </h3>
                            <h3> <span>skill : </span> Full Stack Engineer </h3>
                            <h3> <span>experience : </span> 6 years </h3>
                            <h3> <span>language : </span> thai </h3>
                        </div>

                    </div>

                    <a href="/profilewithcss/files/resume.pdf" class="btn"> download CV <i class="fas fa-download"></i>
                    </a>

                </div>

                <div class="count-container">

                    <div class="box">
                        <h3>5+</h3>
                        <p>years of experience</p>
                    </div>

                    <div class="box">
                        <h3>10+</h3>
                        <p>happy clients</p>
                    </div>

                    <div class="box">
                        <h3>20+</h3>
                        <p>project completed</p>
                    </div>

                    <div class="box">
                        <h3>5+</h3>
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
                    <img src="images/html.png">
                    <h3>html</h3>
                </div>
                <div class="box">
                    <img src="images/css.png">
                    <h3>css</h3>
                </div>
                <div class="box">
                    <img src="images/javascript.png">
                    <h3>javascript</h3>
                </div>
                <div class="box">
                    <img src="images/ps.png">
                    <h3>Photoshop </h3>
                </div>
                <div class="box">
                    <img src="images/live2d.jpg">
                    <h3>live2d</h3>
                </div>
                <div class="box">
                    <img src="images/clip studio paint.png">
                    <h3>clip studio paint</h3>
                </div>
            </div>

        </section>

        <!-- skills section ends -->

        <!-- education section starts  -->

        <section class="education">

            <h1 class="heading"> <span>my</span> education </h1>

            <div class="box-container">

                <div class="box">
                    <i class="fas fa-briefcase"></i>
                    <span>2014 - 2020</span>
                    <h3>เรียนมัธยมที่โรงเรียนสารวิทยา</h3>
                    <p>เรียนม.ต้นที่โรงเรียนสารวิทยา และต่อม.ปลายที่โรงเรียนเดิมสายวิทย์-คณิต</p>
                </div>

                <div class="box">
                    <i class="fas fa-briefcase"></i>
                    <span>2021 - now</span>
                    <h3>กำลังศึกษาที่มหาวิทยาลัยกรุงเทพ</h3>
                    <p>เรียนต่อมหาลัยคณะวิศวกรรมศาสตร์ สาขามัลติมีเดียและเอ็นเตอร์เทนเมนต์</p>
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