<script>
import mainNavbar from './mainComponents/mainNavbar.vue';
import mainSection1 from './mainComponents/mainSection1.vue';
import mainSection2 from './mainComponents/mainSection2.vue';
import mainSection3 from './mainComponents/mainSection3.vue';
import mainSection4 from './mainComponents/mainSection4.vue';

export default {
    components: {
        mainNavbar,
        mainSection1,
        mainSection2,
        mainSection3,
        mainSection4


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
    <a href="#">
        <mainSection2/>
    </a>
    <mainSection3/>
    <mainSection4/>

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