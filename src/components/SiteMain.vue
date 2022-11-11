<script>
    import Comics from "../dc-comics"
    export default{
        data(){
            return{
                comics: Comics,
                path: "../img/"
            }
        },
        mounted() {
            console.log(this.comics);
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
        <div class="container-fluid titles p-4">
            <div class="current-series row">
                <div v-for="(comic,i) in comics" class="col-2 p-4">
                    <img :src="comic.thumb" :alt="comic.series">
                    <p>{{comic.series}}</p>
                </div>
            </div>
        </div>
    </div>
</template>

