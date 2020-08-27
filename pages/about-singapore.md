---
layout: leftnav-page-content
title: About Singapore
permalink: /about-sg-test
breadcrumb: About

---

#something {
  display: none;
}

#something:target {
  display: block;
}

### **About**
<a href="#something">Show</a>
<div id="something">Bingo!</div>


<table>
    <div class="container">
    
            <div id="intro" class="myModal" >
                <div class="modal-window">
                    <h3 style="float:left;">Introduction</h3>

                    <div class="my-content" >
                        <p></p>
                        <p>
                            <ol class="parts" style="margin-top:2em;">
								<li>This self-assessment tool is designed to provide a preliminary assessment as to whether an individual or an entity qualifies for temporary relief under the COVID-19 (Temporary Measures) Act 2020 (the “<strong>Act</strong>”).</li>
								<li>It will take approximately <strong>5 minutes</strong> to complete the self-assessment.</li>
								<li>For more information on the relief measures under the Act, please refer to <a href="https://www.mlaw.gov.sg/covid19-relief" target="_blank">http://www.mlaw.gov.sg/covid19-relief.</a></li>                              
                            </ol>
                        </p>
                    </div>

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
