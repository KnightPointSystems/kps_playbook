---
layout: default
title: KPS Playbook - Players
---
<div class="container mt-5">
  <!-- .row -->
  <div class="row">
    {% include sidenav.html %}
    <!-- .main -->
    <main role="main" class="col-md-9">
      <!-- hero -->
      {% assign hero = site.data.players.index.hero %}
      {% include content/hero.html hero=hero %}
      <!-- /.hero -->
      <!-- .tiles -->
      {% assign related = site.data.players.index.roles %}
      {% include content/related.html related=related hide_header=true %}
      <!-- /.tiles -->
    </main>
    <!-- /.main -->
  </div>
  <!-- /.row -->
</div>