<template>
    <v-app-bar app flat class="white--text primary" >
        <v-toolbar-title class="display-1 mx-5">Tourino</v-toolbar-title>
        <v-spacer></v-spacer>
        <!-- <div width="50px" height="50px">
            <img id="img" src="../assets/a.png" alt="">
        </div> -->
        <v-spacer></v-spacer>

        <v-layout
                align-center
                style="max-width: 350px"
            >
                <v-text-field
                    placeholder="Search..."
                    single-line
                    rounded
                    color="grey darken-2"
                    background-color="white"
                    hide-details
                ></v-text-field>
                <v-btn id="search-btn" small flat icon class="ml-4">
                    <v-icon  class="white--text" medium>mdi-magnify</v-icon>
                </v-btn>
            </v-layout>

        <!-- Singin and Signup -->
        <registering/>

    </v-app-bar>
</template>

<script>
import registering from './registering.vue';

export default {
    components:{
        registering
    },
    
}
</script>

<style scoped>
#img{
    width: 250px;
    height: 60px;
}
#search-btn:active{
    color: yellow;
}
</style>