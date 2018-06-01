---
layout: page
title: Sample Header 1
header: Template Header
permalink: /template-file/
---
<div class="row">
<div class="col-md-7">
  <div class="toc">
    <h3>Table of Contents</h3>
    <ul>
    <li><a href="#headings">Headings</a></li>
    <li><a href="#paragraph">Paragraph Text</a></li>
     <li><a href="#list">Bulleted List</a></li>
     <li><a href="#columns">Columns</a></li>
      <ul>
      <li><a href="#equalcolumns">Equal-Width Columns</a></li>
      <li><a href="#varyingcolumns">Varying Width Columns</a></li>
      </ul>
     <li><a href="#linksandimages">Links and Images</a></li>
     <ul>
     <li><a href="#links">Links</a></li>
     <li><a href="#images">Images</a></li>
     <ul>
     <li><a href="#linkedimage">Linked Image</a></li>
     </ul>
    </ul>
    </ul>
    </div>
    <p> Please make sure you are NOT working on the master branch. Create your own branch or use an existing branch to submit your content.</p>
<p> Please use this template if you want to create/edit a markdown file within this playbook. Select the icon that resembles a pencil to edit this file. Copy and paste this content and use it as a guide to create your own.</p>
<p> If you are creating a new file, please add the .md extension to the end of your filename. Make sure to include the heading above (layout, title, header, and permalink) at the top of your file. Leave the layout the same and change the title and header to match your content. Change the permalink to match the name of the file you will be creating. For example, this file is called "template-file.md" so the permalink is /template-file/ (the .md extension is not necessary). </p>

<p>If you are editing an existing file, omit the heading above and insert your content where you see fit.</p>
</div>
  <div class="col-md-1">
</div>
  <div class="col-md-4">
    <div class="sideLinks">
    <h2>Sample Resources/Plays</h2>
    <ul>
    <li><a href="#">Sample Play 1</a></li>
     <li><a href="#">Sample Play 2</a></li>
     <li><a href="#">Sample Play 3</a></li>
     <li><a href="#">Sample Play 4</a></li>
     <li><a href="#">Sample Play 5</a></li>
     <li><a href="#">Sample Play 6</a></li>
     <li><a href="#">Sample Play 7</a></li>
     <li><a href="#">Sample Play 8</a></li>
     <li><a href="#">Sample Play 9</a></li>
     <li><a href="#">Sample Play 10</a></li>
     <li><a href="#">Sample Play 11</a></li>
     <li><a href="#">Sample Play 12</a></li>
    </ul>
    </div>
  </div>
</div>

 
<h2 class="headings" id="headings">Headings</h2>
<h2>Sample Header 2</h2>
<h3>Sample Header 3</h3>
<h4>Sample Header 4</h4>
<h5>Sample Header 5</h5>
<h6>Sample Header 6</h6>

<div class="dropdown-divider"></div>


<h2 class="paragraph" id="paragraph">Paragraph Text</h2>
<p>This is a sample paragraph.</p>
<p>This is another sample paragraph.</p>

<div class="dropdown-divider"></div>


<h2 class="list" id="list">Bulleted List</h2>
<ul>
  <li>This is a list item</li>
  <li>This is a list item</li>
  <li>This is a list item</li>
</ul>

<div class="dropdown-divider"></div>
<h2 id="columns" class="columns">Columns</h2>
<h3 id="equalcolumns" class="equalcolumns">Equal-Width Columns</h3>
<div class="row"> 
<!-- Note: There are a total of 12 possible columns per row.
All column classes in a row should equal 12. This row has two columns with a width of 6. -->
<div class="col-md-6">
<h4>Column 1 of 2</h4>
<p>Column 1 of 2</p>
</div>
<div class="col-md-6">
<h4>Column 2 of 2</h4>
<p>Column 2 of 2</p>
</div>
</div>


<div class="row">
<div class="col-md-3">
<h4>Column 1 of 4</h4>
<p>Column 1 of 4</p>
</div>
<div class="col-md-3">
<h4>Column 2 of 4</h4>
<p>Column 2 of 4</p>
</div>
<div class="col-md-3">
<h4>Column 3 of 4</h4>
<p>Column 3 of 4</p>
</div>
<div class="col-md-3">
<h4>Column 4 of 4</h4>
<p>Column 4 of 4</p>
</div>
</div>

<h3 id="varyingcolumns" class="varyingcolumns">Varying Width Columns</h3>
<div class="row"> 
<!-- Note: There are a total of 12 possible columns per row.
All column classes in a row should equal 12. This row has two columns with a width of 6. -->
<div class="col-md-4">
<h4>Column 1 of 2</h4>
<p>Column 1 of 2</p>
</div>
<div class="col-md-8">
<h4>Column 2 of 2</h4>
<p>Column 2 of 2</p>
</div>
</div>

<div class="row">
<div class="col-md-3">
<h4>Column 1 of 3</h4>
<p>Column 1 of 3</p>
</div>
<div class="col-md-4">
<h4>Column 2 of 3</h4>
<p>Column 2 of 3</p>
</div>
<div class="col-md-5">
<h4>Column 3 of 3</h4>
<p>Column 3 of 3</p>
</div>
</div>


<div class="dropdown-divider"></div>

<div class="linksandimages" id="linksandimages">
<h2>Links and Images</h2>

<h3 class="links" id="links">Links</h3>
<p>This is an <a href="https://pages.git.uscis.dhs.gov/USCIS/didit_playbook/product-management/">external link</a> to the Product Management page (Follow this format whenever you need to reference an external link outside of the playbook.)
</p>

<p>This is an <a href="{{ site.baseurl }}/product-management">internal/local link</a> to the Product Management Page (Follow this format whenever you need to reference an internal link within the playbook.)
</p>

<h3 class="images" id="images">Images</h3>
<img src="../images/didit_logo.png" alt="did it logo" width="104"/>
<p>Note: All images must be uploaded to the "images" folder. Be sure to follow the exact path above ("../images/filename.png") and replace 'filename.png' with your image file in order for your image to display properly on the site. It may or may not show properly in this editor, but it will show on the live site.</p>

<h4 class="linkedimage" id="linkedimage">Linked Image</h4>
<p>Images can also be linked. This logo below links to the live playbook site's home page.</p>
<a href="https://pages.git.uscis.dhs.gov/USCIS/didit_playbook/">
<img src="../images/didit_logo.png" alt="did it logo" width="104"/>
</a>
</div>