<ul class="ontario-card__container ontario-card--cards-per-row-2">
{% for c in card %}
<li class="ontario-card ontario-card--image--one-third   ontario-card--position-horizontal ontario-card--position-horizontal__image-left">
<div class="ontario-card__image-container">
<img class="" src="/assets/imgs/{{ c.image }}" alt="card component image">
</div>
<div class="ontario-card__text-container ontario-card--image-true">
<h2 class="ontario-card__heading">
<a href="#">
{{ c.title }}
</a>
</h2>
{% if c.content %}
<div class="ontario-card__description">
{{ c.content }}
</div>
{% endif %}
</div>
</li>
{% endfor %}
</ul>