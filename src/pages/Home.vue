<template>
<div>
    <Navbar/>
    <Heroimg :info="dataAbout"/>
    <About :info="dataAbout"/>
    <Skills/>
    <Qualification :info="dataAbout"/>
    <Portfolio/>
    <Contactme/>
    <Footer/>
    <ScrollTop/>
    
</div>
</template>

<style>
@import '../assets/css/styles.css';

</style>

<script>
import axios from "axios";
import Navbar from "../components/Navbar.vue";
import Heroimg from "../components/Heroimg.vue";
import About from "../components/About.vue";
import Skills from "../components/Skills.vue";
import Qualification from "../components/Qualification.vue";
import Portfolio from "../components/Portfolio.vue";
import Contactme from "../components/Contactme.vue";
import Footer from "../components/Footer.vue";
import ScrollTop from "../components/ScrollTop.vue";


export default {
    created(){
        this.getAPIusers();
    },
    data: function(){
        return{
          
           dataAbout: []
        };
    },
    methods: {
        async getAPIusers(){
            try{
                const response = await axios.get('http://localhost:3000/users');
                const { data } = response;
                if (data.length){
                    this.dataAbout = data;
                }
            } catch (err){
                console.error(err);
            }
        }
    },
    components:{
        Navbar,
        Heroimg,
        About,
        Skills,
        Qualification,
        Portfolio,
        Contactme,
        Footer,
        ScrollTop,
        
        
    }
}


</script>