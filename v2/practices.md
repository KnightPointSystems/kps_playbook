---
layout: v2/default
title: DID(it) Playbook - Practices
---
<div class="container mt-5">
  <!-- .row -->
  <div class="row">
    {% include v2/sidenav.html %}
    <!-- .main -->
    <main role="main" class="col-md-9">
      <!-- hero -->
      {% assign hero = site.data.practices.index.hero %}
      {% include v2/content/hero.html hero=hero %}
      <!-- /.hero -->
      <!-- .custom-list -->
      <section class="mb-5">
        <div class="custom-list">
          {% for section in site.data.practices.index.sections %}
            <div class="mb-5">
              <div class="d-flex align-items-center">
                <h3 class="font-weight-bold mr-2">{{ section.title }}</h3>
                <span class="badge badge-pill badge-primary mb-2">
                  <span class="h6 font-weight-light">{{ section.pill }}</span>
                </span>
              </div>
              <p class="mb-4">{{ section.text }}</p>
              <div class="row">
                {% include v2/content/related.html related=section.related hide_header=true%}
              </div>
            </div>
          {% endfor %}
        </div>
      </section>
      <!-- /.custom-list -->
    </main>
    <!-- /.main -->
  </div>
  <!-- /.row -->
</div>