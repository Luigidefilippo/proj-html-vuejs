<!-- TESTIMONIALS -->
<script>
export default {
    props: {
        cardS6Elements: {
            type: Object,
            required: true
        },
    }
}
</script>


<template>
    <li>
        <img class="testimonials" :src="cardS6Elements.image" alt="">
        <h5>{{ cardS6Elements.title }}</h5>
        <p>{{ cardS6Elements.description }}</p>
    </li>


</template>

<style lang="scss">
@use '../../style/partials/colors' as*;

li {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;
    gap: 40px;
    line-height: 30px;
    text-align: center;
    color: $smallTitle;
    .testimonials{
        width: 150px;
        border-radius: 999px;
    }
}

</style>