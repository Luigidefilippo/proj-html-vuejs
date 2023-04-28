<script>
export default{
    
}
</script>

<template>
    <div class="section2">
        <p>
            GET A FREE QUOTE ONLINE NOW !
        </p>
    </div>

</template>

<style lang="scss">
@use '../style/partials/colors' as*;


.section2 {
    background-color: black;
    height: 141px;
    background-color: $denim;
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    font-size: 18px;
    text-transform: uppercase;
    transition: background-color 0.3s ease-in-out;
}
.section2:hover{
    background-color: lighten($denim, 15%);
}
</style>