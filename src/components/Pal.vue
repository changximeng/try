<template>
  <div class="main">
      <div class="left">
        <div class="logo">
          <img src="../assets/logo.png"/>
        </div>
        <div class="trophy">
          <img src="../assets/Trophy.png"/>
          <div class="text1"> Leaderboard </div>
        </div>
        <div class="profile">
          <img src="../assets/proF.png"/>
          <div class="text2"> Profile </div>
        </div>
        <div class="setting">
          <img src="../assets/setting.png"/>  
          <a>Setting</a>        
        </div>        
      </div>
        
      <div class="right">
        <div class="login">
          <img src="../assets/setting.png"/>  
          </div>
        <div class="prof">
          <img src="../assets/setting.png"/>  
        </div>
      </div>  
    </div>

 
</template>


<style>
    *{
      margin: 0;       
    }
    
    .main{
      max-width: 100%;
      max-height: 100%;   
      display: flex;
      /* flex-direction: row; */
      /* background-size: 100% 100%; */
    }

    .left{
      /* background-size: 200tpx,1024px; */
      /* float: right; */
      background-color: #40514e;
      max-width: 13.87%;
      max-height: 100%;
      /* height: 100%; */
      /* position: relative; */
      margin-right: 0%;
      /* background-position: left; */
      /* background-repeat: no-repeat; */
      /* left:0; */
      /* background-position-x: left 0px;
      background-position-y: 0px; */
    }

    .right{
      /* float: left; */
      background-color: #549382;  
      max-width: 86.13%;
      max-height: 100%;
      /* height: auto; */
      /* height: 100%; */
      /* position:relative; */
      margin-left: 0%;
      /* float: right; */
      /* background-position: right; */
      /* background-repeat: no-repeat; */
        
    }
    

    .logo{
        /* height 191/1024 wi 191/200 */
        /* top:15/1024 left:4.5/200*/
        max-height: 18.65%;
        /* max-width: 95.5%; */
        max-width: auto;
        /* margin-left: 2.25%;
        margin-right: 2.25%; */
        align:"center";
        margin-top:1.46%;
    }

    /* .logo img{        
        max-height: 100%;
        max-width: 100%;
        /* position:fixed; */
        /* margin-top: 1.46%;
        padding-left: 0.02%;   */
        /* left: 0.1%;
        top:1.46%; */
        /* float: left; */       
    /* }     */ 

    .trophy{
        /* height 152/1024   w:140/200 
            top:220/1024   left:30/200
        */
        max-height: 14.84%;
        /* max-width: 70%;*/
        max-width: auto;
        margin-left: 15%;
        margin-right: 15%;
        margin-top: 21.48%;        
    }

    /* .trophy img{
        /* height 70/152   w:70/140 
            top:237-220/152  left:68-30/140 right:
        */
        max-height: 46.05%;
        max-width: auto;
        /* max-width: 50%; */
        margin-top: 11.18%;

        /* margin-left: 20.14%;  
        margin-right: 27.14%;   */
    /* } */ */

    .text1{
        /* height: 35/152 width 128/140:
        top: 327-307/152 left: 36-30/140*/
        font: SourceHanSansSC-bold;
        color: #FFFFFF;
        max-height: 23.03%;
        /* width: 91.43%; */
        max-width: auto;
        margin-top: 13.15%;/*problem */
        margin-left: 2.28%;  
        margin-right: 2.28%; 
    }

    .profile{
        /* height: 152/1024 width:143/200: 
        top:  387/1024    left:  28/200 */
        max-height: 14.84%;
        /* width: 71.5%; */
        width:auto;
        margin-left: 14%;
        margin-right: 14%;
        margin-top: 37.79%;   

    }

    .profile img{
        /* height: 73/152 width:97/143: 
        top:  414-387/152    left:  50-28/143 */
        max-height: 48.03%;
        /* width: 67.83%; */
        width: auto;
        /* margin-left: 15.38%;
        margin-right: 15.38%; */
        /* margin-top: 17.76%;    */
    }

    .text2{
        /* height: 35/152 width 128/140:
        top: 327-307/152 left: 36-30/140*/
        font: SourceHanSansSC-bold;
        color: #FFFFFF;
        max-height: 23.03%;
        /* max-width: 91.43%; */
        max-width: auto;
        margin-top: 13.15%;/*problem */
        margin-left: 4.28%;  
        margin-right: 4.28%; 
        
    }



    .setting img{
        /* height: 73/152 width:97/143: 
        top:  414-387/152    left:  50-28/143 */
        max-height: 3.9%;
        max-width: 20%;
        /* margin-left: %; */
        /* margin-right:67%; */
        margin-top: 89%;
        vertical-align:text-bottom;

        /* text-align: left; */
        /* vertical-align:bottom; */
    }

    .setting a {
        /* height: 26/1024 width:60/200: 
        top:  967/1024    left:  93/200 */
        font:  SourceHanSansSC-bold;
        color: #FFFFFF;
        height: 2.54%;
        width: 30%;
        margin-left: 1%;      
        /* text-align: left; */
        
    }


</style>


