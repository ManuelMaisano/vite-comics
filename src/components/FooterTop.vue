<template>
    <footer>
        <div class="container">
            <ul class="d-flex justify-content-around align-items-center list-unstyled">
                <li><img src="/public/images/buy-comics-digital-comics.png" alt="DigitalComics"><a
                        class="text-decoration-none mx-3 text-uppercase" ef="&">DIGITAL COMICS</a></li>
                <li><img src="/public/images/buy-comics-merchandise.png" alt="DCmerchandise"><a
                        class="text-decoration-none mx-3 text-uppercase" ef="&">DC MERCHANDISE</a></li>
                <li><img src="/public/images/buy-comics-subscriptions.png" alt="Subcripition"><a
                        class="text-decoration-none mx-3 text-uppercase" ef="&">SUBCRIPTION</a></li>
                <li><img src="/public/images/buy-comics-shop-locator.png" alt="ComicSHopLocator"><a
                        class="text-decoration-none mx-3 text-uppercase" ef="&">COMIC SHOP LOCATOR</a></li>
                <li><img src="/public/images/buy-dc-power-visa.svg" alt="DcPowerVisa"><a
                        class="text-decoration-none mx-3 text-uppercase" ef="&">DC POWER VISA</a></li>
            </ul>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'FooterTop',
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

ul {
    display: flex;
    align-items: center;
    margin: auto;
}

li {
    list-style: none;
    margin: 10px;
}

a {
    color: white;
}

a:hover {
    color: rgb(208, 208, 208);
}

img {
    height: 70px;
}
</style>