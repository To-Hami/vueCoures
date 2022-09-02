<template>
    {{name}}
    {{age}}
    <br>
    {{hopiets[0]}}
    <br>

<!----------------------------------------------    directive in vue -->
    <h2 v-text="name"></h2>
    <br>


    <div v-if="hopiets.length > 5 ">
        {{hopiets}}
    </div>

    <div v-show="hopiets.length > 0 ">
        {{hopiets}}
    </div>






</template>


<script>
export  default{
    data() {

        return{
            name:'toham',
            age :28,
            hopiets : ['play','programing','drawing']
        }

    }
}

</script>


<style>

</style>