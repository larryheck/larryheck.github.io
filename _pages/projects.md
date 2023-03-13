---
layout: page
title: AVA Lab
permalink: /avalab/
description:  Georgia Tech's Artificial Intelligence Virtual Assistant (AVA) lab is focused on research behind next-generation virtual assistants.  We revisit assumptions regarding every aspect of modern AVAs - human-computer interaction design, single vs multimodal interactions, situated interactions over screens and mixed reality (AR/VR), task-oriented conversations to open-domain chit-chat to both, explicit to implicit (commonsense) knowledge-driven conversations, and higher level inference and reasoning.  
nav: true
nav_order: 1
display_categories: []
horizontal: false
---

  <article>
    <!--<input class="form-control" id="myInput" type="text" placeholder="Search.."/> <br/>-->

<h3 id="current-members">current members</h3>
<table class="table table-hover table-borderless text-left">
<tbody id="myTable">


<tr class="d-flex">
<td class="col-6" scope="row"><a href='https://scholar.google.com/citations?user=zaosyNUAAAAJ&hl=en'>Anirudh Sundar</a></td>
<td class="col-6">PhD student</td>
</tr>

<td class="col-6" scope="row"><a href='https://scholar.google.com/citations?user=DCMff-kAAAAJ&hl=en'>Benjamin Reichman</a></td>
<td class="col-6">PhD student</td>
</tr>

<td class="col-6" scope="row"><a href='https://scholar.google.com/citations?user=6Lk0excAAAAJ&hl=en'>Christopher Richardson</a></td>
<td class="col-6">PhD student</td>
</tr>

<td class="col-6" scope="row"><a href='https://www.researchgate.net/profile/Tamara-Zubatiy-2'>Tamara Zubatiy </a></td>
<td class="col-6">PhD student</td>
</tr>

<td class="col-6" scope="row"><a href='https://www.research.gatech.edu/ece-students-place-first-second-premier-microelectronics-undergraduate-research-competition'> Tyler Lizzo </a></td>
<td class="col-6">PhD student</td>
</tr>

<td class="col-6" scope="row"><a href='https://www.linkedin.com/in/prithwijit-chowdhury-067455152/?originalSubdomain=fr'>Prithwijit Chowdhury </a></td>
<td class="col-6">MS student</td>
</tr>

<td class="col-6" scope="row"><a href='https://scholar.google.com/citations?user=gPPkcwkAAAAJ&hl=en'>Venkata Sai Ritwik Kotra  </a></td>
<td class="col-6">MS student</td>
</tr>

</tbody>
</table>

<script>
  $(document).ready(function(){
      $("#myInput").on("keyup", function() {
        var value = $(this).val().toLowerCase();
        $("#myTable tr").filter(function() {
          if(($(this).text().toLowerCase().indexOf(value) > -1)){
            $(this).removeClass("hidehack").addClass("d-flex");
            return(1==1);
          }else{
            $(this).addClass("hidehack").removeClass("d-flex");
            return(0==1);
          };
        })
      });
    });
</script>

<!--<script>
  $(document).ready(function(){
      $("#myInput").on("keyup", function() {
	  var value = $(this).val().toLowerCase();
	  $("#myTable tr").filter(function() {
	      $(this).toggle($(this).text().toLowerCase().indexOf(value) > -1)
	  });
      });
  });
</script>-->

  </article>

</div>

    </div>

    <!-- Footer -->

    
<footer class="fixed-bottom">
  <div class="container mt-0">
    &copy; Copyright 2023 Larry P. Heck.
    
    
    
    Last updated: March 10, 2023.
    
  </div>
</footer>
