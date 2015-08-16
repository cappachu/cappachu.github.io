---
layout: default
---
<div class="section">
    <div class="container">
        <div class="section-title">code</div>
        <div class="items">
          {% for project in site.code %}
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
    <div class="container">
        <div class="section-title">art</div>
        <div class="items">
            <div class="item">
                <div class="item-title">sculpture</div>
                <div class="item-description">some thing</div>
            </div>
            <div class="item">
                <div class="item-title">painting</div>
                <div class="item-description">some thing</div>
            </div>
        </div>
    </div>
</div>
