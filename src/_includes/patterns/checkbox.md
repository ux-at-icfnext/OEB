<div class="ontario-form-group">
<fieldset class="ontario-fieldset">
<legend class="ontario-fieldset__legend">
{{ checkbox.label }}<span class="ontario-label__flag"> {% if checkbox.required %}({{ checkbox.required }}){% endif %}</span>
</legend>
<div class="ontario-checkboxes">
{% for check in checkbox.list %}
<div class="ontario-checkboxes__item">
<input class="ontario-checkboxes__input" id="checkbox-option-1" name="options" type="checkbox" value="option-1">
<label class="ontario-checkboxes__label" for="checkbox-option-1">
{{ check }}
</label>
</div>
{% endfor %}
</div>
</fieldset>
</div>