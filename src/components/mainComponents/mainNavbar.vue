<script>
export default{

    data() {
        return {
            navbarElement: [
            {
                    "name": "Home",
                    "active": "true",
                    "button": "false"
                },

                {
                    "name": "Rates",
                    "active": "false",
                    "button": "false"
                },

                {
                    "name": "Tesimonials",
                    "active": "false",
                    "button": "false"
                },

                {
                    "name": "FAQ",
                    "active": "false",
                    "button": "false"
                },

                {
                    "name": "Blog",
                    "active": "false",
                    "button": "false"
                },

                {
                    "name": "Contact",
                    "active": "false",
                    "button": "false"
                },

                {
                    "name": "Free Quote",
                    "active": "false",
                    "button": "true"
                },
            ]

        }
    }
}
</script>


<template>
    <nav>
        <div class="container">
            <img src="../../../public/avada-movers-logo.png" alt="">
            <ul>
                <li v-for="(el, i) in navbarElement" :key="i" :class="{ button: el.button == 'true', active: el.active == 'true' }">
                    <a href="#"> {{ el.name }}</a>
                </li>
            </ul>
        </div>
    </nav>
</template>

<style lang="scss">
@use '../style/partials/colors' as*;

nav {
    height: 105px;
    padding: 0 30px;

    .container {
        height: 100%;
        display: flex;
        align-items: center;
        justify-content: space-between;
        ul {
            display: flex;
            align-items: center;
            gap: 50px;
            font-weight: 700;
            .active {
                color: $lima;
            }
        }
    }
}
</style>