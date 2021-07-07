<template>
   <header>
       <div v-for="header in header" key="header.image.text">
           :img="header.image"
           :Text="header.text"
       </div>
   </header>
</template>

<script>
export default {
    data() {
        return{
            header: [
                {
                require('../assets/dc-logo.png'),
                  image:"../assets/dc-logo.png",
                  text: "Characters comics movies tv games collectibles videos fans news shop" 
     
                }
            ]
        }
    }
}
</script>

<style>

</style>