---
layout: archive
---

<div>
    <p>{{page.description}}</p>
    <ul class="tab-container">
      {% for item in page.items %}
        <li class="tab">
            {% if item.active == true %}
                <a class="active" aria-current="page" href="/courses/{{page.parentPath}}/{{item.id}}">{{item.title}}</a>
            {% else %}
                <a aria-current="page" href="/courses/{{page.parentPath}}/{{item.id}}">{{item.title}}</a>
            {% endif %}
        </li>
      {% endfor %}
    </ul>
    <div>
        <p>{{page.courseDescription}}</p>
    </div>
</div>