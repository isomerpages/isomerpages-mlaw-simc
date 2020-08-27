---
layout: leftnav-page-content
title: About Singapore
permalink: /about-sg-test
breadcrumb: About

---
<style>
#something {
  display: none;
}

#something:target {
  display: block;
}

  body {
    font-family: 'Open Sans', sans-serif;
    background: #FDFBF7;
    font-size: 1rem;
    color: #465661;
    padding-right: 0px !important;
    margin: 0;
}


.btn, .btn-sm, .btn-group-sm > .btn, .btn-lg, .btn-group-lg > .btn {
    border-radius: 0;
    cursor: pointer;
}

.btn-green {
    display: inline-block;
    cursor: pointer;
    text-align: center;
    text-decoration: none;
    outline: none;
    color: #fff;
    background-color: #4CAF50;
    border: none;
    border-radius: 15px;
    box-shadow: 0 9px #999;
    
  }
  
  .btn-green:hover {background-color: #3e8e41}
  
  .btn-green:active {
    background-color: #3e8e41;
    box-shadow: 0 5px #666;
    transform: translateY(4px);
  }

  .btn-red {
    display: inline-block;
    cursor: pointer;
    text-align: center;
    text-decoration: none;
    outline: none;
    color: #fff;
    background-color: #AB1E37;
    border: none;
    border-radius: 15px;
    box-shadow: 0 9px #999;
    
  }
  
  .btn-red:hover {background-color:rgb(190, 34, 62)}
  
  .btn-red:active {
    background-color: #FF6666;
    box-shadow: 0 5px #666;
    transform: translateY(4px);
  }


.myModal {

    display: none;
    margin-top: 150px;
    min-height: 500px;
    padding-bottom: 50px;

}


.close {
    position: absolute;
    top: 0;
    right: 0;
    color: rgba(0,0,0,0.3);
    height: 30px;
    width: 30px;
    font-size: 30px;
    line-height: 30px;
    text-align: center;
}

.close:hover,
.close:focus {
    color: #000000;
    cursor: pointer;
}

.open {
    display: block;
}


.parts li {
    padding-top: 1em;
}

.part1Button {
    font-size: larger;
    text-align: left;
    cursor: pointer;
    width:100%
}
.start {
    padding: 15px;
    font-size: 1em;
    background: rgb(46, 125, 216);
    color: #FFF;
    border: none;
    cursor: pointer;
    font-family: Lato,sans-serif;
}
.start2 {
    
    background: rgb(20, 55, 95);

}
.hover_bkgr_fricc{
  
    cursor:pointer;
    display:none;
    height:100%;
    position:fixed;
    text-align:center; 
    top:30px;
    width:50%;
    z-index:10000;

}

.measure-pic{
    float:right;
    padding-left:1em ;
    padding-bottom:1em ;
}

    

/* Portrait */
@media only screen 
  and (min-device-width: 320px) 
  and (max-device-width: 812px) 
 { 
    .popover-inner {
        width: 350px !important;
        max-width:500px !important;
     }
     .popover {
        width: 350px !important;
        max-width:500px !important;
     }
    .hover_bkgr_fricc{
  
        cursor:pointer;
        display:none;
        height:100%;
        position:fixed;
        /* text-align:center; */
        top:30px;
        width:100%;
        z-index:10000;
        overflow-x: auto;
    
    }

    .measure-pic{
        float:right;
        padding-left:1em ;
        display:none;
    }

}
</style>

### **About**
<a href="#something">Show</a>
<div id="something">Bingo!</div>


<table>
    <div class="container">
    
            <div id="intro" class="myModal" >
                <div class="modal-window">
                    <h3 style="float:left;">Introduction</h3>

                    Test

                </div>
                <button my-target1="decideLeftorRight" my-target2="decideLeftorRight" my-toggle="modal" style="float:right;cursor: pointer;" class="btn-red assessment">Begin Assessment Tool</button>
                <br><br>
            </div>
	    
	    <div id="decideLeftorRight" class="myModal">
                <div class="modal-window">
                    <a href="#"  class="back">Back to previous step...</a>
                    <h2>Next Step ...</h2>
                    <div class="my-content">
                        <p class="question">Choose one of the following</p>
                        <p>
                            <button style="height:auto;" my-target1="rightTrack" my-target2="leftTrack" my-toggle="modal" class="btn-red fullwidth" userType="company">I am / my business is seeking temporary relief under the Act.</button>
                            <br><br>
                            <button style="height:auto;" my-target1="rightTrack" my-target2="rightTrack" my-toggle="modal" class="btn-red fullwidth" userType="user">A party with whom I / my business has an existing contract is seeking temporary relief under the Act <span style="text-decoration: underline;font-weight: bold;">against</span> me / my business.</button>
                        </p>
                    </div>

                </div>
            </div>   
	    
        </div>    
            </table>
