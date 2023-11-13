<template>
    <div :class="$style.child">
        <h2>Child3</h2>
    </div>
</template>

<script>
    export default {
        name:"Child3"
    }
</script>

<style module>
.child{background:purple; border: solid 1px black; margin : 1.5em; padding: 1.0em;}
</style>