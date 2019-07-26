<template>
    <carousel :autoplay="true" :nav="true">
        <div v-for="(item,index) in 25" :key="index">
            <Slide :index="index">
                <img :src="'https://picsum.photos/45'+index+'/300/?random'"/>
            </Slide>
        </div>
    </carousel>
</template>
<script>
import carousel from 'vue-owl-carousel'

export default {
    components: { carousel },
}

</script>