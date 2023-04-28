<script>
export default {

}
</script>

<template>
    <section class="bannerS1">
            <h6>MOVING WITHOUT THE HASSLE</h6>
            <h3>WE MAKE IT SIMPLE</h3>
            <h6>PROFESSIONAL SERVICE WITH QUALITY AND COSTUMER SATISFACTION</h6>
    </section>

</template>

<style lang="scss">
@use '../style/partials/colors' as*;

.bannerS1{
    text-align: center;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 35px;

    h6 {
        color: $smallTitle;
        font-size: 16px;
        text-transform: uppercase;
    }
    h3 {
        color: $title;
        font-size: 58px;
        text-transform: uppercase;
    }
}
</style>