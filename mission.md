---
layout: page
title: "Our Mission"
lead: "We're the Chautauqua County Land Bank Corporation.<br/>It's nice to meet you!"
image: "img/man_demo.jpg"
---
{General About Video Will Go here}

Control and manage strategically selected dilapidated and abandoned residential and commercial properties acquired through the County tax foreclosure process, bank foreclosures and/or donations, and facilitate solutions aimed at stabilizing neighborhoods, encouraging private investment, and improving the quality of life throughout Chautauqua County.

<div class="number">
  <div class="col-xs-2">
    <span class="fa fa-dollar number-icon"></span>
  </div>  
  <div class="col-xs-10">
    <div id="odometer" class="odometer public-investment">0.00</div>
    <script>
      $(window).scroll(function() {
         var hT = $('.public-investment').offset().top,
             hH = $('.public-investment').outerHeight(),
             wH = $(window).height(),
             wS = $(this).scrollTop();
          console.log((hT-wH) , wS);
         if (wS > (hT+hH-wH)){
           setTimeout(function(){
               $('.public-investment').html(2.86);
           }, 100);
         }
      });
    </script>
  </div>
  <div class="number-caption">Million dollars in public grant funding</div>
</div>

# Overview

The Chautauqua County Land Bank Corporation (CCLBC) was designated as one of the first five land banks in NYS, by authority of the New York State Land Bank Act, in 2012. By 2016, the Land Bank secured over $2.86 million dollars in public grant funding, and leveraged over $1.65 million in private investment in the interventions of more than 173 vacant or abandoned properties in the county.

<div class="number">
  <div class="col-xs-2">
    <span class="fa fa-dollar number-icon"></span>
  </div>  
  <div class="col-xs-10">
    <div id="odometer" class="odometer private-investment">0.00</div>
    <script>
      $(window).scroll(function() {
         var hT = $('.private-investment').offset().top,
             hH = $('.private-investment').outerHeight(),
             wH = $(window).height(),
             wS = $(this).scrollTop();
          console.log((hT-wH) , wS);
         if (wS > (hT+hH-wH)){
           setTimeout(function(){
               $('.private-investment').html(1.65);
           }, 100);
         }
      });
    </script>
  </div>
  <div class="number-caption">Million in private investment</div>
</div>

<hr>

<a href="problem" target="blank" class="btn btn-default btn-lg center-block">The Problem <i class="fa fa-arrow-right"></i></a>
