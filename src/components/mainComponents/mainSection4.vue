<script>
import cardS4 from './cards/cardS4.vue'
export default {
    data() {
        return {
            cardElements: [
                {
                    "image": "../../../public/avada-movers-serviceonephoto-final-600x383.jpg",
                    "title": "Two Man Teams",
                    "description": "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac consectetur augue. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.",
                    "buttonText": "read more"
                },
                {
                    "image": "../../../public/avada-movers-servicetwophoto-final-600x383.jpg",
                    "title": "We Do All The Lifting",
                    "description": "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac consectetur augue. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.",
                    "buttonText": "read more"
                },
                {
                    "image": "../../../public/avada-movers-servicethreephoto-final-600x383.jpg",
                    "title": "Coast To Coast",
                    "description": "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac consectetur augue. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.",
                    "buttonText": "read more"
                },
            ]
        }
    },
    components: {
        cardS4,
    }
}
</script>
<template>
    <section class="s4">
        <div class="container">
            <h6>we are a professional</h6>
            <h4>Full-Service Solution</h4>
            <ul class="cards">
                <cardS4 v-for="(element, i) in cardElements" :key="i" :cardS4Elements="element" />
            </ul>
        </div>
    </section>
</template>

<style lang="scss">
@use '../style/partials/colors' as*;

.s4 {
    height: 1100px;
    text-align: center;
    padding: 0 30px;
    .container {
        height: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 25px;
        h4 {
            margin-bottom: 25px;
        }
        .cards {
            display: flex;
            justify-content: center;
            gap: 100px;
        }
    }
}
</style>