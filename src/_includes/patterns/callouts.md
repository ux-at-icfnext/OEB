{% if callout.type == "aside" %}
{% assign highlight = callout.highlight %}
<!-- Asides -->
<aside class="ontario-aside {{highlight}}">
    <h2 class="ontario-aside__title ontario-h5">{{ callout.title }}</h2>
    <p>{{ callout.content }}</p>
</aside>
{% else %}
<!-- Default -->
<div class="ontario-callout {{highlight}}">
    <h2 class="ontario-callout__title ontario-h5">{{ callout.title }}</h2>
    <p>{{ callout.content | markdownify }}</p>
</div>
{% endif %}


