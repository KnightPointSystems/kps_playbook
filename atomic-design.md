---
layout: page
title: Atomic Design
header: Atomic Design
permalink: /atomic-design/
---
<div class="row">
    <div class="col-md-3">
        {% include product-plays.html %}
    </div>
    <div class="col-md-6">
    <h4 class="Definition" id="Definition">
            Definition of Atomic Design
        </h4>
        <ul>
            <li>
                A design system that breaks down UI elements to the “atomic” level
            </li>
        </ul>
        <h4 class="What" id="What">
            What Are We Doing
        </h4>
            <ul>
                <li>
                   A design system that breaks down UI elements to the “atomic” level
                </li>
            </ul>
        <h4 class="Why" id="Why">
            Why We Do It
        </h4>
            <ul>
                <li>
                   Achieves consistency in design and development
                </li>
                <li>
                   Allows for quick style updating and code re-use
                </li>
            </ul>
        <h4 class="Who" id="Who">
            Who Is Doing It
        </h4>
        <ul>
            <li>Facilitated By:
                <ul>
                    <li>Product Designer</li>
                </ul>
            </li>
        </ul>
<h4 class="How" id="How">
    How We Do It
</h4>
<ul>
    <li>Name UI elements at a basic level, like .atom_form_label which would be the text label of an input field</li>
    <li>Input fields could be .atom_form_input_text</li>
    <li>Do the same for any error messaging, and any other elements</li>
    <li>Group the atomic elements together into a molecule named .molecule_form_text_input</li>
    <li>Create the elements as nested symbols in Sketch, so they are technology agnostic for various apps that might use different frameworks</li>
</ul>
    </div>
    <div class="col-md-3">
        {% include design-plays.html %}
    </div>
</div>
