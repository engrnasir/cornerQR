<template>
  <div class="wrapper">
    <b-container>
        <b-row align-v="center" align-h="between">
            <b-col class="col1">
                <h1 class="heading"><span>Single code —</span> for the Published author</h1>
                <p class="snippet">Best way to share all that your book has to offer. Take your book and its readers to the next level.</p>
                <div class="inputWrapper d-flex">
                    <b-form-input placeholder="cornerQR.com/corner/your-book-name"></b-form-input>
                    <b-button variant="dark">Claim your Corner</b-button>
                </div>
            </b-col>

            <b-col class="hero">
                <img src="@/assets/iphone13.png" alt="" class="phoneImg">
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
        background-color: #FFC727;
        caret-color: transparent;
        padding: 0 20px;
        padding-bottom: 50px;
    }
    .heading{
        font-family: 'Nunito';
        font-style: normal;
        font-weight: 400;
        font-size: 56px;
        line-height: 120%;
        color: #222222;
        span{
            font-weight: 700;
        }
        @media only screen and (max-width:990px){
            font-size: 40px;
        }
        @media only screen and (max-width:760px){
            font-size: 28px;
        }
    }

    .row{
        padding: 0 50px;
        @media only screen and (max-width:760px){
            padding: 0;
        }
    }
    .col1{
        min-width: 60%;
    }
    .hero{
        display: flex;
        justify-content: center;
    }
    .snippet{
        font-weight: 400;
        font-size: 20px;
        color: rgba(34, 34, 34, 0.7);
        @media only screen and (max-width:990px){
            font-size: 18px;
        }
        @media only screen and (max-width:760px){
            font-size: 15px;
        }
    }
    .phoneImg{
        height: 504.81px;
        filter: drop-shadow(16px 16px 64px rgba(254, 222, 132, 0.7));
        transform: rotate(5.44deg);
        @media only screen and (max-width:990px){
            height: 400px;
        }
        @media only screen and (max-width:760px){
            height: 300px;
        }
        @media only screen and (max-width:460px){
            margin-top: 30px;
        }
    }
    .inputWrapper{
        @media only screen and (max-width:990px){
            flex-direction: column;
        }
        input{
            border-radius: 100px;
            margin-right: 15px;
            @media only screen and (max-width:760px){
                font-size: 12px;
            }
        }
        .btn-dark{
            min-width: 210px;
            width: min-content;
            border-radius: 100px;
            @media only screen and (max-width:990px){
                margin-top: 20px;
            }
            @media only screen and (max-width:760px){
                font-size: 14px;
            }
        }
    }

</style>