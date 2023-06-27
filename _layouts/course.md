---
layout: archive
---

<div>
    <p>{{page.description}}</p>
    <ul class="nav nav-tabs">
      {% for item in page.items %}
        <li class="nav-item">
            {% if item.active == true %}
                <a class="nav-link active" aria-current="page" href="/courses/{{page.parentPath}}/{{item.id}}">{{item.title}}</a>
            {% else %}
                <a class="nav-link" aria-current="page" href="/courses/{{page.parentPath}}/{{item.id}}">{{item.title}}</a>
            {% endif %}
        </li>
      {% endfor %}
    </ul>
    <div>
        <p class="d-block">{{page.courseDescription}}</p>
    </div>
</div>