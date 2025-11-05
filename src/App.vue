<template>
    <Translation />
    <!-- <Enlarge /> -->
    <!--<Brush /> -->
</template>
<script>
import Enlarge from "./enlarge";
import Translation from "./translation";
import Brush from "./brush";
export default {
    components: {
        Translation,
        Enlarge,
        Brush
    },
    data(){
        return {}
    },
}
</script>
<style>
html, body, #app {
    margin: 0;
    padding: 0;
    height: 100%;
}
.app-container{
    padding: 20px;
}
</style>