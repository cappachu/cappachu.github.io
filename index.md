---
layout: default
---
<div class="section">
  <div class="anchor" id="code"></div>
  <div class="container">
    <div class="section-title">
      <div class="prompt">>></div>
       code
    </div>
    <div class="items">
      {% for project in site.code | sort:'identifier' %}
      <div class="item">
        <div class="item-title">
          <a href="{{ project.github_url }}">{{ project.title }}</a>
        </div>
        <div class="item-brief">
          {{ project.brief }}
        </div>
        <div class="item-description">
          {{ project.content }}
        </div>
      </div>
      {% endfor %}
    </div>
  </div>
</div>

<div class="section">
  <div class="anchor" id="art"></div>
  <div class="container">
    <div class="section-title">
      <div class="prompt">>></div>
        art
    </div>
    <div class="items">
      {% for i in (1..20) %}
      <div class="item">
        <div class="item-title"><a href="#">title</a></div>
        <div class="item-brief">brief</div>
        <div class="item-description">a description</div>
      </div>
      {% endfor %}
    </div>
  </div>
</div>
