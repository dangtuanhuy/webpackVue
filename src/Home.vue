<template><diV>
<app-server-status v-for="Server in 5" :key="Server"></app-server-status>
</div>
</template>

<script>
import ServerStatus from './components/Server/ServerStatus.vue'
export default {
 components:{
     'app-server-status': ServerStatus
 }
};
</script>

<style>
</style>
