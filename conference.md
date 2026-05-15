---
title: "Graph theory: structure, surfaces, spectra"
description: "Shanghai Center for Mathematical Sciences"
layout: sub
filename: conference
---

<style>
.conf-page{display:flex;gap:36px;align-items:flex-start;margin-left:-35px}
.conf-sidebar{width:230px;flex-shrink:0}
.conf-sidebar a{display:block;margin-bottom:10px;padding:11px 14px;border:1px solid #cfcfcf;border-radius:6px;color:#159957;text-decoration:none;font-weight:600;background:#fff}
.conf-sidebar a:hover{background:#f3f8f5}
.conf-sidebar a.active{background:#159957;color:#fff;border-color:#159957}
.conf-content{flex:1;min-width:0}
.conf-section{display:none}
.conf-section.active{display:block}
@media(max-width:700px){.conf-page{display:block;margin-left:0}.conf-sidebar{width:auto;margin-bottom:25px}}
</style>

<div class="conf-page">

<div class="conf-sidebar">
<a href="#home" class="conf-link active" onclick="showSection('home',this)">Home</a>
<a href="#venue" class="conf-link" onclick="showSection('venue',this)">Conference Venue</a>
<a href="#speakers" class="conf-link" onclick="showSection('speakers',this)">Speakers</a>
<a href="#accommodation" class="conf-link" onclick="showSection('accommodation',this)">Accommodation</a>
<a href="#contact" class="conf-link" onclick="showSection('contact',this)">Contact</a>
</div>

<div class="conf-content">

<section id="home" class="conf-section active">

# Conference

## Shanghai, China

**Time:** Date–Date, 2026  
**City:** Shanghai, China  
**Organizer:** Shanghai Center for Mathematical Sciences  
**Host:** SCMS Combinatorics Seminar  

Welcome to the conference website.

</section>

<section id="venue" class="conf-section">

## Conference Venue

**Address:** Shanghai Center for Mathematical Sciences, Fudan University, Shanghai, China.

### Transportation

Please add detailed transportation information here, including directions from Pudong International Airport, Hongqiao Railway Station / Airport, and nearby metro stations.

</section>

<section id="speakers" class="conf-section">

## Speakers

- Speaker 1, University 1
- Speaker 2, University 2
- Speaker 3, University 3

</section>

<section id="accommodation" class="conf-section">

## Accommodation

Please add hotel and accommodation information here.

### Meals

Please add lunch, dinner, and coffee break information here.

</section>

<section id="contact" class="conf-section">

## Contact

For questions, please contact:

**Name:** Contact person  
**Email:** your-email@example.com

</section>

</div>
</div>

<script>
function showSection(id,el){
  document.querySelectorAll('.conf-section').forEach(s=>s.classList.remove('active'));
  document.querySelectorAll('.conf-link').forEach(a=>a.classList.remove('active'));
  document.getElementById(id).classList.add('active');
  el.classList.add('active');
}
</script>
