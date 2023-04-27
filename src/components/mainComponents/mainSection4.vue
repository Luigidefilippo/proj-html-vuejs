<script>
import cards4 from './cards/cards4.vue';

export default {
    components: {
        cards4,
    }
}

</script>

<template>
    <section class="s4">
        <div class="container">
            <h6>WE ARE A PROFESSIONAL</h6>
            <h4>Full-Service Solution</h4>
            <div class="cards">
                <cards4 />
                <cards4 />
                <cards4 />
            </div>
        </div>
    </section>
</template>

<style lang="scss">
@use '../style/partials/colors' as*;


.s4 {
    text-align: center;
    margin: 100px;
    .container {
        .cards {
            margin-top: 100px;
            display: flex;
            justify-content: center;
            gap: 100px;
        }
    }
}

</style>