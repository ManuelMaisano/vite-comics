<template>
    <footer>
        <div>
            <ul>
                <li><img src="../assets/img/buy-comics-digital-comics.png" alt="digital comics"><span>DIGITAL
                        COMICS</span></li>
                <li><img src="../assets/img/buy-comics-merchandise.png" alt="merchandise"> <span>DC MERCHANDISE</span>
                </li>
                <li><img src="../assets/img/buy-comics-subscriptions.png" alt="subscription"> <span>SUBSCIPTION</span>
                </li>
                <li><img src="../assets/img/buy-comics-shop-locator.png" alt="shoplocator"><span>COMIC SHOP
                        LOCATOR</span></li>
            </ul>
        </div>

    </footer>


</template>

<script>
export default {
    name: 'FooterOne',
    data() {
        return {

        }
    }
}
</script>

<style lang="scss" scoped>
footer {
    background-color: #0282F9;
}

img{
    width: 50px;
}
ul {
    display: flex;
    align-items: center;
    margin: auto;
    width: 1200px;
    justify-content: space-between;

}

li {
    display: flex;
    list-style: none;
    margin: 10px;
    padding: 10px;
   

}

span {
    color: white;
    display: flex;
    text-align: center;
    padding: 25px;
}
</style>
