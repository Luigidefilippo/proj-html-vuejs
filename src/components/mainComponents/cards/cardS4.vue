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

.photoS4{
    background-color: $sectionBg;
}

li {
    padding: 20px;
    img {
        margin-bottom: 20px;
    }
    .cardText {;
        display: flex;
        flex-direction: column;
        align-items: center;
        line-height: 30px;
    }
}
</style>