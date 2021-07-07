<template>
   <header>
       <div>
           <div class="logo">
               <img :src="logo">
               </div>
           <Header :key="index" v-for="(link,index) in links"            
           :Text="link.text"/>
       </div>
   </header>
</template>

<script>

import Header from './Header.vue'

export default {
    components:{
            Header
    },
    data() {
        return{
            logo:require("../assets/dc-logo.png"),
            links: [
                {               
                  
                  text: "Characters" 
     
                },
                {                    
                    text:"Comics"    
                },
                {                    
                    text:"movies"    
                },
                {                    
                    text:"tv"    
                },
                {                    
                    text:"games"    
                },
                {                    
                    text:"collectibles"    
                },
                {                    
                    text:"videos"    
                },
                {                    
                    text:"fans"    
                },
                 {                    
                    text:"news"    
                },
                 {                    
                    text:"shop"    
                },
            ]
        }
    }
}
</script>

<style>

</style>