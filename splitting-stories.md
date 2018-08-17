---
layout: page
title: Splitting Stories
header: Splitting Stories
permalink: /splitting-stories/
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
		<li>Decomposing workinto manageable, measureable slices that provide value to the users</li>
		</ul>
        <h4 class="What" id="What">
            What Are We Doing
        </h4>
	<ul>
        <li>Breaking larger stories or epics into smaller stories that can be completed in less time</li>
        <li>Provide a framework to plan for releases</li>
	</ul>
        <h4 class="Why" id="Why">
            Why We Do It
        </h4>
            <ul>
                <li>To reduce complexity and not get lost in the details of a large feature</li>
                <li>To focus our development efforts</li>
                <li>To encourage more accurate sizing</li>
                <li>To identify features that can be delivered independently</li>
                <li>To speed up feedback loops</li>
	         </ul>
        <h4 class="Who" id="Who">
            Who Is Doing It
        </h4>
            <ul>
                <li>Facilitated By:
    	            <ul>
        	      <li>Product Managers</li>
    	            </ul>
                 </li>
                <li>Participants:
    	            <ul>
                      <li>Product Engineers</li>
                      <li>Product Designers</li>
                    </ul>    
                </li>
                <li>Audience:
    	            <ul>
                      <li>Product Owner Team</li>
                  </ul>    
                </li>
            </ul>
        <h4 class="How" id="How">
            How We Do It
        </h4>
            <ul>
               <li>During sizing meetings, if any story would be considered “large” decompose the story</li>
                <li>Break functions down into increments, and start by building the simplest piece</li>
                <li>Various techniques can be used to divide a large story into manageable chunks:</li>
                <ul>
                <li>CRUD (Create, Update, Delete) boundaries</li>
                <li>Create a separate story to meet a big or complex acceptance criteria</li>
                <li>Create separate stories for exception conditions</li>
                <li>Create separate stories for UI fields</li>
               <li> Create separate stories for data validation</li>
               </ul>
            </ul>
    </div>
    <div class="col-md-3">
        {% include design-plays.html %}
    </div>
</div>
