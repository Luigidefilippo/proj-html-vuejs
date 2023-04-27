<script>
import mainNavbar from './mainComponents/mainNavbar.vue';
import mainSection1 from './mainComponents/mainSection1.vue';
import mainSection2 from './mainComponents/mainSection2.vue';
import mainSection3 from './mainComponents/mainSection3.vue';

export default {
    components: {
        mainNavbar,
        mainSection1,
        mainSection2,
        mainSection3


    }
}

</script>

<template>
<div class="containerS1">
        <div class="container">
            <mainNavbar class="top-right" />
            <mainSection1 />
        </div>
    </div>
    <mainSection2/>
    <mainSection3/>

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