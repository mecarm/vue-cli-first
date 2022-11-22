<template>

    <div>
        <h1>Jumbotron</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Architecto doloremque accusamus reprehenderit ipsa molestias doloribus ipsum quos vitae quae, perspiciatis quaerat alias dolorem nostrum atque dignissimos praesentium nemo modi quas?</p>
    </div>
    
</template>

<script>
export default {
  name: 'HeroTron',
}
</script>

<style scoped lang="scss">
div {
    background-image: url('https://images.unsplash.com/photo-1669040501450-982e2c643358?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2944&q=80');
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    color: white;
    text-align: left;
    height: 300px;
    line-height: 30px;
    width: 80%;
    margin: auto;
    padding: 15px;
    
}
p{
    width: 50%;
}
</style>