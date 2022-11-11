<script>
    import Comics from "../dc-comics"
    export default{
        data(){
            return{
                comics: Comics,
                path: "../img/"
            }
        }
    }
</script>

<template>
    <div id="main">
        <div class="jumbotron">
            <h3 class="current-series-ad p-2 text-white">
                Current Series
            </h3>
        </div>

        <div class="current-series">
            <div v-for="(comic,i) in comics">
                <h1>{{comic.price}}</h1>
                <h1>{{comic}}</h1>
            </div>
        </div>
    </div>
</template>

