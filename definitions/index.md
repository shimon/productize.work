Definitions of product management:

<ul class="post-list">
  {% for page in site.pages %}
    {% if page.categories contains 'definition' %}
      <li><a href="{{page.url}}">{{page.title}}</a></li>
    {% endif %}
  {% endfor %}
</ul>

