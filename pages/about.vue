<template>
    <div>
        <h2>About</h2>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Delectus laboriosam magni fugiat, cupiditate totam velit illo nesciunt asperiores voluptates! Velit!</p>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Delectus laboriosam magni fugiat, cupiditate totam velit illo nesciunt asperiores voluptates! Velit!</p>
        <div> {{ data }} </div>
    </div>  
</template>

<script setup>
    const { data } = await useFetch('/api/ninja?name=mario')

</script>

<style scoped>
h2{
    margin-bottom: 20px;
    font-size: 36px;
}

p{
    margin: 20px 0;
}

</style>