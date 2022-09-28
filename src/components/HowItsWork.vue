<template>
  <div class="wrapper">
    <b-container>
        <b-row>
            <b-col align-self="center" class="col1">
                <svg width="72" height="72" viewBox="0 0 72 72" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M0 36C0 26.4522 3.79285 17.2955 10.5442 10.5442C17.2955 3.79285 26.4522 0 36 0C45.5478 0 54.7045 3.79285 61.4558 10.5442C68.2072 17.2955 72 26.4522 72 36C72 45.5478 68.2072 54.7045 61.4558 61.4558C54.7045 68.2072 45.5478 72 36 72C26.4522 72 17.2955 68.2072 10.5442 61.4558C3.79285 54.7045 0 45.5478 0 36ZM26.568 23.3865C26.3604 23.1716 26.1122 23.0002 25.8377 22.8823C25.5632 22.7644 25.2679 22.7023 24.9692 22.6997C24.6704 22.6971 24.3741 22.754 24.0976 22.8672C23.8211 22.9803 23.5699 23.1474 23.3586 23.3586C23.1474 23.5699 22.9803 23.8211 22.8672 24.0976C22.754 24.3741 22.6971 24.6704 22.6997 24.9692C22.7023 25.2679 22.7644 25.5632 22.8823 25.8377C23.0002 26.1122 23.1716 26.3604 23.3865 26.568L41.8185 45H29.3625C28.7658 45 28.1935 45.2371 27.7715 45.659C27.3496 46.081 27.1125 46.6533 27.1125 47.25C27.1125 47.8467 27.3496 48.419 27.7715 48.841C28.1935 49.2629 28.7658 49.5 29.3625 49.5H47.25C47.8467 49.5 48.419 49.2629 48.841 48.841C49.2629 48.419 49.5 47.8467 49.5 47.25V29.3625C49.5 28.7658 49.2629 28.1935 48.841 27.7715C48.419 27.3496 47.8467 27.1125 47.25 27.1125C46.6533 27.1125 46.081 27.3496 45.659 27.7715C45.2371 28.1935 45 28.7658 45 29.3625V41.8185L26.568 23.3865Z" fill="#FFC727"/>
                </svg>
                <h3 class="title">How it Works</h3>
            </b-col>
        </b-row>
        <b-row class="d-flex justify-content-between align-items-center mb-5">
            <b-col>
                <ul class="list">
                    <h3 class="sub-heading">Social <span>Marketing</span></h3>
                    <li class="list-item" v-for="(el, index) in socialList" :key="index">
                        <div class="tick">
                            <svg width="9" height="7" viewBox="0 0 9 7" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M8.29358 1.0955C8.25863 1.20098 8.20292 1.2984 8.12976 1.38203L3.96309 6.38203C3.88897 6.47095 3.79713 6.54345 3.69344 6.59491C3.58974 6.64636 3.47646 6.67565 3.36082 6.68091C3.24518 6.68616 3.12971 6.66726 3.02177 6.62542C2.91384 6.58357 2.81581 6.5197 2.73393 6.43787L0.233927 3.93786C0.0821286 3.7807 -0.00186726 3.57019 3.15047e-05 3.3517C0.00193027 3.1332 0.089571 2.92419 0.244078 2.76968C0.398584 2.61518 0.607596 2.52753 0.826093 2.52564C1.04459 2.52374 1.25509 2.60773 1.41226 2.75953L3.26643 4.61453L6.84976 0.315364C6.91883 0.228318 7.00461 0.155965 7.10205 0.102559C7.19949 0.0491533 7.30663 0.0157747 7.41716 0.00438787C7.5277 -0.00699996 7.63939 0.00383283 7.74568 0.0362501C7.85196 0.0686665 7.95069 0.122013 8.03605 0.19315C8.12141 0.264285 8.19169 0.351775 8.24274 0.450471C8.29379 0.549168 8.32459 0.657077 8.33332 0.767852C8.34205 0.878626 8.32854 0.990029 8.29358 1.0955Z" fill="#FFC727"/>
                            </svg>
                        </div>
                        <p>{{el}}</p>
                    </li>
                </ul>
            </b-col>
            <b-col class="d-flex justify-content-center align-items-center">
                <img src="@/assets/cuate.png" alt="" class="cuate">
            </b-col>
        </b-row>
        <b-row>
            <svg width="1119" height="2" viewBox="0 0 1119 2" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path opacity="0.1" d="M0 1L1119 0.999902" stroke="#222222" stroke-width="2" stroke-dasharray="8 8"/>
            </svg>
        </b-row>
        <b-row class="d-flex flex-row-reverse justify-content-between align-items-center mt-5">
            <b-col>
                <ul class="list">
                    <h3 class="sub-heading">Supports the <span>Following</span></h3>
                    <li class="list-item" v-for="(el, index) in supportsList" :key="index">
                        <div class="tick">
                            <svg width="9" height="7" viewBox="0 0 9 7" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M8.29358 1.0955C8.25863 1.20098 8.20292 1.2984 8.12976 1.38203L3.96309 6.38203C3.88897 6.47095 3.79713 6.54345 3.69344 6.59491C3.58974 6.64636 3.47646 6.67565 3.36082 6.68091C3.24518 6.68616 3.12971 6.66726 3.02177 6.62542C2.91384 6.58357 2.81581 6.5197 2.73393 6.43787L0.233927 3.93786C0.0821286 3.7807 -0.00186726 3.57019 3.15047e-05 3.3517C0.00193027 3.1332 0.089571 2.92419 0.244078 2.76968C0.398584 2.61518 0.607596 2.52753 0.826093 2.52564C1.04459 2.52374 1.25509 2.60773 1.41226 2.75953L3.26643 4.61453L6.84976 0.315364C6.91883 0.228318 7.00461 0.155965 7.10205 0.102559C7.19949 0.0491533 7.30663 0.0157747 7.41716 0.00438787C7.5277 -0.00699996 7.63939 0.00383283 7.74568 0.0362501C7.85196 0.0686665 7.95069 0.122013 8.03605 0.19315C8.12141 0.264285 8.19169 0.351775 8.24274 0.450471C8.29379 0.549168 8.32459 0.657077 8.33332 0.767852C8.34205 0.878626 8.32854 0.990029 8.29358 1.0955Z" fill="#FFC727"/>
                            </svg>
                        </div>
                        <p>{{el}}</p>
                    </li>
                </ul>
            </b-col>
            <b-col class="d-flex justify-content-center align-items-center">
                <img src="@/assets/amico.png" alt="" class="cuate">
            </b-col>
        </b-row>
    </b-container>
  </div>
</template>

<script>
export default {
    data(){
        return{
            socialList:[
                'One tap generation of a unique QR for Facebook, Instagram and 30+ social networks',
                'New Readers scan your QR on Social Networks',
                'New Purchasers scan your QR code from the corner of your book',
                'User is directed to a page where they can purchase, register or see more resources',
                'Collect Analytics and Register user'
            ],
            supportsList:[
                'Sales direct to Amazon, Shopify,',
                'Unique codes for all social: Facebook, Instagram,',
                'Multi-Lingual',
                'Know where your users are coming from.',
                'Registration link to get even more deals',
                'Unique code to track from Facebook'
            ]
        }
    }

}
</script>

<style lang="scss" scoped>
    .wrapper{
        padding: 100px 0;
        background: #f5f5f5;
    }
    .col1{
        display: flex;
        align-items: center;
        justify-content: center;
        margin-bottom: 50px;
        .title{
            font-family: 'Nunito';
            font-weight: 800;
            font-size: 40px;
            color: #000000;
            margin-left: 24px;
        }
    }
    .list{
        list-style: none;
        .sub-heading{
            font-family: 'Nunito';
            font-style: normal;
            font-weight: 700;
            font-size: 40px;
            color: #222222; 
            margin-bottom: 20px;
            span{
                color: #FFC727;
            }
        }
        .list-item{
            display: flex;
            align-items: center;
            justify-content: flex-start;
            margin-bottom: 16px;
            .tick{
                min-width: 18px;
                min-height: 18px;
                display: flex;
                align-items: center;
                justify-content: center;
                border-radius: 50%;
                background: #222222;
                margin-right: 10px;
            }
            p{
                font-family: 'Nunito';
                font-style: normal;
                font-weight: 400;
                font-size: 16px;
                line-height: 24px;
                color: #222222;
                margin: 0;
            }
            
        }
    }
    .cuate{
        width: 402px;
    }

</style>