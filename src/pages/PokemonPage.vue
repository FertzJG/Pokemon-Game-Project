<script lang="ts">

import PokemonOptions from '@/components/PokemonOptions.vue'
import PokemonPicture from '@/components/PokemonPicture.vue'
import getPokemonOptions from '@/helpers/getPokemonOptions'

console.log(getPokemonOptions())

export default {
        components: { PokemonOptions, PokemonPicture }
    }
</script>


<template>
    <h1>¿Quién es este pokemon?</h1>

    <PokemonPicture :pokemonId="25" :showPokemon="false" />
    <PokemonOptions />
</template>


<style>

</style>