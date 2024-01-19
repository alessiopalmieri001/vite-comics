<script >
    export default{
        data() {
            return {
                Object:[
                    {
                        immagine: '../../public/img/buy-comics-digital-comics.png',
                        name : 'DIGITAL COMICS'
                    },
                    {
                        immagine: '../../public/img/buy-comics-merchandise.png',
                        name : 'DC MERCHANDISE'
                    },
                    {
                        immagine: '../../public/img/buy-comics-subscriptions.png',
                        name : 'SUBSCRIPTION'
                    },
                    {
                        immagine: '../../public/img/buy-comics-shop-locator.png',
                        name : 'COMINC SHOP LOCATOR'
                    },
                    {
                        immagine: '../../public/img/buy-dc-power-visa.svg',
                        name : 'DC POWER VISA'
                    },

                ],
            };
        },
        methods: {

        }
    }
</script>

<template>
    <main>
        <section class="my-main">
            <div class="container">
                <p>
                    Content
                </p>
            </div>
        </section>
        <section class="my-main-2">
            <div class="container">
                <div class="row">
                    <div class="col-1-5" v-for="elem in Object">
                        <div>
                            <img :src="elem.immagine" :alt="elem.name">
                        </div>
                        <div>
                            {{ elem.name }}
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
    </main>
</template>

<style lang="scss" scoped>
@use "../assets/scss/main.scss" as *;
</style>

