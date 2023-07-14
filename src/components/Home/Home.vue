<template>
    <div class="Container">
        <img src="../../assets/back.jpg" class="firstImage"/>
        <div class="firstData">
            <div class="firstText">
                <div class="Data">
                    <h1 class="Title Align">network IDS at scale</h1>
                    <h1 class="Align">easily manage distributed IDS probes</h1>
                    <h1 class="Align">through dispersed traffic sources</h1>
                    <h3 class="Align">an Open Source project to Visualize and Manage Suricata, Zeek & Arkime life cycles</h3>
                </div>
                <div class="Option">
                    <div class="SmallContainer">
                        <button class="Button">
                            OwlH is open source
                        </button>
                        <div class="white">
                            Flexible, scalable, no vendor lock-in and no license cost.
                            <a href="https://owlh.slack.com/" target="_blank" class="white">Join us on Slack</a>
                        </div>
                    </div>
                    <div class="SmallContainer">
                        <button class="Button">
                            Start using OwlH
                        </button>
                        <div class="white">
                            We will help you to be successful with your Owlh first deployment
                        </div>
                    </div>
                    <div class="SmallContainer">
                        <button class="Button">
                            How can we help you
                        </button>
                        <div class="white">
                            Become part of our Open Source 
                            <Router-link to="/community" class="white">Community</Router-link>
                            or access our
                            <Router-link to="/help" class="white">professional support and services.</Router-link>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="secondData">
            <!-- Slider main container -->
            <div class="swiper">
            <!-- Additional required wrapper -->
            <div class="swiper-wrapper">
                <!-- Slides -->
                <div class="swiper-slide"><img class="Img" src="../../assets/1.png"></div>
                <div class="swiper-slide"><img class="Img" src="../../assets/2.png"></div>
                <div class="swiper-slide"><img class="Img" src="../../assets/3.png"></div>
                <div class="swiper-slide"><img class="Img" src="../../assets/4.png"></div>
                <div class="swiper-slide"><img class="Img" src="../../assets/5.png"></div>
                <div class="swiper-slide"><img class="Img" src="../../assets/6.png"></div>
                <div class="swiper-slide"><img class="Img" src="../../assets/7.png"></div>
                <div class="swiper-slide"><img class="Img" src="../../assets/8.png"></div>
                <div class="swiper-slide"><img class="Img" src="../../assets/9.png"></div>
                <div class="swiper-slide"><img class="Img" src="../../assets/10.png"></div>   
            </div>
            <!-- If we need pagination -->
            <div class="swiper-pagination"></div> 
            <!-- If we need navigation buttons -->
            <div class="swiper-button-prev Change"></div>
            <div class="swiper-button-next Change"></div>
            <!-- If we need scrollbar -->
            <div class="swiper-scrollbar"></div>
            </div>
        </div>
        <div class="firstFooter">
            <div class="Text">
                OwlH was  born to help security engineers to manage, analyze and respond to network threats and anomalies using Open Source Network IDS Suricata and Zeek, offering: 
                <ul>
                    <li class="Li">Centralized Rule management and Network IDS nodes Configuration Management</li>
                    <li class="Li">Software TAP to capture cloud and distributed traffic in cloud and hybrid dispersed environments </li>
                    <li class="Li">Traffic Forensics with Moloch</li>
                    <li class="Li">Centralized Visualization</li>
                    <li class="Li">Compliance Mapping</li>
                </ul>
            </div>
        </div>
        <div class="secondFooter">
            <div class="secondText">
                Current - 
                <a href="https://github.com/OwlH-net/NEWS/blob/master/README.md" target="_blank">v0.11.x</a>
            </div>
        </div>
        <div class="thirdFooter">
            <div class="thirdText">
                How to manage multiple probes 
            <br>
            <div class="br"></div>
                When you have multiple probes, multiple sites, multiple security levels, or do you manage multiple companies, there are different ways to manage your Network IDS probes
            </div>
        </div>
        <div class="newOption">
                <div class="newSmallContainer">
                    <div class="newContent">
                        Stand-alone
                    </div>
                    <div>
                        Define each probe as an stand-alone system
                        <br>
                        <div class="br"></div>
                        Manage probes configuration individually
                    </div>
                </div>
                <div class="newSmallContainer">
                    <div class="newContent">
                        Group
                    </div>
                    <div>
                        Create groups of nodes 
                        <br>
                        <div class="br"></div>
                        share rulesets and services configurations between nodes in a same group 
                    </div>
                </div>
                <div class="newSmallContainer">
                    <div class="newContent">
                        RESTful API
                    </div>
                    <div>
                        Use REST API to manage and configure your probes,  
                        <br>
                        <div class="br"></div>
                        No user Interface, just your app and our API    
                    </div>
                </div>
            </div>
        <div>

        </div>
        <div>

        </div>
        <div>
        </div>
    </div>

</template>

<script setup>
import Swiper from 'swiper';
import { Navigation, Pagination } from 'swiper/modules';
// import Swiper and modules styles
import 'swiper/css';
import 'swiper/css/navigation';
import 'swiper/css/pagination';
// import Swiper from 'https://cdn.jsdelivr.net/npm/swiper@10/swiper-bundle.min.mjs'
</script>

<script>

    const swiper = new Swiper('.swiper', {
    // Optional parameters
    // direction: 'horizontal',
    modules: [Navigation, Pagination],
    loop: true,
    grabCursor:true,

    // If we need pagination
    pagination: {
        el: '.swiper-pagination',
        dynamicBullets: true,
        clickable: true,
    },

    // Navigation arrows
    navigation: {
        nextEl: '.swiper-button-next',
        prevEl: '.swiper-button-prev',
    },

    // And if we need scrollbar
    scrollbar: {
        el: '.swiper-scrollbar',
    },
    });
</script>
<style src ="./Home.css" scoped>@import "../../node_modules/swiper/css/swiper.css";</style>