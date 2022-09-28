<template>
  <div class="wrapper">
    <img class="bg" src="@/assets/claimbg.png" alt="">
    <b-container>
        <b-row class="d-flex align-items-center">
            <b-col class="col1">
                <img src="@/assets/cuate2.png" alt="">
            </b-col>
            <b-col>
                <h2 class="title"><span>Claim</span> your corner of the internet today</h2>
                <div class="inputWrapper d-flex">
                    <b-form-input placeholder="cornerQR.com/corner/your-book-name"></b-form-input>
                    <b-button variant="dark">Claim your Corner</b-button>
                </div>
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
    position: relative;
    background-color: #FFC727;
    caret-color: transparent;
    padding: 80px 0;
}
.bg{
    max-height: 100%;
    position: absolute;
    top: 0;
    right: 0;
}
.col1{
    @media only screen and (max-width: 980px){
        display: flex;
        align-items: center;
        justify-content: center;
    }
    img{
        width: 422px;
        @media only screen and (max-width: 980px){
            width: 300px;
            margin-bottom: 30px;
        }
        @media only screen and (max-width: 580px){
            width: 260px;
        }
    }
}
.title{
    position: relative;
    z-index: 1;
    font-family: 'Nunito';
    font-style: normal;
    font-weight: 400;
    font-size: 48px;
    line-height: 65px;
    color: #000000;
    margin-bottom: 32px;
    span{
        font-weight: 700;
    }
    @media only screen and (max-width :580px){
        font-size: 36px;
        line-height: 45px;
    }
}
.inputWrapper{
    position: relative;
    z-index: 1;
    @media only screen and (max-width :980px){
        flex-direction: column;
    }
        input{
            border-radius: 100px;
            margin-right: 15px;
        }
        .btn-dark{
            width: min-content;
            min-width: 210px;
            border-radius: 100px;
            @media only screen and (max-width :980px){
                margin-top: 15px;
            }
        }
    }
</style>