<template>
    <div className="card">
        <img alt="character image" src="">
        <h3>character name</h3>
        <p>description</p>
    </div>
</template>

<script>

export default {
    name: 'HelloWorld'
}
</script>

<style scoped>
.card {
    width: 12rem;
    height: 18rem;
    background-color: cornflowerblue;
    /* display: flex; */
    /* flex-direction: column; */
    /* align-items: center; */
}

img {
    max-width: 12rem;
    max-height: 12rem;
}

p {
    color: black;
}
</style>
