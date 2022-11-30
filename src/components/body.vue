<template>
    <div>

        <aside>Evan You: "I am an independent software developer and the creator of the open source JavaScript framework
            Vue.js. Most of my work
            is open source and publicly available on GitHub. You can follow me on Twitter

            where I mostly tweet about Vue and frontend technologies.

            Outside of programming and helping my wife take care of our two kids, I enjoy video games, karaoke, sushi
            and collecting
            watches."</aside>
        <h2>What are frameworks?</h2>
        <p>Frameworks were made to make code less fragile, and more universally written (and readable!). They are aimed
            to speed up development.</p>
        <aside>Which big companies use VueJS?
            <ol>Facebook</ol>
            <ol>Netflix</ol>
            <ol>Nintendo</ol>
            <ol>Adobe</ol>
            <ol>Xiaomi</ol>
            <ol>The Motley Fool</ol>
            <ol>Trivago</ol>
            <ol>Grammarly</ol>
            ... to name a few!
        </aside>
        <h2> Frameworks are good:</h2>
        <li>VueJS forces everyone to write in the same style of code.</li>
        <li>The code is written in component based architecture.</li>
        <h2>There are a couple of drawbacks, but not insurmountable challenges:</h2>
        <li>Frameworks have a steeper learning curve and you have to know what you're doing to be proficient with
            them.
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

ol {
    font-weight: 800;
}

p,
li {
    font-size: 2em;
}

aside {
    display: block;
    float: right;
    width: 30%;
    padding-left: 15px;
    font-style: italic;
    background-color: darkgrey;
}

aside,
li {
    font-style: italic;
}
</style>