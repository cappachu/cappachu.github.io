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
        <div class="item-content">
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
    <!-- <img src="/images/300px-Codanda-appachu-glove_board.jpg">  -->
    <!-- <img src="/images/400px-Codanda-appachu-chord_key_map.jpg"> -->
    <!-- <img src="/images/mario_board.jpeg"> -->
    <!-- <img src="/images/mario_figurine.jpeg"> -->
  </div>
</div>
