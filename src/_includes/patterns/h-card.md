<style>
.ontario-card__image-container, .ontario-card__heading {text-align: center;}
.ontario-card__image-container {background-color: #5F8129;}
.ontario-card__image{ max-width: 40px; height: auto; padding: 20px;}
</style>
<!-- Title card (default header with 4:3 aspect ratio) -->
<ul class="ontario-card__container ontario-card--cards-per-row-3">
{% for c in card %}
<li class="ontario-card ontario-card--default ontario-card--no-description ontario-card--position-vertical  ">
<div class="ontario-card__image-container">
<img class="ontario-card__image" src="/assets/imgs/{{ c.image }}" alt="">
</div>
<div class="ontario-card__text-container ontario-card--image-true">
<h2 class="ontario-card__heading">
<a href="{{c.link}}">
{{ c.title }}
</a>
</h2>
{% if c.content %}
<div class="ontario-card__description">
{{ c.content | markdownify }}
</div>
{% endif %}
</div>
</li>
{% endfor %}
</ul>