<h2 id="publications" style="margin: 2px 0px 0px;">Publications</h2>

<p style="margin: 2px 0px 0px; font-size:15px"> (* co-primary authors) </p>

<div class="publications">
<p style="margin: -25px 0px 10px; font-size:20px; font-weight: 1000; color:black">  Learning-Based Storage Systems </p>
<ul class="bibliography">
{% for link in site.data.publications.learning %}

<li style="margin: 0px 0px 5px;">
<div class="pub-row">
  <div class="col-sm-9" style="position: relative;padding-right: 0px;padding-left: 0px;">
      <div class="title"><a href="{{ link.pdf }}" style="font-size:19px">{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em>{{ link.conference }}</em> 
      </div>
      <font style="color:#9b2d15; font-weight:800">{{ link.notes }}</font>
    <div class="links">
      {% if link.pdf %} 
      <a href="{{ link.pdf }}" style="font-size:16px; color:black; text-decoration:underline">[Paper]</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" style="font-size:16px; color:black; text-decoration:underline">[Code]</a>
      {% endif %}
      {% if link.slides %} 
      <a href="{{ link.slides }}" style="font-size:16px; color:black; text-decoration:underline">[Slides]</a>
      {% endif %}
      {% if link.talk %} 
      <a href="{{ link.talk }}" style="font-size:16px; color:black; text-decoration:underline">[Talk]</a>
      {% endif %}
      
    </div>
  </div>
</div>
</li>

{% endfor %}

</ul>
</div>



<div class="publications">
<p style="margin: -20px 0px 10px; font-size:20px; font-weight: 1000; color:black">  Reliable and Secure Storage Systems  </p>
<ul class="bibliography">
{% for link in site.data.publications.reliable %}

<li style="margin: 0px 0px 5px;">
<div class="pub-row">
  <div class="col-sm-9" style="position: relative;padding-right: 0px;padding-left: 0px;">
      <div class="title"><a href="{{ link.pdf }}" style="font-size:19px">{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em>{{ link.conference }}</em> 
      </div>
      <font style="color:red">{{ link.notes }}</font>
    <div class="links">
      {% if link.pdf %} 
      <a href="{{ link.pdf }}" style="font-size:16px; color:black; text-decoration:underline">[Paper]</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" style="font-size:16px; color:black; text-decoration:underline">[Code]</a>
      {% endif %}
      {% if link.slides %} 
      <a href="{{ link.slides }}" style="font-size:16px; color:black; text-decoration:underline">[Slides]</a>
      {% endif %}
      {% if link.talk %} 
      <a href="{{ link.talk }}" style="font-size:16px; color:black; text-decoration:underline">[Talk]</a>
      {% endif %}
      
    </div>
  </div>
</div>
</li>

{% endfor %}

</ul>
</div>




<div class="publications">
<p style="margin: -20px 0px 10px; font-size:20px; font-weight: 1000; color:black;">  System Sustainability  </p>
<ul class="bibliography">
{% for link in site.data.publications.sustainable %}

<li style="margin: 0px 0px 5px;">
<div class="pub-row">
  <div class="col-sm-9" style="position: relative;padding-right: 0px;padding-left: 0px;">
      <div class="title"><a href="{{ link.pdf }}" style="font-size:19px">{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em>{{ link.conference }}</em> 
      </div>
      <font style="color:red">{{ link.notes }}</font>
    <div class="links">
      {% if link.pdf %} 
      <a href="{{ link.pdf }}" style="font-size:16px; color:black; text-decoration:underline">[Paper]</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" style="font-size:16px; color:black; text-decoration:underline">[Code]</a>
      {% endif %}
      {% if link.slides %} 
      <a href="{{ link.slides }}" style="font-size:16px; color:black; text-decoration:underline">[Slides]</a>
      {% endif %}
      {% if link.talk %} 
      <a href="{{ link.talk }}" style="font-size:16px; color:black; text-decoration:underline">[Talk]</a>
      {% endif %}
      
    </div>
  </div>
</div>
</li>

{% endfor %}

</ul>
</div>