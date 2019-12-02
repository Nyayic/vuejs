<template>
    
    <div class="container" >
        <AppHeader/>
        <br><br>
        <div class="container">
            <div class="row">
                <div class="col-md-3">
            <!--App SideBar goes here-->
                    <h4>SideBar</h4>
                    <AppSideBar />
                </div>
                
            <!--App Intro goes here-->
            <AppIntro />

                <div class="col-md-3">
                    <h4>Welcome to Top Model Third Runner Up</h4>
                    <img class="image-responsive"  width="100%" src="../assets/image_3.jpg">
                    <p>Welcome to my website 3</p>
                    <button class="btn btn-outline-info btn-block">Model Three</button>
                </div>
                
            </div> 
        </div>
        <!--footer goes here-->
                <AppFooter />
            
    </div>
</template>

<script>
import AppHeader from './AppHeader'
import AppSideBar from './AppSideBar'
import AppFooter from './AppFooter'
import AppIntro from './AppIntro'

export default {
    name:'AppBodyStructure',
    components:{
        AppHeader, 
        AppSideBar,
        AppFooter,
        AppIntro
    
    }
}
</script>