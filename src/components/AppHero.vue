<script>
export default{
    data(){
        return{
            url: "https://m.media-amazon.com/images/I/61e8NZAUkgL._UF1000,1000_QL80_.jpg",
        }
    }
}
</script>
<template>
        <img :src="url" alt="">
</template>

<style>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

img{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    z-index: -1;
    height: 100vh;
    width: 100vw;
    object-fit: cover;
} 
</style>