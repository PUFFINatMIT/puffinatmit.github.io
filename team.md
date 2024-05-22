---
layout: page
title: Team
permalink: /team/
---

# Meet the PUFFIN Team

The PUFFIN team work out of the Plasma Science and Fusion Center here at MIT, though we are from a range of departments. There are two graduate students, though we often have openings for undergraduates to join us for a UROP project. See the "Work With Us" page for more information about becoming part of our team!

<div class="profile-container">
<hr class="profile-divider">
    {% for person in site.data.people %}
        {% include profile_block.html 
            name=person.name
            pronouns=person.pronouns
            img=person.profile_img
            email=person.email
            description=person.description
            website=person.website
            website_url=person.website_url
        %}
    {% endfor %}
</div>

## UROP Students

We actively recruit UROP students to run research projects within the group. If you are interested in registering for a UROP project with us, visit the "Work With Us" page.

<div class="urop-names-container">
    {% for person in site.data.urops.students %}
        <div class="urop-names-student">
            <b>{{ person.name }}</b> {% if person.affiliation %} ({{ person.affiliation }}) {% endif %} <br>
            Started {{ person.start }}
        </div>
    {% endfor %}
</div>

## Alumni

* Dr. Antonio Magnanimo, now at the European Patent Office
* Lily Li, now working with Prof. Anne White
* Jane Atkinson (UROP 2023)
* Osahon Odiase (UROP 2023)
* Dylan Robinson (UROP 2022-23)
* Jose Cerritos Arevalo (UROP 2022)
* Jason Smith (UROP 2022)
* Hanfei Cui (UROP 2022)
* Emily Wong (UROP 2021-22)

## Collaborations

Prof. Hare is co-PI of the MARZ collaboration (Magnetically Ablated Reconnection on Z), a Z Fundamental Science collaboration to run magnetic reconnection experiments on the Z machine at Sandia national labs. Z is the most powerful pulsed-power facility in the world, capable of delivering 25 MA current pulses. With MARZ, we will study strong radiative cooling in magnetic reconnection and the development of magnetized shocks. The MARZ collaboration includes Clayton Myers (SNL), Sergey Lebedev and Jerry Chittenden (Imperial College London), Dmitri Uzdensky (University of Colorado Boulder), Carolyn Kuranz (University of Michigan Ann Arbor), and Will Fox and Hantao Ji (PPPL).

We collaborate with [Prof. Loureiro’s group](http://loureirogroup.mit.edu/) at MIT, who carry out theoretical work on the connections between magnetic reconnection and magneto-hydrodynamic turbulence.

We work with the [High Energy Density Physics group at MIT](https://www1.psfc.mit.edu/research/hedp/index.html), who design state of the art diagnostics for two of the largest lasers in the world; OMEGA and NIF, as well as for Z, the world’s largest pulsed-power machine, at Sandia National labs.

We use the 3D MHD GORGON code, developed by [Prof. Chittenden](https://www.imperial.ac.uk/people/j.chittenden/research.html) at Imperial College, to design and model our experiments.

We collaborate with researchers at other pulsed-power facilities across the US and internationally, including the [COBRA generator at Cornell](https://www.lps.cornell.edu/project/cobra/), the [MAIZE generator at Ann Arbor, Michigan](https://plasmabay.engin.umich.edu/), and the [MAGPIE generator at Imperial College London](https://www.imperial.ac.uk/plasma-physics/magpie/).

## Puffins

Of course, we wouldn't be here without the puffins, some of the most charismatic birds on the planet. Ungainly in flight but unbelievably elegant in the water, puffins spend the winter at sea and the summer nesting on isolated cliffs. Puffins have only one chick per year, the puffling, and they feed it on sand-eels which they scoop up from the water and collect on special barbed spikes inside their beaks. Below are some photos of puffins taken by team members:

{% include image_with_caption.html src="/assets/puffins/20210330_bempton.jpg" caption="A puffin at Bempton cliffs in East Yorkshire, near where Jack grew up. Photo by Jack Hare." %}

{% include image_with_caption.html src="/assets/puffins/20210621_lunga4.jpg" caption="Jack with puffins on the island of Lunga in the Scottish Hebrides. The puffins here are unafraid of humans and will carry on unconcerned if you sit quietly. Photo by Alex Betts." %}

{% include image_with_caption.html src="/assets/puffins/20210621_lunga2.jpg" caption="A puffin landing at Lunga. Photo by Jack Hare." %}

{% include image_with_caption.html src="/assets/puffins/20210621_lunga3.jpg" caption="A puffin at Lunga with a beak full of sand eels for the puffling chick. Photo by Jack Hare." %}

{% include image_with_caption.html src="/assets/puffins/20210621_lunga1.jpg" caption="A group of puffins and razorbills sunning themselves on a rock on Lunga. Photo by Jack Hare." %}
