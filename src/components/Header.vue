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
    }

    .row{
        padding: 0 50px;
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
    }
    .phoneImg{
        height: 504.81px;
        filter: drop-shadow(16px 16px 64px rgba(254, 222, 132, 0.7));
        transform: rotate(5.44deg);
    }
    .inputWrapper{
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