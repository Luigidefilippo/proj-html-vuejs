<script>
export default{

}
</script>

<template>
    <div class="limefooter"></div>
    <section class="footermain">
        <div class="container">
            <div class="row">
                <div class="col">
                    <h5>about</h5>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis convallis ex ut sem accumsan vehicula.
                        Integer elit arcu, hendrerit id sapien ut, facilisis accumsan arcu.</p>
                    <img src="../../../public/avada-movers-logo.png" alt="">
                </div>
                <div class="col">
                    <h5>avada movers</h5>
                    <ul class="navfooter">
                        <li><a href="#">Home</a></li>
                        <li><a href="#">Rates</a></li>
                        <li><a href="#">Testimonials</a></li>
                        <li><a href="#">Blog</a></li>
                        <li><a href="#">Free Quote</a></li>
                    </ul>
                </div>
                <div class="col list">
                    <h5>recent posts</h5>
                    <ul>
                        <li><a href="#">&raquo; Heading Out To College?</a></li>
                        <li><a href="#">&raquo; Moving Your Business</a></li>
                        <li><a href="#">&raquo; Outstanding Quality</a></li>
                        <li><a href="#">&raquo; Cost of Moving</a></li>
                        <li><a href="#">&raquo; Best Moving Tips</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss">
@use '../style/partials/colors' as*;

.footermain {
    height: 480px;
    background-color:white;
    padding: 70px 30px 50px;
    .container {
        height: 100%;
        .row {
            height: 100%;
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            gap: 50px;
            .col {
                flex-basis: calc(100% / 3);
                display: flex;
                flex-direction: column;
                img {
                    align-self: flex-start;
                }
                h5 {
                    color: black;
                    text-transform: uppercase;
                    font-size: 19px;
                    margin-bottom: 40px;
                    text-align: center;
                }
                p {
                    line-height: 30px;
                    color: $smallTitle;
                    margin-bottom: 40px;
                }
                .navfooter{
                    display: flex;
                    flex-direction: column;
                    color: $smallTitle;
                    
                    li {
                        transition: color 0.3s ease-in-out;
                    }
                    li:hover {
                        color: $lima;
                    }
                }
            }
            .list {
                li:hover {
                    color: $lima;
                    padding-left: 1em;
                    text-indent: -1em;
                }

                }
            }
        }
    }
.limefooter{
    height: 20px;
    background-color: $lima;
}
</style>