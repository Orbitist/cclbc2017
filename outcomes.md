---
layout: page
title: Outcomes
lead: ""
image: "img/drone_beach.jpg"
---
Between 2013–2016, the Chautauqua County Land Bank Corporation secured two separate grants from the NYS Office of Attorney General’s Community Revitalization Initiative Program totaling $2.86 million. This funding has been allocated primarily towards activities related to demolition, vacant lot disposition, acquisition of bank foreclosed properties, administration and marketing (Refer to attached 2016 Financial Audit Report).

Through the generous support of the county Legislature, the Chautauqua County Land Bank has also demonstrated its ability to address blight and stabilize neighborhoods across the county through its Sales 4 Rehab program and creative problem-solving. The Land Bank’s programs will impact vacancy rates and property values, most dramatically in the cities of Jamestown and Dunkirk, where 62 properties have entered the Sales 4 Rehab program and an additional 69 have been or are currently scheduled for demolition. Rural townships participate receive additional resources from the land bank in project management to help these smaller municipalities build capacity to effectively tackle blight in their communities. The Land Bank is shifting the paradigm on how the county deals with tax foreclosed properties by leveraging resources to tackle the glut of vacant, abandoned and condemned properties.

{% include maps/inventory.html %}

# 2016 Results of Acquisitions from the Legislature

{% include charts/property-types.html %}

_* Note: Demolitions were acquired from were acquired 2013-2016_

<div class="number">
  <div class="col-xs-2">
    <span class="fa fa-dollar number-icon"></span>
  </div>  
  <div class="col-xs-10">
    <div id="odometer" class="odometer reinvestment">000,000</div>
    <script>
      $(window).scroll(function() {
         var hT = $('.reinvestment').offset().top,
             hH = $('.reinvestment').outerHeight(),
             wH = $(window).height(),
             wS = $(this).scrollTop();
          console.log((hT-wH) , wS);
         if (wS > (hT+hH-wH)){
           setTimeout(function(){
               $('.reinvestment').html(431145);
           }, 100);
         }
      });
    </script>
  </div>
  <div class="number-caption">Private reinvestment commitments for Rehab renovations</div>
</div>


# 2016 Financial Overview

Statements of Financial Position:

{% include charts/financials.html %}

<hr>

<a href="team" class="btn btn-default btn-lg center-block">Our Team <i class="fa fa-arrow-right"></i></a>
