---
layout: home
title: Agility with Microservices Programming 2025
feature_image: "image25.jpg"
image_source: "<a href=\"https://pixabay.com/users/anis1969-6452442\" target=\"_blank\">Barcha</a>"
---

<ul class="nav nav-tabs nav-justified">
  <li role="presentation" class="active"><a href="#about">About</a></li>
  <li role="presentation" id="cfp_tab"><a href="#cfp">Call for Papers</a></li>
  <li role="presentation" id="submission_tab"><a href="#submission">Submission</a></li>
</ul>

<div class="tab-content">
<div role="tabpanel" class="tab-pane active" id="about">

{% include_relative include_md.html file="subpages/about.md" %}

{% include_relative include_md.html file="subpages/keynote_speakers.md" %}

{% include_relative include_md.html file="subpages/conference_theme.md" %}

</div>

<div role="tabpanel" class="tab-pane" id="cfp">

{% include_relative include_md.html file="subpages/cfp.md" %}

</div>

<div role="tabpanel" class="tab-pane" id="submission">

{% include_relative include_md.html file="subpages/submission.md" %}

</div>

</div>

<script>
$('.nav-tabs li a').click(function (e){e.preventDefault();$(this).tab('show');})
</script>