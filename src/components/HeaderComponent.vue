<template>
    <header>
        <div id="header">
            <img src="../assets/img/dc-logo.png" alt="Logo">


            <ul>
                <li>CHARACTERS</li>
                <li>COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTIBILES</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>SHOP</li>
            </ul>
        </div>
    </header>
</template>

<script>
export default {
    name: 'HeaderComponent',
    data() {
        return {
            title: 'HeaderComponent'
        }
    }

}
</script>

<style lang="css" scoped>





header {
    width: 1200px;
    display: flex;
    align-items: center;
    margin: auto;
    
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
    padding-left: 250px;
}

li {
    list-style: none;
    margin: 10px;
}

a {
    text-decoration: none;
    color: black;
    font-weight: bold;
}
</style>