{% assign status = 1 %}

Contributions and Evaluation
----------------------------
AMP2024 seeks original contributions of the following types (maximum length):

- Full papers: research papers, industry experiences, or case studies (12 pages in LNCS format, incl. references, single-blinded).
- Short papers: research papers, industry experiences, or case studies (8 pages in LNCS format, incl. references, single-blinded).
- Extended Abstracts: tool presentations, position papers (2 pages, not part of the proceedings).

Papers should be formatted in Springer’s LNCS format and submitted through [EasyChair](https://easychair.org/conferences/?conf=icsoc2024).

In accordance with ICSOC 2024 publication guideline, we adopt a two-step process for the workshop proceedings. Online proceedings (available before the start of the workshop) will include all the accepted papers to AMP2024 and will be published online on the AMP 2024 web page (no proceedings). The accepted papers will be accessible only by the AMP2024. After the conference, we will organize post-proceedings of accepted full and short papers of workshops that will be published in a Springer LNCS volume (up to 12 pages).


## How to submit

Contributions should be formatted in [Springer LNCS](https://www.springer.com/computer/lncs?SGWID=0-164-2-791344-0) format
and submitted through EasyChair (link below)
to the track __[Workshop] AMP 2024: The 5th International Workshop on Agility with Microservices Programming__
as a PDF file interpretable by common PDF tools and printable in black and white on A4 paper.

{% case status -%}
{%- when 0 -%}
<p style="margin:2em;" class="text-center">
    <button style="padding:1em;" type="button" class="btn btn-primary btn-lg disabled">The submission system is not open yet</button>
</p>
{%- when 1 -%}
<p style="margin:2em;" class="text-center">
    <a href="https://easychair.org/conferences/?conf=icsoc2024"><button style="padding:1em;" type="button" class="btn btn-primary btn-lg">Submit</button></a>
</p>
{%- else -%}
<p style="margin:2em;" class="text-center">
    <button style="padding:1em;" type="button" class="btn btn-primary btn-lg disabled">The submission system is closed</button>
</p>
{%- endcase -%}
