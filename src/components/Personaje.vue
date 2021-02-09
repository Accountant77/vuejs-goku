<template>
    <div>
        <img :src="imagen">
        <p>Fuerza actual: {{fuerzaActual}}</p>
        <button @click="cabrear">Cabrear personaje</button>
    </div>
</template>

<script>
import {ref} from 'vue'
export default {
    name: 'Personaje',
    //COMPOSITION API
    /*props: {
        fuerza:{
            type: Number,
            default: 10,
            required: true
        },
        imagen:{
            type: String,
            default: 'goku.png'
        }
    },
    setup(props){
        let fuerzaActual=ref(props.fuerza)
        let imgPersonaje= '/images/' + props.imagen
        const cabrear =()=>{
            fuerzaActual.value++
        }
        return {
            fuerzaActual,
            imagen:imgPersonaje,
            cabrear
        }
    }*/

    //OPTIONS API
    props: {

    },
    methods:{

    },
    data(){

    }
}
</script>

<style lang="scss" scoped>

</style>