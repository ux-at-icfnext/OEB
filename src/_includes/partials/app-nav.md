<style>
.appnav { padding: 20px;}
.appnav p { margin: 16px; padding: 0;}
.appnav a.disabled {
  color: #000;
  text-decoration: none
}
@media (min-width: 800px) {
  .appnav { 
    display: flex; 
    justify-content: space-evenly;
  }
}
</style>


<div class="appnav">
<p><a href ="/app" {% if page.url == "/app/" %} class="disabled" {% endif %}>1 - Utility Account Information </a></p>
<p><a href ="/app2" {% if page.url == "/app2/" %} class="disabled" {% endif %} >2 - Additional Information </a> </p> 
<p><a href ="/app3" {% if page.url == "/app3/" %} class="disabled" {% endif %} >3 - People In Your House </a> </p>
<p><a href ="/app4" {% if page.url == "/app4/" %} class="disabled" {% endif %} >4 - Review & Submit </a>  </p>
</div>




