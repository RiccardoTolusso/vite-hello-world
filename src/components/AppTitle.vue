<script>
export default{
    name:"HelloWorld",
    data(){
        return {
            title: 'La mia prima app con Vite!',
        }
    }
}
</script>
<template>
    <div>
        <h1>{{ title }}</h1>
    </div>
</template>

<style scoped>
div{
    width: 100vw;
    height: 100vh;
    background-color: rgba(0, 0, 0, 0.292);
}

h1{
    color: white;
    text-align: center;
    position: relative;
    top: 50%;
    transform: translateY(-50%);
}
</style>