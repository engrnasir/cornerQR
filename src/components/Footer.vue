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
                <!-- Social Icons -->
                <div class="social-icons d-flex align-items-center justify-content-start">
                    <!-- Insta Icon -->
                    <a href="#" class="icon">
                        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M11.997 7.9983C9.79351 7.9983 7.99529 9.79651 7.99529 12C7.99529 14.2035 9.79351 16.0017 11.997 16.0017C14.2005 16.0017 15.9987 14.2035 15.9987 12C15.9987 9.79651 14.2005 7.9983 11.997 7.9983ZM23.9991 12C23.9991 10.3429 24.0141 8.70077 23.9211 7.04665C23.828 5.12536 23.3897 3.4202 21.9847 2.01525C20.5768 0.607302 18.8746 0.172008 16.9533 0.0789456C15.2962 -0.0141173 13.6541 0.000892936 12 0.000892936C10.3429 0.000892936 8.70077 -0.0141173 7.04665 0.0789456C5.12535 0.172008 3.4202 0.610305 2.01525 2.01525C0.607303 3.42321 0.172008 5.12536 0.0789456 7.04665C-0.0141172 8.70377 0.000892936 10.3459 0.000892936 12C0.000892936 13.6541 -0.0141172 15.2992 0.0789456 16.9533C0.172008 18.8746 0.610305 20.5798 2.01525 21.9847C3.4232 23.3927 5.12535 23.828 7.04665 23.9211C8.70377 24.0141 10.3459 23.9991 12 23.9991C13.6571 23.9991 15.2992 24.0141 16.9533 23.9211C18.8746 23.828 20.5798 23.3897 21.9847 21.9847C23.3927 20.5768 23.828 18.8746 23.9211 16.9533C24.0171 15.2992 23.9991 13.6571 23.9991 12ZM11.997 18.1572C8.58969 18.1572 5.83984 15.4073 5.83984 12C5.83984 8.5927 8.58969 5.84284 11.997 5.84284C15.4043 5.84284 18.1542 8.5927 18.1542 12C18.1542 15.4073 15.4043 18.1572 11.997 18.1572ZM18.4063 7.02864C17.6108 7.02864 16.9684 6.38621 16.9684 5.59067C16.9684 4.79513 17.6108 4.1527 18.4063 4.1527C19.2019 4.1527 19.8443 4.79513 19.8443 5.59067C19.8445 5.77957 19.8075 5.96667 19.7353 6.14124C19.6631 6.31581 19.5572 6.47442 19.4237 6.608C19.2901 6.74157 19.1315 6.84748 18.9569 6.91967C18.7823 6.99185 18.5952 7.02888 18.4063 7.02864Z" fill="#FFC727"/>
                        </svg>
                    </a>
                    <!-- Twitter Icon -->
                    <a href="#" class="icon">
                        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <g clip-path="url(#clip0_718_1430)">
                        <path d="M12.0005 0C5.3737 0 0.000488281 5.37321 0.000488281 12C0.000488281 18.6268 5.3737 24 12.0005 24C18.6273 24 24.0005 18.6268 24.0005 12C24.0005 5.37321 18.6273 0 12.0005 0ZM17.7675 9.04554C17.7755 9.17143 17.7755 9.30268 17.7755 9.43125C17.7755 13.3634 14.7808 17.8929 9.30852 17.8929C7.62102 17.8929 6.05674 17.4027 4.73888 16.5589C4.97995 16.5857 5.21031 16.5964 5.45674 16.5964C6.8496 16.5964 8.12995 16.125 9.15049 15.3268C7.84335 15.3 6.74513 14.4429 6.37013 13.2643C6.82817 13.3313 7.24067 13.3313 7.7121 13.2107C7.03904 13.074 6.43408 12.7084 6 12.1762C5.56591 11.644 5.32947 10.9779 5.33085 10.2911V10.2536C5.7246 10.4759 6.18799 10.6125 6.67281 10.6313C6.26524 10.3596 5.931 9.99164 5.69971 9.5599C5.46843 9.12817 5.34725 8.64603 5.34692 8.15625C5.34692 7.60179 5.49156 7.09554 5.75138 6.65625C6.49844 7.5759 7.43066 8.32806 8.48745 8.86384C9.54423 9.39961 10.7019 9.70702 11.8853 9.76607C11.4648 7.74375 12.9755 6.10714 14.7916 6.10714C15.6487 6.10714 16.4201 6.46607 16.9639 7.04464C17.6362 6.91875 18.2791 6.66696 18.8523 6.32946C18.63 7.01786 18.1639 7.59911 17.5451 7.96607C18.1451 7.90179 18.7237 7.73571 19.2594 7.50268C18.855 8.09732 18.3487 8.625 17.7675 9.04554Z" fill="#FFC727"/>
                        </g>
                        <defs>
                        <clipPath id="clip0_718_1430">
                        <rect width="24" height="24" fill="white" transform="translate(0.000488281)"/>
                        </clipPath>
                        </defs>
                        </svg>
                    </a>
                    <!-- Facebook -->
                    <a href="#" class="icon">
                        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <g clip-path="url(#clip0_718_1433)">
                        <path fill-rule="evenodd" clip-rule="evenodd" d="M0.000488281 12.067C0.000488281 18.033 4.33349 22.994 10.0005 24V15.333H7.00049V12H10.0005V9.333C10.0005 6.333 11.9335 4.667 14.6675 4.667C15.5335 4.667 16.4675 4.8 17.3335 4.933V8H15.8005C14.3335 8 14.0005 8.733 14.0005 9.667V12H17.2005L16.6675 15.333H14.0005V24C19.6675 22.994 24.0005 18.034 24.0005 12.067C24.0005 5.43 18.6005 0 12.0005 0C5.40049 0 0.000488281 5.43 0.000488281 12.067Z" fill="#FFC727"/>
                        </g>
                        <defs>
                        <clipPath id="clip0_718_1433">
                        <rect width="24" height="24" fill="white" transform="translate(0.000488281)"/>
                        </clipPath>
                        </defs>
                        </svg>
                    </a>
                    <!-- LinkedIn -->
                    <a href="#" class="icon">
                        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M12.0005 0C5.37299 0 0.000488281 5.3725 0.000488281 12C0.000488281 18.6275 5.37299 24 12.0005 24C18.628 24 24.0005 18.6275 24.0005 12C24.0005 5.3725 18.628 0 12.0005 0ZM9.06299 16.9738H6.63299V9.15375H9.06299V16.9738ZM7.83299 8.19375C7.06549 8.19375 6.56924 7.65 6.56924 6.9775C6.56924 6.29125 7.08049 5.76375 7.86424 5.76375C8.64799 5.76375 9.12799 6.29125 9.14299 6.9775C9.14299 7.65 8.64799 8.19375 7.83299 8.19375ZM17.938 16.9738H15.508V12.64C15.508 11.6313 15.1555 10.9462 14.2767 10.9462C13.6055 10.9462 13.2067 11.41 13.0305 11.8563C12.9655 12.015 12.9492 12.24 12.9492 12.4638V16.9725H10.518V11.6475C10.518 10.6713 10.4867 9.855 10.4542 9.1525H12.5655L12.6767 10.2388H12.7255C13.0455 9.72875 13.8292 8.97625 15.1405 8.97625C16.7392 8.97625 17.938 10.0475 17.938 12.35V16.9738Z" fill="#FFC727"/>
                        </svg>
                    </a>

                </div>
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
        padding: 110px 20px;
        padding-bottom: 60px;
        @media only screen and (max-width:760px){
            padding: 70px 20px;
        }
    }
    .row{
        @media only screen and (max-width:760px){
            flex-direction: column;   
        }
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
    .social-icons{
        .icon{
            margin-right: 15px;
        }
    }
</style>