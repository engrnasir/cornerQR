<template>
  <div class="wrapper">
    <b-container>
        <b-row>
            <b-col align-self="center" class="col1">
                <svg width="72" height="72" viewBox="0 0 72 72" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M0 36C0 26.4522 3.79285 17.2955 10.5442 10.5442C17.2955 3.79285 26.4522 0 36 0C45.5478 0 54.7045 3.79285 61.4558 10.5442C68.2072 17.2955 72 26.4522 72 36C72 45.5478 68.2072 54.7045 61.4558 61.4558C54.7045 68.2072 45.5478 72 36 72C26.4522 72 17.2955 68.2072 10.5442 61.4558C3.79285 54.7045 0 45.5478 0 36ZM26.568 23.3865C26.3604 23.1716 26.1122 23.0002 25.8377 22.8823C25.5632 22.7644 25.2679 22.7023 24.9692 22.6997C24.6704 22.6971 24.3741 22.754 24.0976 22.8672C23.8211 22.9803 23.5699 23.1474 23.3586 23.3586C23.1474 23.5699 22.9803 23.8211 22.8672 24.0976C22.754 24.3741 22.6971 24.6704 22.6997 24.9692C22.7023 25.2679 22.7644 25.5632 22.8823 25.8377C23.0002 26.1122 23.1716 26.3604 23.3865 26.568L41.8185 45H29.3625C28.7658 45 28.1935 45.2371 27.7715 45.659C27.3496 46.081 27.1125 46.6533 27.1125 47.25C27.1125 47.8467 27.3496 48.419 27.7715 48.841C28.1935 49.2629 28.7658 49.5 29.3625 49.5H47.25C47.8467 49.5 48.419 49.2629 48.841 48.841C49.2629 48.419 49.5 47.8467 49.5 47.25V29.3625C49.5 28.7658 49.2629 28.1935 48.841 27.7715C48.419 27.3496 47.8467 27.1125 47.25 27.1125C46.6533 27.1125 46.081 27.3496 45.659 27.7715C45.2371 28.1935 45 28.7658 45 29.3625V41.8185L26.568 23.3865Z" fill="#222222"/>
                </svg>
                <h3 class="title">Our Books</h3>
            </b-col>
        </b-row>
        <b-row>
            <h3 class="heading">Discover more than +1000 book</h3>
            <h4 class="sub-heading">CHOOSE YOURS</h4>
        </b-row>
    </b-container>
        <div class="carousel-wrapper">
            <img src="@/assets/c-img1.png" class="card-item" alt="">
            <img src="@/assets/c-img2.png" class="card-item" alt="">
            <img src="@/assets/c-img3.png" class="card-item" alt="">
            <img src="@/assets/c-img4.png" class="card-item" alt="">
            <img src="@/assets/c-img4.png" class="card-item" alt="">
        </div>
        <div class="carousel-dots d-flex align-items-center justify-content-center">
            <div class="dot" v-for="i in 6" :key="i" :id="`dot${i}`" ></div>
        </div>
        <b-container>
            <b-row align-h="center">
                <b-button variant="dark">Get started for free</b-button>
            </b-row>
        </b-container>
    
  </div>
</template>

<script>
export default {
    methods:{
        setPosition(pos){
            var doc = document.documentElement;
            var cards = document.querySelector('.carousel-wrapper')
            if(pos == 'left'){cards.scrollLeft = 0}
            else if(pos == 'center'){cards.scrollLeft = 600}
            else if(pos == 'right'){cards.scrollLeft = 1200}
            
        },
        resetColor(){
            let dots =  document.querySelectorAll('.dot')
            for(let i=0; i<dots.length; i++){
                dots[i].style.backgroundColor = '#fff'
            }
        },
        setShowScroll(){
            var doc = document.documentElement;
            var cards = document.querySelector('.carousel-wrapper')

            var position = (cards.pageXOffset || cards.scrollLeft)  - (doc.clientLeft || 0);
            console.log(position);
            this.resetColor()   
            if(position==0){
                document.getElementById('dot1').style.backgroundColor = '#000'
            }else if(position>200){
                document.getElementById('dot6').style.backgroundColor = '#000'
            }
            else if(position>150){
                document.getElementById('dot5').style.backgroundColor = '#000'
            }else if(position>100){
                document.getElementById('dot4').style.backgroundColor = '#000'
            }else if(position>30){
                document.getElementById('dot3').style.backgroundColor = '#000'
            }else if(position>0){
                document.getElementById('dot2').style.backgroundColor = '#000'
            }
        }
  },
  mounted() {
      document.querySelector('.carousel-wrapper').addEventListener('scroll', this.setShowScroll);
  },

}
</script>

<style lang="scss" scoped>
.wrapper{
        padding: 100px 0;
        background: #FFC727;
    }
    .col1{
        display: flex;
        align-items: center;
        justify-content: center;
        margin-bottom: 50px;
        svg{
            @media only screen and (max-width: 780px){
                width: 50px;
                height: 50px;
            }
        }
        .title{
            font-family: 'Nunito';
            font-weight: 800;
            font-size: 40px;
            color: #000000;
            margin-left: 24px;
            @media only screen and (max-width: 780px){
                font-size: 32px;
            }
        }
    }
    .heading{
        font-family: 'Nunito';
        font-style: normal;
        font-weight: 400;
        font-size: 48px;
        line-height: 65px;
        text-align: center;
        color: #222222;
        @media only screen and (max-width: 780px){
            font-size: 36px;
            line-height: 55px;
        }
    }
    .sub-heading{
        font-family: 'Nunito';
        font-style: normal;
        font-weight: 400;
        font-size: 20px;
        line-height: 27px;
        text-align: center;
        letter-spacing: 0.3em;
        color: #222222;
        opacity: 0.3;
    }
    .btn-dark{
        width: 218px;
        background: #222222;
        box-shadow: 0px 16px 32px rgba(0, 0, 0, 0.16);
        border-radius: 100px;
        font-weight: 600;
        font-size: 16px;
        line-height: 25px;
        color: #FFFFFF;
    }
    .carousel-wrapper{
        width: 100%;
        display: flex;
        align-items: center;
        overflow-x: scroll;
        padding: 30px 0;
        margin-bottom: 40px;
        .card-item{
            border: none;
            box-shadow: none;
            background: transparent;
            background-color: transparent;
            height: 360px;
            margin: 0 20px;
            border-radius: 20px;
            @media only screen and (max-width:980px){
                height: 280px;
                margin: 0 10px;
            }
            @media only screen and (max-width:780px){
                height: 250px;
                margin: 0 10px;
            }
            @media only screen and (max-width:580px){
                height: 200px;
                margin: 0 10px;
            }
        }
        &::-webkit-scrollbar {
        display: none;
    }
    }
    .carousel-dots{
        width: 100%;
        margin-bottom: 40px;
        #dot1{
            background-color: #000;
        }
        .dot{
            width: 16px;
            height: 16px;
            border-radius: 50%;
            background: #fff;
            margin: 5px;
        }
        #dot3,#dot4{
            width: 12px;
            height: 12px;
        }
        #dot5,#dot6{
            width: 6px;
            height: 6px;
        }
    }
    
   
</style>