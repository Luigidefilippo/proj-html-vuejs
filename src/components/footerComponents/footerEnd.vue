<script>
export default {
}
</script>

<template>
    <footer>
        <p>© Copyright 2012 - 2023 | Avada Theme by ThemeFusion | All Rights Reserved | Powered by WordPress</p>

    </footer>
</template>

<style lang="scss">
@use '../style/partials/colors' as*;

footer{
    background-color:$lima;
    height: 150px;
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 25px;

    p{
        font-size: 14px;

    }
}

</style>