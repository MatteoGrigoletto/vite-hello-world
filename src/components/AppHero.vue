<script>
// script vue.js
export default{
    data(){
        return{
            // proppieta data del singolo componente
            title:'Jumbotron',
            text:'che bello vite!!',
        }
    }
}
</script>

<template>
<!-- creazione template html -->
<div class="container">
    <h1>{{title}}</h1>
    <p>{{text}}</p>
</div>
</template>
<style scoped>
/* aggiunta stile css */
.container{
    background-color: rgb(122, 121, 121, 0.3);
    height: 200px;
    width: 100%;
}
</style>