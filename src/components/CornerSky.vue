<template>
  <div class="wrapper">
    <b-container>
        <b-row align-v="center">
            <b-col class="col1">
                <img src="@/assets/ant.png" alt="">
            </b-col>
            <b-col class="col2">
                <h3 class="title"><span class="create">Create and customize</span><br> Your corner of the sky <br><span class="mint">in minutes</span></h3>
                <p class="snippet">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mollis mauris tincidunt at ultricies est felis hac. Iaculis neque leo, eget pretium vestibulum.</p>
                <b-button variant="dark">Get started for free</b-button>
            </b-col>
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
        padding: 130px 0;
        background: #FFC727;
        @media only screen and (max-width: 980px){
            padding: 80px 0;
        }
    }
    .row{
        @media only screen and (max-width: 980px){
            flex-direction: column;
        }
    }
    .col1{
        img{
            width: 100%;
            filter: drop-shadow(0px 24px 48px rgba(0, 0, 0, 0.05));
            border-radius: 16px;
        }
    }
    .col2{
        .title{
            font-family: 'Nunito';
            font-weight: 800;
            font-size: 40px;
            line-height: 55px;
            color: #222222;
            margin-bottom: 30px;
            @media only screen and (max-width: 780px){
                font-size: 28px;
                line-height: 35px;
            }
            .create{
                color: rgba(34, 34, 34, 0.7);
                font-weight: 400;
                font-size: 24px;
            }
            .mint{
                font-weight: 400;
            }
        }
        .snippet{
                font-family: 'Nunito';
                font-style: normal;
                font-weight: 400;
                font-size: 18px;
                line-height: 29px;
                color: rgba(0, 0, 0, 0.7);
                @media only screen and (max-width: 780px){
                    font-size: 14px;
                    line-height: 18px;
                }
            }
        }
        .btn-dark{
            background: #222222;
            box-shadow: 0px 16px 32px rgba(0, 0, 0, 0.16);
            border-radius: 100px;
            font-weight: 600;
            font-size: 16px;
            line-height: 25px;
            color: #FFFFFF;
        }

</style>