<script >
    export default{
        data() {
            return {
                navBar: [
                    {
                        link :'CHARACTERS',
                        href : '#'
                    },
                    {
                        link :'COMICS',
                        href : '#'
                    },
                    {
                        link :'MOVIES',
                        href : '#'
                    },
                    {
                        link :'TV',
                        href : '#'
                    },
                    {
                        link :'GAMES',
                        href : '#'
                    },
                    {
                        link :'COLLECTIBLES',
                        href : '#'
                    },
                    {
                        link :'VIDEOS',
                        href : '#'
                    },
                    {
                        link :'FANS',
                        href : '#'
                    },
                    {
                        link :'NEWS',
                        href : '#'
                    },
                    {
                        link :'SHOP',
                        href : '#'
                    },
                    

                ],
            };
        },
        methods: {

        }
    }
</script>

<template>
    <header>
        <div class="container">
            <div class="nav-bar">
            <section>
                <img src="../../public/img/dc-logo.png" alt="logodc">
            </section>
            <section>
                <ul>
                    <li v-for="index in navBar" >
                        <a href="index.href">
                            {{ index.link }}
                        </a>
                    </li>
                </ul>
            </section>
        </div>
        </div>
        
    </header>
</template>

<style lang="scss" scoped>
@use "../assets/scss/header.scss" as *;
</style>
