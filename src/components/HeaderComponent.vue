<template>
    <header>
        <div id="header" class="container ">

            <div class="p-3">
                <img class="img-fluid" src="/public/images/dc-logo.png" alt="Logo">
            </div>
            <div id="nav" class="p-3">
                <ul>
                    <li>CHARACTERS</li>
                    <li>COMICS</li>
                    <li>MOVIES</li>
                    <li>TV</li>
                    <li>GAMES</li>
                    <li>COLLECTIBLES</li>
                    <li>VIDEOS</li>
                    <li>FANS</li>
                    <li>NEWS</li>
                    <li>SHOP</li>
                </ul>
            </div>

        </div>
    </header>
</template>

<script>
export default {
    name: 'HeaderComponent',
    data() {
        return {

        }
    }

}
</script>

<style lang="scss" scoped>
img {
    padding: 10px;
}

#header {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

ul {
    display: flex;
    align-items: center;
    margin: auto;
}

li {
    list-style: none;
    margin: 10px;
}


</style>