<template>
  <div class="about">
    <h1>This is an about page</h1>
    <Personaje fuerza="3" />
  </div>
</template>


<script>
import Personaje from '@/components/Personaje.vue'
export default {
  //name: 'otraCosa',
  components:{
    Personaje
  }
}
</script>
