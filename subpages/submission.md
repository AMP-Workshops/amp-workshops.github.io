{% assign status = 1 %}

Contributions and Evaluation
----------------------------
AMP2024 seeks original contributions of the following types (maximum length):

- Full papers: research papers, industry experiences, or case studies (12 pages in LNCS format, incl. references, single-blinded).
- Short papers: research papers, industry experiences, or case studies (8 pages in LNCS format, incl. references, single-blinded).
- Extended Abstracts: tool presentations, position papers (2 pages, not part of the proceedings).

Papers should be formatted in Springer’s LNCS format and submitted through [EasyChair](https://easychair.org/conferences/?conf=amp2024).

In accordance with [ICSOC 2024](https://icsoc2024.redcad.tn/call-workshops.html) publication guideline for workshops, accepted papers will be published in the post-proceedings.

## How to submit

Contributions should be formatted in [Springer LNCS](https://www.springer.com/computer/lncs?SGWID=0-164-2-791344-0) format
and submitted through EasyChair (link below) as a PDF file interpretable by common PDF tools and printable in black and white on A4 paper.

{% case status -%}
{%- when 0 -%}
<p style="margin:2em;" class="text-center">
    <button style="padding:1em;" type="button" class="btn btn-primary btn-lg disabled">The submission system is not open yet</button>
</p>
{%- when 1 -%}
<p style="margin:2em;" class="text-center">
    <a href="https://easychair.org/conferences/?conf=amp2024"><button style="padding:1em;" type="button" class="btn btn-primary btn-lg">Submit</button></a>
</p>
{%- else -%}
<p style="margin:2em;" class="text-center">
    <button style="padding:1em;" type="button" class="btn btn-primary btn-lg disabled">The submission system is closed</button>
</p>
{%- endcase -%}
