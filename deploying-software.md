---
layout: page
title: Deploying Software
header: Deploying Software
permalink: /deploying-software/
---
<div class="row">
    <div class="col-md-3">
        {% include product-plays.html %}
    </div>
    <div class="col-md-6">
        <h4 class="Definition" id="Definition">
            Definition
        </h4>
		<ul>
		<li>Deploying features that provide value early and often</li>
		</ul>
        <h4 class="What" id="What">
            What Are We Doing
        </h4>
	<ul>
        <li>Making updated software available to users</li>
        <li>Progressing towards the Strategic Objective</li>
	</ul>
        <h4 class="Why" id="Why">
            Why We Do It
        </h4>
            <ul>
                <li>To make software available to users quickly</li>
                <li>To reduce risk</li>
                <li>To deliver value</li>
	         </ul>
        <h4 class="Who" id="Who">
            Who Is Doing It
        </h4>
            <ul>
                <li>Facilitated By:
    	            <ul>
        	      <li>Product Manager</li>
    	            </ul>
                 </li>
                <li>Participants:
    	            <ul>
                      <li>Product Team</li>
                    </ul>    
                </li>
                <li>Audience:
    	            <ul>
                      <li>Product Stakeholders</li>
                  </ul>    
                </li>
            </ul>
        <h4 class="How" id="How">
            How We Do It
        </h4>
            <ul>
               <li>Sort stories into affinity clusters for development</li>
               <li>Make sure master branch is ready to deploy</li>
               <ul><li>Product Manager asks the team</li></ul>
               <li>Push update master to production</li>
               <ul><li>Kick off the build pipeline (ex Jenkins job) to push master to production</li></ul>
               <li>Smoke test the build</li>
               <ul><li>Check for any errors in production</li></ul>
               <li>Send a deployment notification to stakeholder</li>
               <ul><li>Compile a brief bulleted list of release notes written in plain language outlining the value the team has delivered</li></ul>
            </ul>
    </div>
    <div class="col-md-3">
        {% include design-plays.html %}
    </div>
</div>
