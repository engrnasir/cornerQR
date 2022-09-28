<template>
  <div class="wrapper">
    <b-container>
        <b-row class="d-flex align-items-start">
            <b-col class="col1">
                <h3 class="title logo">cornerQR</h3>
                <p class="item"><a href="">Built with 💙 by authors for authors in Athens, GA</a></p>
            </b-col>
            <b-col>
                <h3 class="title">Company</h3>
                <p class="item"><a href="">About Us</a></p>
                <p class="item"><a href="">Discover</a></p>
                <p class="item"><a href="">Our Blog</a></p>
                <p class="item"><a href="">Pricing</a></p>
            </b-col>
            <b-col>
                <h3 class="title">Support</h3>
                <p class="item"><a href="">Privacy</a></p>
                <p class="item"><a href="">Tearms and Conditions</a></p>
                <p class="item"><a href="">Data and Cookie Policy (GPDR)</a></p>
            </b-col>
            <b-col>
                <h3 class="title">Address</h3>
                <p class="item"><a href="">9461 Charleville Blvd. #888
Beverly Hills, CA 90212</a></p>
                <p class="item"><a href="">Email: hi@journeybinder.com</a></p>
                <p class="item"><a href="">Phone: + (559) 512-0719</a></p>
            </b-col>
        </b-row>
        <b-row>
            <div class="h-line"></div>
        </b-row>
        <b-row>
            <p class="copy-text">Copyright 2022 © cornerQR all rights reserved</p>
        </b-row>
    </b-container>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .wrapper{
        background: #222222;
        padding: 110px 0;
        padding-bottom: 60px;
    }
    .col1{
        margin-right: 100px;
    }
    .col{
        .title{
            font-family: 'Nunito';
            font-style: normal;
            font-weight: 700;
            font-size: 18px;
            line-height: 33px;
            color: #FFC727;
            margin-bottom: 24px;
        }
        .logo{
            font-size: 24px;
        }
        .item a{
            text-decoration: none;
            font-family: 'Nunito';
            font-style: normal;
            font-weight: 400;
            font-size: 14px;
            color: #FFFFFF;
            margin-bottom: 16px;
        }
    }
    .h-line{
        width: 100%;
        height: 0px;
        border: 1px solid  #333333;
        margin-top: 80px;
        margin-bottom: 30px;
    }
    .copy-text{
        font-family: 'Nunito';
        font-style: normal;
        font-weight: 400;
        font-size: 12px;
        line-height: 120%;
        color: #FFFFFF;
        text-align: center;
    }

</style>