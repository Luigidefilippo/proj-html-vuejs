<script>
export default{

}
</script>

<template>
 <section class="s5">
        <div class="container">
            <div class="card">
                <div class="cardText">
                    <h6>WE REMOVE THE HEADACHE FROM MOVING</h6>
                    <h4>Move With Ease</h4>
                    <p>With our super simple service we can take you from getting a quote, right through to being in your new home with all of your belongings securely packed and safely delivered, even in the rooms of your choice.
                    </p>
                    <a href="#" class="button">GET A FREE QUOTE NOW </a>
                </div>
            </div>
        </div>
    </section>
</template>


<style lang="scss">
@use '../style/partials/colors' as*;

.s5 {
    height: 800px;
    background-image: url(../../../public/avada-movers-movewithease-background-new.jpg);
    background-position: top left;
    background-size: cover;
    padding: 0 30px;
    .container {
        height: 100%;
        display: flex;
        justify-content: flex-end;
        align-items: center;
        .card {
            background-color: $cardS5Border;
            width: 625px;
            padding: 15px;
            .cardText {
                background-color: $lima;
                padding: 40px;
                display: flex;
                flex-direction: column;
                justify-content: flex-start;
                align-items: center;
                gap: 25px;
                h6,
                h4
                {
                    color: white;
                }
                p{
                    color: white;
                    line-height: 34px;
                }
                h4 {
                    padding: 0 25px 25px 25px;
                    border-bottom: 1px solid white;
                }
                a {
                    font-size: 18px;
                    padding: 17px 40px;
                    margin: 25px 0;
                }
            }
        }
    }
}

</style>