<template>
      <div>
        <div>
            <img :src="image" class="img-fluid w-100 " :alt="series">
        </div>
        <div class="card-body text-start  my-2">
            <h5 class="text-white">{{ series }}</h5>
        </div>
    </div>
    <div class="d-flex align-items-end justify-content-between">
        <span class="text-white ">{{ price }}</span>
      
    </div>
</template>

<script>
    export default {
        name:'CardComponent',
        props: [
            'image',
            'series',
            'price',
            'link',
        ],
        
    }
</script>

<style lang="scss" scoped>

</style>