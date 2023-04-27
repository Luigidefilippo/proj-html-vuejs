<script>
import mainNavbar from './mainComponents/mainNavbar.vue';
import mainSection1 from './mainComponents/mainSection1.vue';

export default {
    components: {
        mainNavbar,
        mainSection1,
    }
}

</script>

<template>
<div class="containerS1">
        <div class="container">
            <mainNavbar class="top-right" />
            <mainSection1 class="center" />
        </div>
    </div>

</template>

<style lang="scss">
.containerS1 {
    background-color: red;

    .top-right{
        background-color: yellow;
        
        .center{
            background-color: brown;
        }
    }
}
</style>