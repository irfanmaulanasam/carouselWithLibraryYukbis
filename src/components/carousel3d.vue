<template>
    <div id="3dcarousel">
        <carousel-3d>
            <div v-for="(item,index) in 6" :key="index">
                <Slide :index="index">
                <img :src="'https://picsum.photos/45'+index+'/300/?random'"/>
                </Slide>
            </div>
        </carousel-3d>
    </div>
</template>
<script>
import { Carousel3d, Slide } from 'vue-carousel-3d';
export default {
    name:'3dcarousel',
  components: {
    Carousel3d,
    Slide
  },
}
</script>
