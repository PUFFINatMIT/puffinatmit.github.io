---
layout: page
title: Research
permalink: /research/
enable_maths: true
---

# Our Research

{% include quote.html
    quote_text="Real experiments are irreplaceable in providing new insights into subtle
                physics issues and in stirring the creative imagination of scientists."
    quote_attrib="Magnetohydrodynamic scaling: From astrophysics to the laboratory"
    quote_author="Ryutov, Remington, Robey, and Drake in Physics of Plasmas (2001)"
%}

PUFFIN is designed to be highly versatile, and will drive a range of loads in different 
geometries to produce shocks and jets, magnetized turbulence, magnetic reconnection, and 
magnetized heat flow. Research areas of interest include magnetohydrodynamic turbulence, 
magnetic reconnection, and magnetized target fusion.

You can find an overview of recent research in the poster we presented at <a href="/assets/posters/2023_APS_DPP_PUFFIN_group_compressed.pdf">APS DPP 2023</a>:

  {% include link_to_poster.html
            poster="/assets/posters/2023_APS_DPP_PUFFIN_group_compressed.pdf"
            thumbnail="/assets/posters/2023_APS_DPP_poster_preview.png"
        %}


<div class="research-page-link-container">
    {% for research_page in site.data.research %}
        <a class="research-page-link" href="{{ research_page.permalink }}">{{ research_page.title }}</a>
    {% endfor %}
</div>
