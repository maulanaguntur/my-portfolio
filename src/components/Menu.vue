<!-- <script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script> -->
<template>
    <section class="navigation">
        <nav class="navbar navbar-expand-lg navbar-custom navbar-fixed-top">
            <div class="container-fluid">
                <div class="nav-wrapper">
                    <a class="navbar-brand" href="#home">
                        <g-image src="/images/logo.png" width="36" />
                    </a>
                </div>
                <div class="nav-wrapper-menu">
                    <ul class="navbar-nav">
                            <li class="nav-item">
                                <!-- <g-link to="/home" class="nav-link">Home</g-link> -->
                                <a href="#home" class="nav-link">Home</a>
                            </li>
                            <li class="nav-item">
                                <!-- <g-link to="/about" class="nav-link">About</g-link> -->
                                <a href="#about" class="nav-link">About</a>
                            </li>
                            <li class="nav-item">
                                <!-- <g-link to="/project" class="nav-link">My Projects</g-link> -->
                                <a href="#project" class="nav-link">My Portfolio</a>
                            </li> 
                            <li class="nav-item">
                                <g-link to="/blog" class="nav-link">Blog</g-link>
                            </li>
                            <a href=" https://wa.me/082121697108" class="btn btn-contact">Get in Touch</a>
                    </ul>
                </div>
            </div>
        </nav>
    </section>
</template>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<script>
import $ from 'jquery'

export default {
name: "Menu",
};
$(document).ready(function() {
    $(window).on("scroll", function() {
        if ($(this).scrollTop() > 100) {
            $(".navbar").addClass("scrolled");
        } else {
            $(".navbar").removeClass("scrolled");
        }
    });
});
// $(document).ready(function() {
//         // Function to handle scroll event
//         $(window).scroll(function() {
//             // Check if scroll position is greater than 50px
//             if ($(this).scrollTop() > 50) {
//                 // Add 'navbar-fix' class to the navbar
//                 $('.navbar').addClass('navbar-fix');
//             } else {
//                 // Remove 'navbar-fix' class from the navbar
//                 $('.navbar').removeClass('navbar-fix');
//             }
//         });
// });
// $(window).scroll(function(){
// $('nav').toggleClass('scrolled',$(this).scrollTop() > 50);
// });
</script>
