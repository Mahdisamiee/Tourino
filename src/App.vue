<template>
  <v-app>
    <navbar v-if="false"/>
    <navbar2 v-if="true"/>
    <v-content>
      <!-- <router-view></router-view> -->
    </v-content>
  </v-app>
</template>
<script>
import navbar from './components/navbar.vue';
import navbar2 from './components/navbar2.vue';

export default {
  components:{
    navbar,
    navbar2
  },
  data(){
    return {

    }
  }

}
</script>
<style>

</style>
