<script >
    export default{
        data() {
            return {
                
            };
        },
        props:{
            image:String,
            name:String,
        }
    }
</script>

<template>
    <div class="single-product">
        <div>
            <img :src="image" :alt="name">
        </div>
        <h2>
            {{ name }}
        </h2>

    </div>
</template>

<style lang="scss">

.single-product{
    width: calc((100% - 40px) / 6);
    height: 200px;
    padding: 20px;
    margin-top: 20px;
    > div{
        height: 150px;
        width: 150px;
        overflow: hidden;
        

    }
    > h2{
        color: white;
        margin-top: 10px;
        font-size: 1rem;
    }
}
</style>

