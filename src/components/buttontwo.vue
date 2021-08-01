<template>
    <div id="buttontwo">

        <div class="row">
            <div class="column">
                
                 <img src="https://i.pinimg.com/originals/ab/eb/a7/abeba7dd5558c9de97856d23cc549d52.png" alt="Snow" style="width:100%">
                 
                  <div id="btnn"><buttonone/></div> 
                  <div id="btnnn"><buttonthree /></div>
                  <div id="coomentt"><comment /></div>
            </div>

            <div class="column">
                <img src="https://lh3.googleusercontent.com/proxy/Y9Ra3T_yRAT63bmqL3CawEI3174sPiyPs_X68ImVwBw1fp0OFj_5k6fJVEDltuT-bZB7VGfhUT_rc6qjQrtzD2buftYInijL1YVsnEeB6K2FxTnmgg0jgb6eWiTklkWaNqWdL4Pf-KH0DTBZL8_2jpNnu3_p" alt="Forest" style="width:100%">
                
                <div id="btnn"><buttonone/></div>
                <div id="btnnn"><buttonthree /></div>
                <div id="coomentt"><comment /></div>
                
            </div>
            <div class="column">
                 <img src="https://wallpaperaccess.com/full/2082795.jpg" alt="Mountains" style="width:100%">
                 
                  <div id="btnn"><buttonone/></div>
                  <div id="btnnn"><buttonthree /></div>
                  <div id="coomentt"><comment /></div>
            </div>
            <div class="column">
                <img src="https://cdn.dribbble.com/users/402053/screenshots/2792314/dribbble-realmadrid.newlogo.jpg" alt="Snow" style="width:100%">
                 
                 <div id="btnn"><buttonone/></div>
                 <div id="btnnn"><buttonthree /></div>
                 <div id="coomentt"><comment /></div>
            </div>
            <div class="column">
                 <img src="https://besthqwallpapers.com/Uploads/8-5-2018/51696/thumb2-persepolis-fc-4k-silk-texture-logo-emblem.jpg" alt="Mountains" style="width:100%">
                 
                     <div id="btnn"><buttonone/></div>
                     <div id="btnnn"><buttonthree /></div>
                     <div id="coomentt"><comment /></div>
                     
                 
                 
                  
            </div>
             <div class="column">
                 <img src="https://media.mehrnews.com/d/2020/10/10/3/3575971.jpg" alt="Mountains" style="width:100%">
                  <div id="btnn"><buttonone/></div>
                  <div id="btnnn"><buttonthree /></div>
                  <div id="coomentt"><comment /></div>
            </div>
        </div>
        <div id="foot"><footerr /></div>
    </div>
</template>
<script>
import buttonone from './buttonone'
import buttonthree from './buttonthree'
import comment from './comment'
import footerr from './footerr'




export default {
    name : 'buttontwo',
    components:{
        buttonone,
        buttonthree,
        comment,
        footerr
        
       
        
        
    }
  
}


</script>
<style>
img{
    width: 250px;
    height: 250px;
   float: left;
   display: inline;
}
.column {
  float: left;
  width: 33.33%;
  padding: 2px;
  margin: 0px;
}


.row::after {
  content: "";
  clear: both;
  display: table;
}
button{
        width: 100px;
       height: 50px;
       margin-top: 10px;
       float: right;
}

#home{
    width: 1300px;
    margin: auto;
}
#btnn{
    margin-left: 30px;

}
#commentt{
    margin-top: 10px;
}
button, input {
    overflow: visible;
    margin-top: 24px;
    margin-left: 10px;
    padding: 11px;
    border: 2px solid black;
}
#foot{
    background-color: black;
    margin-top: 10px;
}
</style>