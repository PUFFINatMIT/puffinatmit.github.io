---
layout: page
title: Work With Us
permalink: /work-with-us/
---

# Work With Us

PUFFIN is a university scale pulsed-power facility, which provides hands-on training for the next generation of experts in high-energy-density science. We work with intense currents, high voltages, strong magnetic fields, high-powered lasers, and custom-built optical setups to create and measure exotic states of matter which do not occur naturally on Earth.

We welcome undergraduate students at MIT through the UROP scheme, and undergraduates from outside MIT through the MIT Summer Research Program. This program is aimed at providing opportunities for research to undergraduates from under-represented groups.

Graduate admissions at MIT are handled at the departmental level---Prof. Hare is a member of the Nuclear Science and Engineering Department, and can review applications made to this department. We particularly encourage applications from under-represented groups in plasma physics, including first generation students, women, members of the LGBT+ community, and members of under-represented ethnic minorities.

Currently we have no vacancies for post-doctoral researchers. However, if you are considering applying for an external fellowship and would like to work on PUFFIN, please get in contact so that we can discuss this further.

Please contact Prof. Hare via email ([jdhare@mit.edu](mailto:jdhare@mit.edu))  you have any questions about research opportunities.

## UROP Projects
If you are interested in working with us, check the UROP page at [https://nurop.scripts.mit.edu/UROP/](https://nurop.scripts.mit.edu/UROP/) to see all available projects in the NSE department.

### Past Projects

<div class="urop-listings-container">
{% for project in site.data.urops.past %}
    {% include urop_project_listing.html 
        title=project.title
        date=project.posted-date
        description=project.description
        image=project.image
        image_description=project.image_description
    %}
{% endfor %}
</div>

{% include collapsible_js.html %}