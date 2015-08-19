---
layout: default
---
<div class="container">
  <div class="items">
    {% for project in site.wires | sort:'identifier' %}
    <div class="item">
      <div class="prompt"> >> &nbsp;&nbsp;</div>
      <div class="item-title">
        <a href="{{ project.github_url }}">{{ project.title }}</a>
      </div>
      <div class="item-brief">
        {{ project.brief }}
      </div>
      <div class="item-content">
        {{ project.content }}
      </div>
    </div>
    {% endfor %}
  </div>
</div>

