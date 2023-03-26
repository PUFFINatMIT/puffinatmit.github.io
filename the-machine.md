---
layout: page
title: The Machine
permalink: /the-machine/
---

# The Machine

PUFFIN is designed to deliver an intense pulse of electrical current to a "load", and arrangement of thin wires or foils which are rapidly converted into hot, dense plasma. PUFFIN is built around the LTD5 modules developed at CEA Gramat. LTDs are Linear Transformer Drivers, a relatively new pulsed-power technology which encloses the capacitive energy store and switch in a single conducting cavity. This reduces the inductance of the system and shields external equipment from the electromagnetic pulse.

PUFFIN's unique capability is it's microsecond pulse length, in contrast to fast rise-time LTD pulsers such as [MAIZE](https://plasmabay.engin.umich.edu/research/michigan-accelerator-for-inductive-z-pinch-experiments-maize/) and [HADES](http://gourdain.pas.rochester.edu/index.php/research/experiment/hades), which drive rapid implosions to reach extreme conditions. Instead, the longer pulse length on PUFFIN allow us to sustain plasmas in a quasi-steady-state, which is ideal for studying fundamental plasma processes.

{% include image_with_caption.html src="/assets/2023_03_24_PUFFIN_annotated_drawings_perspective.png" caption="The current PUFFIN design using 2 LTD modules." %}

PUFFIN is currently in the design phase. Two LTD5 modules, along with the charge-and-dump, pre-magnetisation, and switch trigger systems arrived at the PSFC in May 2022. Refurbishment of the lab space in the West Cell of the PSFC (MIT building NW21) is expected to be finished by the end of Summer 2022. 

{% include image_with_caption.html src="/assets/2023_03_24_PUFFIN_annotated_drawings_side-on.png" caption="Side on view of PUFFIN showing the outside of the transmission lines and power junction." %}

PUFFIN consists of 2 LTD5 modules (consisting of two 3.9 uF, 100 kV Haefly capacitors) coupled to two coaxial vacuum transmission lines (200 mm OD, 20 mm gap) by multi-channel low-inductance switches immersed in pressurized dry air.
The transmission lines merge at the power junction and transmit the current upwards into the vacuum chamber.

{% include image_with_caption.html src="/assets/2023_03_24_PUFFIN_annotated_drawings_cutaway.png" caption="Cutaway view of the center of PUFFIN showing the conical power feed and insulator stack. " %}

The vacuum chamber has 16 sides with configurable vacuum ports to enable a range of diagnostics to be fielded, including interferometry, Thomson scattering and Faraday rotation imaging. There is also a clear line of sight axially through the load.

In a future design we intend to use uses eight LTD5 modules (or stages) arranged in four lines of two modules each. The modules stacked in series increase the overall voltage of the pulse, and the modules stacked in parallel increase the total current.

  {% include link_to_poster.html
            poster="/assets/posters/APSDPP2020_PUFFIN_Poster_lowres.pdf"
            thumbnail="/assets/posters/APSDPP2020_PUFFIN_Poster_lowres_thumbnail.png"
        %}

You can find out more about PUFFIN <a href="/assets/posters/APSDPP2020_PUFFIN_Poster_lowres.pdf">in this poster</a> we presented at APS DPP 2020, though as noted the design has now evolved to the two stage version presented above.


### Recommended reading
- ["A Primer on Pulsed Power and Linear Transformer Drivers for High Energy Density Physics Applications"](https://spiral.imperial.ac.uk/handle/10044/1/64848) by McBride et al. A very thorough review of LTDs and pulsed-power in general.
- ["Status on the SPHINX machine based on the 1 microsecond LTD technology"](https://ieeexplore.ieee.org/document/4651825) by Lassalle et al. An overview of the LTD5 stages to be used on PUFFIN.