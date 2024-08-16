<style>
.ontario-dropdown{background-color:#fff;background-image:url("/assets/imgs/ontario-material-dropdown-arrow-48px.svg");background-position:right .5rem center;background-repeat:no-repeat;background-size:2rem;padding-right:2.25rem;cursor:pointer}.ontario-dropdown::-ms-expand{display:none}.ontario-dropdown option{font-weight:normal}
</style>


<div class="ontario-form-group">
    <label class="ontario-label" for="dropdown-list-example">
        {{ select.label }}<span class="ontario-label__flag">({{ select.required }})</span>
    </label>
    <select class="ontario-input ontario-dropdown" id="dropdown-list-example" name="dropdown-list-example">
      {% for s in select.list %}
        <option value="">{{ s }}</option>
      {% endfor %}
    </select>
</div>
