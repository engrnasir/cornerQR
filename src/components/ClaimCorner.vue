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
    img{
        width: 422px;
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
}
.inputWrapper{
    position: relative;
    z-index: 1;
        input{
            border-radius: 100px;
            margin-right: 15px;
        }
        .btn-dark{
            min-width: 210px;
            border-radius: 100px;
        }
    }
</style>