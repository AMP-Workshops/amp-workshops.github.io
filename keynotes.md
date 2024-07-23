---
title: Keynotes
layout: page
feature_image: "image12.jpg"
image_source: "<a href=\"https://pixabay.com/users/svitlanarom-1246047\" target=\"_blank\">SvitlanaRom</a>"
---


{% for keynote in site.data.keynotes %}
<div class="row col-md-12" markdown="1">

<h3><a id="{{keynote.title|slugify}}"></a>{{ keynote.title }}</h3>
<span class="glyphicon glyphicon-user" aria-hidden="true"></span> <span style="padding:.2em;" class="bg-info">*{{ keynote.speaker }}*</span> <span class="text-muted">@ {{ keynote.affiliation }}</span>{% if keynote.date %}
<br><span class="glyphicon glyphicon-calendar" aria-hidden="true"></span>
{{ keynote.date }}
{% endif %}
{% if keynote.link %}<br><span class="glyphicon glyphicon-bookmark" aria-hidden="true"></span> <a href="{{ keynote.link }}">Homepage</a>{% endif %}

<div class="col-md-7">
<h4>Abstract</h4>

<div style="margin-top:.5em; padding:1em;" class="bg-info text-justify" markdown="1">
{{ keynote.abstract }}
</div>
</div>

{% if keynote.bio %}
<div class="col-md-5">
  <h4>Speaker's Bio</h4>

  <div class="text-muted text-justify">
  {% if keynote.image %}<img class="img-thumbnail" style="margin:8px;max-width:120px;height:auto" align="left" src="/2024/assets/images/speakers/{{ keynote.image }}">{% endif %}
  {{ keynote.bio }}
  </div>
</div>
{% endif %}

{% if keynote.bios and keynote.bios.size > 0 %}
  {% if keynote.bios.size == 1 %}
<h4>Speaker's Bio</h4>
  {% else %}
<h4>Speaker Bios</h4>
  {% endif %}

  {% for bio in keynote.bios %}
  <div class="text-muted text-justify">
  {% if bio.image %}<img class="img-thumbnail" style="margin:8px;max-width:120px;height:auto" align="left" src="/2024/assets/images/speakers/{{ bio.image }}">{% endif %}
  {{ bio.text }}
  </div>
  {% endfor %}
{% endif %}

</div>
{% endfor %}

<div style="height:4em;" class="row col-md-12"></div>
