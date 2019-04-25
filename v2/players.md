---
layout: v2/default
title: DID(it) Playbook - Players
---
<div class="container mt-5">
  <!-- .row -->
  <div class="row">
    {% include v2/sidenav.html menu=site.data.players.sidenav %}
    <!-- .main -->
    <main role="main" class="col-md-9">
      <!-- hero -->
      <div class="jumbotron custom-primary-base mb-5">
        <div class="media">
          <img class="align-self-center custom-md-img mr-5" src="{{ site.baseurl }}/assets/img/v2/icons/{{ site.data.players.index.hero.image.filename }}" alt="{{ site.data.players.index.hero.image.alt }}">
          <div class="media-body">
            <h1>{{ site.data.players.index.hero.title }}</h1>
            <p class="lead">{{ site.data.players.index.hero.text }}</p>
          </div>
        </div>
      </div>
      <!-- /.hero -->
      <!-- .tiles -->
      <section class="mb-5">
        <div class="row">
          {% for item in site.data.players.index.roles %}
            <div class="col-md-3 mb-4">
              <div class="card">
                <img class="card-img-top" src="{{ site.baseurl }}/assets/img/v2/icons/{{ item.image.filename }}" alt="{{ item.image.alt }}">
                <div class="card-body">
                  <h5 class="card-title text-center">{{ item.name }}</h5>
                </div>
                <div class="card-footer text-center">
                  <a href="{{ site.baseurl }}/v2/players/{% include v2/to_url.html title=item.name %}">Read more <span class="sr-only">about {{ item.name }}</span></a>
                </div>
              </div>
            </div>
          {% endfor %}
        </div>
      </section>
      <!-- /.tiles -->
    </main>
    <!-- /.main -->
  </div>
  <!-- /.row -->
</div>