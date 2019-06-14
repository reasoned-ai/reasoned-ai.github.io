<template>
    <header>
        <nuxt-link to="/" class="logo">
            <img src="@/assets/images/logo.png">
            &nbsp;&nbsp;&nbsp;&nbsp; Reasoned AI
        </nuxt-link>
        <nav>
            <ul>
                <li><nuxt-link to="/">Home</nuxt-link></li>
                <li><a href="https://blog.reasoned.ai">Blog</a></li>
                <li><nuxt-link to="/about">About</nuxt-link></li>
                <li><nuxt-link to="/demo">Demo</nuxt-link></li>
                <li><nuxt-link to="/login">Join</nuxt-link></li>
            </ul>
        </nav>
    </header>    
</template>

<script>
export default {

}
</script>

<style>
    header {
        background: rgb(251, 251, 251);
        display:grid;
        grid-template-columns: auto auto auto;
        column-gap: 3em;
        margin-left: 10%;
        margin-right: 10%;
        font-weight: bold;
    }

    .logo, li a {
        padding: 1em 2em;
        display: block;
        text-transform: uppercase;
        text-decoration: none;
        font-weight: bold;
        color: black;
        font-size: 1em;
    }

    nav {
        justify-self: right;
    }
    ul {
        list-style-type: none;
        margin-top:2em;
    }
    li {
        display: inline;
    }
    @media (max-width:600px) {
        header {
            display: none;
        }
    }

    li a {
        padding: 1em 1em;
        display: inline-block;
        text-transform: capitalize;
        background: rgba(0,0,0,0);
    }
    li a:hover {
        padding: 1em 1em;
        display: inline-block;
        color: #03d6a5;
    }
</style>
