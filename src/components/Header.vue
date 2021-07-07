<template>
    <div>
        <img :src="img" />
        <p>{{Text}}</p>
    </div>
</template>

<script>
export default {
    props:{
        img: String,
        Text: String
    }
}
</script>

<style lang ="scss" scoped>

Header{
    text-align: center;
    float: left;
    ul {
        list-style: none;
        text-decoration: none;
        li {
            margin-right: 10px;
            display: inline-block;
            text-transform: uppercase;
           
            
            
        }
    }
}

</style>