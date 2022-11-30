<template>
    <div>
        <header>
            <h1>Welcome to my VueJS page!</h1>
            <h2>Keep reading for some exciting things about VueJS</h2>
        </header>
    </div>
</template>

<script>
export default {
    name: "HeaderComponent"
}
</script>

<style scoped>
header {
    background-color: floralwhite;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    height: 15vh;
}

h1 {
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    text-shadow: 1px 1px 2px grey, 0 0 1em lightgray, 0 0 0.2em royalblue;
    padding-top: 0.8em;
    font-size: 3em;
}

h2 {
    font-size: 2.5em;
}
</style>