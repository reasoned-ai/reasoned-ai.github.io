<template>
    <div class="header">
        <nuxt-link to="/" class="logo">
            <img src="@/assets/images/logo.png">
            &nbsp;&nbsp;&nbsp;&nbsp; Reasoned AI
        </nuxt-link>
        <nav>
            <ul>
                <li><nuxt-link to="/">Home</nuxt-link></li>
                <li><a href="https://medium.com/reasoned-ai">Blog</a></li>
                <li><a href="https://docs.google.com/document/d/1d8IH734g_bwnHXLvTe24OXdm97ioIqnUuMTwmAbtUSM/edit?usp=sharing">Vision</a></li>
                <li><a href="https://reasoned.us20.list-manage.com/subscribe/post?u=cf65772f893ac97470fb3ae81&id=ec94e66734">Demo</a></li>
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
        margin-left: 25%;
        margin-right: 30%;
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
        color: #ff756d;
    }
</style>
