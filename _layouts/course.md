---
layout: archive
---

<div class="flex-container">
    <p>{{page.description}}</p>
    <div class="tab-container">
      {% for item in page.items %}
        {% if item.active == true %}
            <span class="tab active">
                <a aria-current="page" href="/courses/{{page.parentPath}}/{{item.id}}">{{item.title}}</a>
            </span>
        {% else %}
            <span class="tab">
                <a aria-current="page" href="/courses/{{page.parentPath}}/{{item.id}}">{{item.title}}</a>
            </span>
        {% endif %}
      {% endfor %}
    </div>
    <div class="tab-content">{{page.courseDescription}}</div>
</div>