---
layout: page
title: Writing User Stories
header: Writing User Stories
permalink: /writing-user-stories/
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
			<li>Short, simple descriptions of a feature</li>
		</ul>
        <h4 class="What" id="What">
            What Are We Doing
        </h4>
	<ul>
        <li>Writing a short description of something that users will do when they use the product</li>
        <li>Writing from the point of view of the user</li>
        <li>Exposing the WHY (value) to the organization</li>
        <li>Using the INVEST model</li>
        <ul>
           <li>Independent: Can be released without dependencies</li>
           <li>Negotiable: Ready for discussion and can be adapted based on team input</li>
           <li>Valuable: Delivers value to the end user</li>
           <li>Estimateable: Product Team can estimate it's relative complexity</li>
           <li>Small: As small as possible while still providing user value</li>
           <li>Testable: Contains acceptance criteria that can be readily validated</li>
        </ul>
	</ul>
        <h4 class="Why" id="Why">
            Why We Do It
        </h4>
            <ul>
                <li>Encourage building products that are prodviding value from the users perspective</li>
                <li>Describe work in a way that is precise enough to show value, but allows room to improve and iterate</li>
                <li>Promote the Product Team's understanding of WHY</li>
                <li>Generate discussion, collaboration, and iteration amongst the team</li>
                <li>Allow freedom to be immaginative and innovative</li>
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
            </ul>
        <h4 class="How" id="How">
            How We Do It
        </h4>
            <ul>
                <li>Document information on a Kanban board using the following techniques:</li>
                <ul>
                   <li>Title: Short, descriptive, and including the specific user/persona</li>
                   <ul><li>Example: <br> Ally should be able to schedule time for her lunch break</li></ul>
                   <li>Business Case: Who wants the functionality, why, and to what end</li>
                   <ul><li>Example: <br> As Ally, I want to be able to schedule time for my lunch break so that my colleagues know that I am not available during that time.</li></ul>
                   <li>Acceptance Test Criteria: Discrete conditions which can be tested to ensure the story is functional</li>
                   <ul><li>Example: <br> GIVEN I know the time for my lunch break <br> WHEN I select my schedule <br> and WHEN I add time for my lunch break <br> THEN my schedule is blocked from meetings during that time</li></ul>
                </ul>
                <li>Notes: Additional information for reference such as technical design or developer notes</li>
                <li>Resources: Designs, links, or other information relevant to delivering the story</li>
    </ul>
    </div>
    <div class="col-md-3">
        {% include design-plays.html %}
    </div>
</div>
