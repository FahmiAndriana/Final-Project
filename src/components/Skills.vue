<template>
    <div>
        <section class="services section" id="services">
                <h2 class="section_title">Skills</h2>
                <span class="section_subtitle">My Technical level</span>

                <div class="services_container container grid">
                    <!--==================== PORFOLIO 1 ====================-->
                    <div class="services_content">
                        <div class="">
                            <i class="uil uil-brackets-curly skills_icon"></i>
                                
                                <div class="">
                                    <h1 class="skills_titles">Frontend Developer</h1>
                                    <span class="Skill_subtitle"></span>
                                </div>
                            
                        </div>

                        <span class="button button-flex button-small button-link services_button" @click="open()">
                            View More
                            <i class="uil uil-arrow-right button_icon"></i>
                        </span>

                        <div class="services_modal">
                            <div class="services_modal-content active-modal">
                                
                                <h4 class="services_modal-title">Frontend Developer</h4>
                                <i class="uil uil-times services_modal-close" @click="open()"></i>
                                <div class="skills_list grid">
                                    <div class="skills_data">
                                        <div class="skills_titles">
                                            <h3 class="skills_name">HTML</h3>
                                            <span class="skills_number">90%</span>
                                        </div>
                                        <div class="skills_bar">
                                            <span class="skills_percentage skills_html"></span>
                                        </div>
                                    </div>
                                    <div class="skills_data">
                                        <div class="skills_titles">
                                            <h3 class="skills_name">CSS</h3>
                                            <span class="skills_number">70%</span>
                                        </div>
                                        <div class="skills_bar">
                                            <span class="skills_percentage skills_css"></span>
                                        </div>
                                    </div>
                                    <div class="skills_data">
                                        <div class="skills_titles">
                                            <h3 class="skills_name">JavaScript</h3>
                                            <span class="skills_number">50%</span>
                                        </div>
                                        <div class="skills_bar">
                                            <span class="skills_percentage skills_js"></span>
                                        </div>
                                    </div>
                                    <div class="skills_data">
                                        <div class="skills_titles">
                                            <h3 class="skills_name">Vue</h3>
                                            <span class="skills_number">50%</span>
                                        </div>
                                        <div class="skills_bar">
                                            <span class="skills_percentage skills_vue"></span>
                                        </div>
                                    </div>
                                </div>

                            </div>
                        </div>
                    </div>

                    <!--==================== PORFOLIO 2 ====================-->
                    <div class="services_content">
                        <div class="">
                            <i class="uil uil-server-connection skills_icon"></i>
                                
                                <div class="">
                                    <h1 class="skills_titles">Backend Developer</h1>
                                    <span class="Skill_subtitle"></span>
                                    
                                </div>
                        </div>

                        <span class="button button-flex button-small button-link services_button" @click="open()">
                            View More
                            <i class="uil uil-arrow-right button_icon"></i>
                        </span>

                        <div class="services_modal">
                            <div class="services_modal-content">
                                <h4 class="services_modal-title">Fullstack Developer</h4>
                                <i class="uil uil-times services_modal-close" @click="open()"></i>
                                <div class="skills_list grid">
                                    <div class="skills_data">
                                        <div class="skills_titles">
                                            <h3 class="skills_name">Pyhton</h3>
                                            <span class="skills_number">60%</span>
                                        </div>
                                        <div class="skills_bar">
                                            <span class="skills_percentage skills_python"></span>
                                        </div>
                                    </div>
                                    <div class="skills_data">
                                        <div class="skills_titles">
                                            <h3 class="skills_name">Node JS</h3>
                                            <span class="skills_number">70%</span>
                                        </div>
                                        <div class="skills_bar">
                                            <span class="skills_percentage skills_node"></span>
                                        </div>
                                    </div>
                                    <div class="skills_data">
                                        <div class="skills_titles">
                                            <h3 class="skills_name">Jquery</h3>
                                            <span class="skills_number">60%</span>
                                        </div>
                                        <div class="skills_bar">
                                            <span class="skills_percentage skills_jquery"></span>
                                        </div>
                                    </div>
                                </div>
                                
                               
                                
                                                             
                            </div>
                        </div>
                    </div>

                    <!--==================== PORFOLIO 3 ====================-->
                    <div class="services_content">
                        <div class="">
                            <div class="skills_header">
                                <i class="uil uil-swatchbook skills_icon"></i><br>
                                
                                <div class="">
                                    <h1 class="skills_titles">Design</h1>
                                    <span class="Skill_subtitle"></span>
                                    
                                </div>
                                
                            </div>

                        </div>

                        <span class="button button-flex button-small button-link services_button" @click="open()">
                            View More
                            <i class="uil uil-arrow-right button_icon"></i>
                        </span>

                        <div class="services_modal">
                            <div class="services_modal-content">
                                <h4 class="services_modal-title">Design</h4>
                                <i class="uil uil-times services_modal-close" @click="open()"></i>
                                <div class="skills_list grid">
                                    <div class="skills_data">
                                        <div class="skills_titles">
                                            <h3 class="skills_name">Figma</h3>
                                            <span class="skills_number">60%</span>
                                        </div>
                                        <div class="skills_bar">
                                            <span class="skills_percentage skills_figma"></span>
                                        </div>
                                    </div>
                                    <div class="skills_data">
                                        <div class="skills_titles">
                                            <h3 class="skills_name">Photoshop</h3>
                                            <span class="skills_number">70%</span>
                                        </div>
                                        <div class="skills_bar">
                                            <span class="skills_percentage skills_photoshop"></span>
                                        </div>
                                    </div>
                                    <div class="skills_data">
                                        <div class="skills_titles">
                                            <h3 class="skills_name">Canva</h3>
                                            <span class="skills_number">70%</span>
                                        </div>
                                        <div class="skills_bar">
                                            <span class="skills_percentage skills_canva"></span>
                                        </div>
                                    </div>
                                    <div class="skills_data">
                                        <div class="skills_titles">
                                            <h3 class="skills_name">Corel Draw</h3>
                                            <span class="skills_number">60%</span>
                                        </div>
                                        <div class="skills_bar">
                                            <span class="skills_percentage skills_coreldraw"></span>
                                        </div>
                                    </div>
                                </div>
                                
                                                             
                            </div>
                        </div>
                    </div>


                </div>
                

            </section>
    </div>
</template>

<style>

</style>

<script>
export default {
    data(){
        return{

        }
    },
    methods: {
        open() {
           const modalViews = document.querySelectorAll('.services_modal'),
                  modalBtns = document.querySelectorAll('.services_button'),
                  modalCloses = document.querySelectorAll('.services_modal-close')

            let modal = function(modalClick){
                modalViews[modalClick].classList.add('active-modal')
                }
                modalBtns.forEach((modalBtn, i) => {
                modalBtn.addEventListener('click', () => {
                modal(i)
                })
            })

                modalCloses.forEach((modalClose) => {
                modalClose.addEventListener('click', () => {
                modalViews.forEach((modalView) =>{
                modalView.classList.remove('active-modal')
                        })
                    })
                })
           
        }
    }
}
</script>