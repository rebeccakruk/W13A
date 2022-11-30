<template>
    <div>

        <h2>What are frameworks?</h2>
        <p>Frameworks were made to make code less fragile, and more universally written (and readable!). They are aimed
            to speed up development.</p>
        <h2> Frameworks are good:</h2>
        <li>VueJS forces everyone to write in the same style of code.</li>
        <li>The code is written in component based architecture.</li>
        <h2>There are a couple of drawbacks, but not insurmountable challenges:</h2>
        <li>Frameworks have a steeper learning curve and you have to know what you're doing to be proficient with them.
        </li>
        <li>Frameworks have rigid structures, so you must follow the rules of Vue or it will not work!
        </li>
    </div>
</template>

<script>
export default {
    name: "BodyComponent"
}
</script>

<style scoped>
div {
    background-color: lightgrey;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    height: 50vh;
    padding-top: 2em;
}

h2 {
    font-size: 2.5em;
}

p,
li {
    font-size: 2em;
}
</style>