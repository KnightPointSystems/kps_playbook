---
layout: page
title: Writing Acceptance Criteria
header: Writing Acceptance Criteria
permalink: /writing-acceptance-criteria/
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
		<li>What must be done to complete a user story</li>
		</ul>
        <h4 class="What" id="What">
            What Are We Doing
        </h4>
	<ul>
        <li>Detailing the criteria that the user story must satisfy to be accepted by a user</li>
	<ul>
	   <li>The criteria should be independent of the implementation, and discuss WHAT to expect, and not HOW to implement the functionality</li>
	 </ul>
	 <li>Defining what “done” means with regards to completing the user story</li>
	 <li>Creating a script for testing</li>
	 <li>Writing in plain language that is easy to understand</li>
	</ul>
        <h4 class="Why" id="Why">
            Why We Do It
        </h4>
            <ul>
                <li>To provide guidance to the development team and testers</li>
		<li>To evaluate if the user story is too big</li>
		<ul>
		   <li>If there are too many “ands” in the acceptance criteria, it means that the user story is probably too big and needs to be decomposed further</li>
		 </ul>
		<li>To deliver small, focused, increments of work that can be easily understood by a broad audience</li>
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
                      <li>Product Owner Team</li>
                  </ul>    
                </li>
            </ul>
        <h4 class="How" id="How">
            How We Do It
        </h4>
            <ul>
               <li>Follow the Gherkin model: GIVEN [necessary context] WHEN [action] THEN [reaction]</li>
	       <li>Example:</li>
	       <ul>
	           <li>Scenario: User adds item to cart</li>
	       <ul>
	       <li>Given I'm a logged-in User</li>
  	       <li>When I go to the Item page</li>
  	       <li>And I click "Add item to cart"</li>
  	       <li>Then the quantity of items in my cart should go up</li>
 	 	<li>And my subtotal should increment</li>
 		<li>And the warehouse inventory should decrement</li>
		</ul>
		</ul>
            </ul>
    </div>
    <div class="col-md-3">
        {% include design-plays.html %}
    </div>
</div>
