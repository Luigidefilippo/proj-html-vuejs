<script>
import mainNavbar from './mainComponents/mainNavbar.vue';
import mainSection1 from './mainComponents/mainSection1.vue';
import mainSection2 from './mainComponents/mainSection2.vue';
import mainSection3 from './mainComponents/mainSection3.vue';
import mainSection4 from './mainComponents/mainSection4.vue';
import mainSection5 from './mainComponents/mainSection5.vue';
import mainSection6 from './mainComponents/mainSection6.vue';
import mainSection7 from './mainComponents/mainSection7.vue';

export default {
    components: {
        mainNavbar,
        mainSection1,
        mainSection2,
        mainSection3,
        mainSection4,
        mainSection5,
        mainSection6,
        mainSection7


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
    <mainSection5/>
    <mainSection6/>
    <mainSection7/>
    
</template>

<style lang="scss">
@use './style/partials/colors' as*;
@use './style/partials/globalReset' as*;

.containerS1 {
    background-image: url(../../public/avada-movers-homeherobackground-final.jpg);
    background-position: center bottom;
    background-size: cover;
    height: 690px;
    padding: 0 30px;
    .container {
        height: 100%;
        position: relative;
        display: flex;
        align-items: center;
        justify-content: center;
        .top-right {
            position: absolute;
            top: 0;
            right: 0;
        }
    }
}

</style>