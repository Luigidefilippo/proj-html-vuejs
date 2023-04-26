<script>
export default {
}
</script>


<template>
<header>
        <div class="container">
            <p>Call us for a Free Quote: 1.800.555.6789</p>
            <ul>
                        <!-- FIX FONT AWESON AND ADD AGAIN SOCIAL ICONS -->
            </ul>
        </div>
    </header>
</template>

<style lang="scss">
@use './style/partials/colors' as*;
@use './style/main.scss' as*;

header {
    height: 47px;
    background-color: $lima;
    font-size: 13px;
    color: white;
    padding: 0 30px;

    .container {
        height: 100%;
        display: flex;
        justify-content: space-between;
        align-items: center;

        ul {
            display: flex;
            gap: 20px;
        }
    }
}

</style>