<template>
    <div class="card">
        <img :src="image" alt="">
        <h3>{{title}}</h3>
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

<style>

</style>