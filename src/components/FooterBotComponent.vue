<template>
    <div id="footerbot">
        <div class="container d-flex justify-content-between align-items-center">
            <button >SING UP NOW!</button>
            <div class="d-flex align-items-center">
                <div id="follow" class=" fs-4 fw-bold  ">FOLLOW US</div>
                <a href=""> <img class="img-fluid" src="/images/footer-facebook.png" alt="LogoFacebook"></a>
                <a href=""> <img class="img-fluid" src="/images/footer-twitter.png" alt="LogoTwitter"></a>
                <a href=""> <img class="img-fluid" src="/images/footer-youtube.png" alt="LogoYoutube"></a>
                <a href=""> <img class="img-fluid" src="/images/footer-pinterest.png" alt="LogoPinterest"></a>
                <a href=""> <img class="img-fluid" src="/images/footer-periscope.png" alt="LogoPeriscope"></a>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'FooterBotComponent',
    data() {
        return {

        }
    }
}
</script>

<style lang="scss" scoped>
#footerbot {
    background-color: #303030;
}

button {
    padding: 10px;
    border: 2px solid #0282F9;
    background-color: #303030;
  ;
    color: white;
    margin: 30px 0px;
}

div {
    #follow {
        color: #0282F9;
        margin-right: 10px;
    }

    img {
        margin: 0px 10px;
    }
}

</style>