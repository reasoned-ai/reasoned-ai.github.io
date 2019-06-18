<template>
    <div class="header">
        <nuxt-link to="/" class="logo">
            <img src="@/assets/images/logo.png">
            &nbsp;&nbsp;&nbsp;&nbsp; Reasoned AI
        </nuxt-link>
        <nav>
            <ul>
                <li><nuxt-link to="/">Home</nuxt-link></li>
                <li><a href="https://blog.reasoned.ai">Blog</a></li>
                <li><nuxt-link to="/whitepaper">About</nuxt-link></li>
                <li><nuxt-link to="/demo">Demo</nuxt-link></li>
                <li><nuxt-link to="/signup">Join</nuxt-link></li>
            </ul>
        </nav>
    </div>    
</template>

<script>
export default {

}
</script>

<style>
    .header {
        opacity: 1;
        display: grid;
        grid-template-columns: auto auto;
        column-gap: 3em;
        margin-left: 15%;
        margin-right: 20%;
        font-weight: bold;
    }

    .logo, li a {
        padding: 1em 2em;
        display: block;
        text-transform: uppercase;
        text-decoration: none;
        font-weight: bold;
        color: rgb(210,210,210);
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
        .header {
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
