---
layout: wide
---


More code can be found at my <a href="https://github.com/markhuberty/">Github</a>.

		<div class="column span-10 append-2">
		### The Berkeley Political Science Compute Cluster 
        
		<p>I am the administrator for the
		Berkeley Political Science department's 
		18-node compute cluster. For more
		information on the cluster, go to the
		cluster's <a href="http://pscluster.berkeley.edu" >homepage</a>.
		</p>
		<p>
		The image below shows tests for the speed
		improvement of Jas Sekhon's GenMatch
		algorithm scaled across 1-17 nodes.
		</p>
        <p>
        <img src="./images/slurmTest.png" width="100%" >
        </p>
        
		</div>
		
		<div class="column span-10 last">

		  <h3 class="title">Balance statistics and plots from <tt>GenMatch()</tt></h3>
		  
		  <p>I've developed some code to produce tables and figures of balance statistics from the output of the
		  MatchBalance routine in the <a href="http://sekhon.berkeley.edu/matching" >Matching</a> package
		  for <a href="http://www.r-project.org"
		   >R</a>. My code builds on the work of <a
		  href="http://www-personal.umich.edu/~titiunik/"
		   >Rocio Titiunik</a> and <a href="http://cgibbons.berkeley.edu" >Charlie Gibbons</a>.
		  </p>
		  <p>
		  You can download the code <a
		  href="./files/balStatsPlot.R"
		   >here</a>. You can also clone the <tt>git</tt> repository <a href="http://github.com/markhuberty/balStatsPlot">here</a>.To use it, source it in your R
		  script via the <tt>source()</tt>
		  function. More documentation is included in
		  the comments section of the code.
		  </p>
		
		
		</div>

		<div class="column span-10 append-2">
		
		<h3>Installing <tt>gputools</tt>
		for R on a Macbook Pro</h3>
		<p>The gputools package for R provides GPU-enabled versions of common
		functions in R. As the documentation at the <a href="http://brainarray.mbni.med.umich.edu/Brainarray/Rgpgpu/" >gputools
		website</a> shows, significant reductions in compute time are
		possible. Installing the packages on a
			Macbook Pro requires a little fiddling, which
			I've documented here. The figure below shows
			that you can achieve some substantial gains in
			speed even with the rather wimpy GPU (nVidia
			9400m) that comes with the stock Macbook.
			  </p>
			  <p>
			  A full description of the installation is
			available <a href="gputools.html" >here</a>. 
			  </p>

			  
			  <img width="100%" src="./images/grangerResults.png" >

		</div>

