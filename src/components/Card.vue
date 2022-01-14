<template>
    <div class="containerCard">
        <div class="image">
            <img :src="image" alt="">
        </div>
        <div class="title">
            <h3>{{title}}</h3>
        </div>
    </div>
</template>

<script>
export default {
    name: "Card",
    props: [
        "image",
        "title",
    ],
    data(){
        return{}
    }
}
</script>

<style lang="scss" scope>
    .containerCard {
        width: 150px;
        .image{
            width: 150px;
            height: 150px;
            overflow: hidden;
            img{
                width: 100%;
            }
        }
        .title{
            h3{
                color: white;
                text-transform: uppercase;
                font-size: 0.7em;
                padding-top: 1.5em;
            }
        }
    }
</style>