<script>
export default{

}
</script>

<template>
     <section class="s3">
        <div class="container">
            <h5>HEADACHE FREE</h5>
            <h1>Award Winning<br>Moving Company</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore molestiae enim cum delectus ipsam expedita, officiis doloribus modi odit voluptatum asperiores dolorem perferendis esse exercitationem, veritatis molestias tenetur mollitia vero!</p>
            <a href="#" class="button">Read our testimonial</a>
        </div>
    </section>
</template>

<style lang="scss">
@use '../style/partials/colors' as*;

.s3 {
    text-align: center;
    height: 600px;
    background-color: $sectionBg;
    .container {
        width: 600px !important;
        height: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        gap: 40px;
        
        h5{
            padding-top: 100px;
            color: $smallTitle;
        }
        
        h1{
            color: $lima;
            font-size: 50px;
        }
        
        p{
            line-height: 30px;
        }
    }
}
</style>