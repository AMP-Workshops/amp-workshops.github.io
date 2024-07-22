---
layout: page
title: Call for Papers and Paper Submission
feature_image: "image11.jpg"
image_source: "<a href=\"https://pixabay.com/users/jonny_joka-4913008\" target=\"_blank\">Jonny_Joka</a>"
---

{% assign status = 2 %}

## Contributions and evaluation

The third edition of AMP aims to continue the success of its previous editions at [XP 2020](https://amp.fe.up.pt/2020/) and [XP 2021](https://amp.fe.up.pt/2021/) in collecting original work on the science and engineering of **Microservices Programming** using **Agile** principles and practices and/or with the goal of supporting **Agility**. The topics include (but are not limited to):

- Using microservices to enable an evolutive and agile architecture.
- Software engineering methods and tools for microservices.
- Patterns for microservices design and development.
- Operations practises for microservices and DevOps support.
- Impact of microservices’ usage on agile teams and processes.
- Programming languages and techniques for microservices.
- Combining microservices with other architectural styles.
- Achieving software qualities, e.g., security, maintainability, and deployability.
- Metrics and software analytics in microservices architectures.
- Verification of microservice architectures.
- Test-driven approaches and testing in microservices development.
- Refactoring in the context of microservices architectures.
- Empirical studies on microservices.
- Experience reports on microservice adoption and teaching.

**Submissions based on empirical studies conducted in industry-academia collaboration are particularly encouraged.**

AMP 2022 seeks original contributions of the following types:

- _Full Papers:_ research papers, industry case studies (from 6 to 8 pages, including references)
- _Extended Abstracts:_ tool presentations, position papers (2 pages, including references)

Submissions must be in English.

Peer groups with expertise in the workshop focus area will review submissions. The [Program Committee](/2022/committees/) will select full papers and extended abstracts for presentation at the workshop. Revised and selected contributions will be included in a separate volume of the XP 2022 conference proceedings published by [Springer LNBIP](https://www.springer.com/computer/lncs?SGWID=0-164-2-791344-0). An author must present the paper/abstract.

AMP 2022 follows a single-blind review process. The authors may publish technical reports and preprints of contributions under review or accepted at AMP.
Substantial overlap with works submitted or accepted at other venues is ground for rejection for full papers.

## Important Dates
- ~~Abstract submission deadline: [**April 1st, 2022 (AoE)**](https://www.timeanddate.com/worldclock/fixedtime.html?msg=AMP+2022+abstract+submission+deadline&iso=2022-04-01&p1=3400)~~
- ~~Paper submission deadline : [**April 8th, 2022 (AoE)**](https://www.timeanddate.com/worldclock/fixedtime.html?msg=AMP+2022+paper+submission+deadline&iso=2022-04-08&p1=3400)~~ <!--(submission is also possible for papers without a previously submitted abstract)-->
- ~~Notification of acceptance: [**April 29th, 2022 (AoE)**](https://www.timeanddate.com/worldclock/fixedtime.html?msg=AMP+2022+notification+of+acceptance&iso=2022-04-29&p1=3400)~~
- Camera-ready due: TBD

## How to submit

Contributions should be formatted in [Springer LNBIP](https://www.springer.com/computer/lncs?SGWID=0-164-2-791344-0) format
and submitted through EasyChair (link below)
to the track __Research WS - Agility with Microservices Programming__
as a PDF file interpretable by common PDF tools and printable in black and white on A4 paper.
{% case status -%}
{%- when 0 -%}
<p style="margin:2em;" class="text-center">
    <button style="padding:1em;" type="button" class="btn btn-primary btn-lg disabled">The submission system is not open yet</button>
</p>
{%- when 1 -%}
<p style="margin:2em;" class="text-center">
    <a href="https://easychair.org/conferences/?conf=xp2022"><button style="padding:1em;" type="button" class="btn btn-primary btn-lg">Submit</button></a>
</p>
{%- else -%}
<p style="margin:2em;" class="text-center">
    <button style="padding:1em;" type="button" class="btn btn-primary btn-lg disabled">The submission system is closed</button>
</p>
{%- endcase -%}

<div class="alert alert-info hidden-print" role="alert">
<span class="glyphicon glyphicon-info-sign"></span> The call is also available as a text file <a href="{{ "/cfp.txt" | relative_url }}">here</a>.
</div>
