<style>
.buttonlist {
  display: flex;
  gap: 10px;
}

</style>
<div class="small-table">
<table style="width: 98%;">
<caption>Total number of household members: 4</caption>
{% for t in table %}
<tr><td>First Name</td><td>{{ t.fname }}</td></tr>
<tr><td>Last Name</td><td>{{ t.lname }}</td></tr>
<tr><td>Date of Birth</td><td>{{ t.date }}</td></tr>
<tr><td>Social Insurance Number</td><td>{{ t.soc }}</td></tr>
<tr><td>Account Holder</td><td>{{ t.account }}</td></tr>
<tr><td colspan="2" style="border-bottom: 2px #000 solid;" class="ontario-table-highlight">{% for b in t.btn %}<a href="#" >{{b.label}}</a> {% endfor %}</td></tr>
{% endfor %}
</table>
</div>


<div class="large-table ontario-table-div">
<table>
<caption>Total number of household members: 4</caption>
<thead>
<tr>
    <th>First Name</th><th>Last Name</th><th>Date of Birth<th>Social Insurance Number</th><th>Account Holder</th><th></th>
</tr>
</thead>
{% for t in table %}
<tr>
<td>{{t.fname}}</td><td>{{t.lname}}</td><td>{{t.date}}</td><td>{{t.soc}}</td><td>{{t.account}}</td>
<td class="buttonlist">{% for b in t.btn %}<a href="#" >{{b.label}}</a> {% endfor %}
</td>
</tr>
{% endfor %}
</table>
</div>