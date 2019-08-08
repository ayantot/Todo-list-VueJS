<template>

<div>
  <carousel>
    <carousel-slide>
      Salut les gens
    </carousel-slide>
    <carousel-slide>
      Au revoir les gens
    </carousel-slide>
  </carousel>
  <Todos></Todos>
</div>

</template>

<script>
import Todos from './components/Todos'
import Carousel from './components/carousel/Carousel'
import CarouselSlide from './components/carousel/CarouselSlide'

export default {
  components: {
    Todos,
    Carousel,
    CarouselSlide
  }
}
</script>

<style>

</style>
