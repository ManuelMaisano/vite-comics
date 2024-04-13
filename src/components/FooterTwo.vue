<template>
    <div id="footer">
        <div class="container d-flex ">
            <div id="list">
                <ul class="list-unstyled pe-3 " v-for="(item, index) in menufooter" :key="index">
                    <li>
                        <h4 class="text-white">{{ item.title }}</h4>
                    </li>
                    <li v-for="(item, index) in item.links" :key="index"><a href="">{{ item.text }}</a></li>
                </ul>
            </div>
            <div id="dc-comics"></div>
        </div>
    </div>
</template>


<script>
    export default {
        name: 'FooterTwo',
        data() {
            return {
                menufooter: [
                    {
                        title: 'DC Comics', 
                        links: [
                            {
                                text: 'Characters' 
                            },
                            {
                                text: 'Comics'
                            },
                            {
                                text: 'Movies'
                            },
                            {
                                text: 'TV'
                            },
                            {
                                text: 'Games' 
                            },
                            {
                                text: 'Videos'
                            },
                            {
                                text: 'News'
                            },
                        ],
                    },
                    {
                        title: 'Shop',
                        links: [
                            {
                                text: 'Shop DC'
                            },
                            {
                                text: 'Shop DC Collectibles'
                            }
                        ]
                    },
                    {
                        title: 'DC',
                        links: [
                            {
                                text: 'Terms of Use' 
                            },
                            {
                                text: 'Privacy Policy (New)' 
                            },
                            {
                                text: 'Ad Choices'
                            },
                            {
                                text: 'Advertising'
                            },
                            {
                                text: 'Jobs'
                            },
                            {
                                text: 'Subscriptions'
                            },
                            {
                                text: 'Talent Workshops'
                            },
                            {
                                text: 'CPSC Certificates'
                            },
                            {
                                text: 'Ratings'
                            },
                            {
                                text: 'Shop Help'
                            },
                            {
                                text: 'Contact Us' 
                            },
                        ]
                    },
                    {
                        title: 'Sites',
                        links: [
                            {
                                text: 'DC'
                            },
                            {
                                text: 'MAD Magazine'
                            },
                            {
                                text: 'DC Kids'
                            },
                            {
                                text: 'DC Universe'
                            },
                            {
                                text: 'DC Power Visa'
                            },
                        ]
                    },
                ]
            };
        }
    };
</script>

<style lang="scss" scoped>

    #footer {

        background-image: url('../assets/img/footer-bg.jpg');


        #list {
            width: 30%;
            height: 390px;
            display: flex;
            flex-wrap: wrap;
            flex-direction: column;
            padding: 30px 0px;

           

            li {

                a {
                    color: grey;
                    text-decoration: none;

                    &:hover{
                        color: white;
                    }
                }



            }
        }

        #dc-comics {
            width: 70%;
            background-image: url('../assets/img/dc-logo-bg.png');
            background-position: right;
            background-repeat: no-repeat;
            background-size: 65%;

        }
    }

</style>