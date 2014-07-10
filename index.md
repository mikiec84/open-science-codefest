---
layout: index
title: Open Science Codefest 2014
---
{% include JB/setup %}
<p id="intro">
The Open Science Codefest will gather researchers from ecology, biodiversity science, and other earth and environmental sciences to collaborate on code projects of mutual interest. Many people are developing software packages for use in the environmental and earth sciences, but there are only rare opportunities for collaboration on these works. We are inspired by hack-a-thon sessions at major computing conferences around the world, and think that major advances in science can occur when people with shared interests gather and hammer out new solutions.
</p>

<div class="filler">
	<a class="lightbox-41817591638969"><img src="{{ BASE_PATH }}assets/img/conference.jpg" /></a>
</div>

<div class="container-fluid featured over-image grid" id="design">
	<h2>Design</h2>
	<p>Collaborate with others to conceive, extend, and design software for open science.</p>
</div>
<div class="container-fluid featured grid" id="analyze">
	<h2>Analyze</h2>
    <p>Integrate, analyze, and model scientific data to solve pressing environmental issues.</p>
</div>
<div class="container-fluid featured grid" id="code">
	<h2>Code</h2>
    <p>Put ideas into reality in real time. Prototype open source software for science with others.</p>
</div>
<div class="clearfix"></div>
<div class="container-fluid" id="sessions">
	<div class="title" id="sessions">
	  Sessions
	</div> 
	
	<p>The Codefest is <a href="http://en.wikipedia.org/wiki/Unconference">yours to customize, organize, and create</a>, with the goal of allowing groups with shared interests to connect organically and to work on projects of mutual interest. The conference will be organized to stimulate productivity and community building, while giving ample opportunities for collaborative coding and design sessions, <a href="http://en.wikipedia.org/wiki/Lightning_talk">ignite talks</a> that promote communication among participants as activities unfold, and birds-of-a-feather discussions.</p>
	
	  <ul class="posts">
	    {% for post in site.posts limit:15 %}
	      <li class="posts-title">
		      	<a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
		      	<span class="label">{{ post.category }}</span>
		      	<span class="post-date">Added {{ post.date | date_to_string }}</span>
	      </li>
	    {% endfor %}
	  </ul>
</div>
<div class="container-fluid labels">
	<div class="title" id="categories">
	  Session Categories
	</div> 
	<div>
	    <p>Sessions are categorized into the type of activity involved, and we expect sessions in Data Science, Coding, Design, Discussion, Lightning talks, and others.  We envision sessions covering data science, data management, research data analysis, software for modeling, model coupling, and data-model integration.  Whether you are into <a href="http://r-project.org">R</a>, <a href="http://python.org">scientific python</a>, or any other language, we expect many Code for Science hacks, where people can conceive of and prototype new science software, extend existing systems, and design new packages. The current types of activities currently are:
	    <ul class="tag_box inline">
	      {% assign categories_list = site.categories %}
	      {% include JB/categories_list %}
	    </ul>
	</div>
</div>
<div class="container-fluid" id="sponsors">
	<div class="title">
	  Sponsors
	</div> 
	<div class="container-fluid">
	  <div class="row-fluid">
	    <div class="span3 text-box">
	      <p>
	      	<img src="{{ BASE_PATH }}assets/img/renci.jpg" class="renci"/><br/>
	      	<a href="http://renci.org/">RENCI</a>
	      </p>
	    </div>
	    <div class="span3 text-box">
	      <p>
	          <img src="{{ BASE_PATH }}assets/img/nceas.png" class="nceas" /><br />
	          <a href="http://www.nceas.ucsb.edu">NCEAS</a>
	      </p>
	    </div>
	   <div class="span3 text-box">
	      <p>
	       <img src="{{ BASE_PATH }}assets/img/nsf.gif"  class="nsf"/><br />
	          <a href="http://www.nsf.gov/">NSF</a><br/>
	          <span class="tiny">Acknowledgement: This material is based upon work supported by the National Science Foundation under Grant Number 1216894</span>
	      </p>
	    </div>
	    <div class="span3 text-box">
	    
	      <p>
	      <a href="http://isees.nceas.ucsb.edu">ISEES</a><br />
	      <a href="">WSSI</a>
	      </p>
	    </div>
	  </div>
	</div>
</div>
