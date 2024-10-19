---
layout: default
title: Welcome
image: "/assets/images/banner.png"
---

<main id="home">
  <figure id="logo" title="TORQUE">
    {% include logo.html %}
  </figure>

  <a href="https://github.com/crashtech/torque-postgresql" target="_blank" id="pg" class="section">
    <figure>
      <img src="{{ '/assets/images/pg.svg' | relative_path }}" alt="TORQUE POSTGRESQL" />
    </figure>
    {% include title.html content="PostgreSQL" %}
    <div>
      <p>Seamless RoR interfaces to empower your PG queries</p>
      <p>Unlock these advanced features under the same DSL</p>
    </div>
  </a>

  <a href="https://github.com/crashtech/torque-admin" target="_blank" id="admin" class="section">
    <figure>
      <img src="{{ '/assets/images/admin.svg' | relative_path }}" alt="TORQUE ADMIN" />
    </figure>
    {% include title.html content="Admin" %}
    <div>
      <p>Combining the newest of HTML, with your favorite CSS library and fully dynamic with Hotwire</p>
    </div>
  </a>

  <a href="/ui" id="ui" class="section">
    <figure>
      <img src="{{ '/assets/images/ui.svg' | relative_path }}" alt="TORQUE UI" />
    </figure>
    {% include title.html content="UI" %}
    <div>
      <p><s>Build</s>, <s>SCSS</s>, <s>JavaScript</s></p>
      <p>Effortless design with plain CSS and clever usages of HTML</p>
    </div>
  </a>

  <footer>
    Created by
    <a href="https://github.com/crashtech" target="_blank">crashtech</a>
    - All rights reserved
  </footer>
</main>
