<script>
export default{

}

</script>


<template>
<section class="s7">
    <div class="container">
        <h4>REQUEST A FREE QUOTE</h4>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti quaerat commodi magni iste officia ut, eveniet nam expedita sapiente veritatis delectus aliquam, fugiat voluptatem totam id dolore suscipit. Ratione, similique.</p>
        <a href="#" class="button">click here</a>
    </div>
</section>

</template>


<style lang="scss">
@use '../style/partials/colors' as*;

.s7{
    height: 540px;
    background-image: url(../../../public/avada-movers-request-quote-background.jpg);
    background-position: top center;
    background-size: cover;
    padding: 0 30px;

    .container{
        width: 750px;
        height: 100%;
        text-align: center;
        color: $smallTitle;
        line-height: 30px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap:  35px;
        
    }
}



</style>