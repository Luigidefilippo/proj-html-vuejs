<script>
export default {
    props: {
        cardS4Elements: {
            type: Object,
            required: true
        },
    }
}
</script>

<template>
    <li class="photoS4">
        <img :src="cardS4Elements.image" alt="">
        <div class="cardText">
            <h5>{{ cardS4Elements.title }}</h5>
            <p>{{ cardS4Elements.description }}</p>
            <a href="#" class="button">{{ cardS4Elements.buttonText }}</a>
        </div>
    </li>
</template>

<style lang="scss">
@use '../../style/partials/colors' as*;

li {
    padding: 20px;
    .cardText {
        background-color: $sectionBg;
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 25px;
        line-height: 30px;
        padding: 30px 20px;
    }
}
</style>