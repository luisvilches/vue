<script>
import Carousel from '../components/Slider_home';
import Retos from "../components/Retos"
export default {
    name:"Home",
    data(){
        return{
            items:[]
        }
    },
    components:{
        Carousel,
        Retos
    },
    created(){
        this.items = [
            {
                src:"https://s3.envato.com/files/231607278/720x300_Pop_Under.jpg",
                alt:"image-1"
            },
            {
                src:"https://cdn2.f-cdn.com/contestentries/76532/4132623/536cac6b051c9_thumb900.jpg",
                alt:"image-2"
            }
        ]
    }
}
</script>

<template>
    <main>
        <carousel :items="items"></carousel>
        <br>
        <Retos />
    </main>
</template>

<style scoped>
    @import url("https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.css");
    main{
        margin-top: 80px;
    }
</style>
