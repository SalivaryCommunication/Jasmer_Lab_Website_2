---
title: Team
nav:
  order: 3
  tooltip: About our team
---
name: Kimberly Jasmer
image: images/team/2024-11-7_Jasmer, Kimberly_Dental_SCH_4630.jpg
role: Principle Investigator
description: Oral Immunology & Infectious Diseases
links:
  home-page: [https://tims-website.com/](https://louisville.edu/dentistry/departments/oralhealth/faculty/kimberly-jasmer-phd)
  email: Kimberly.Jasmer@Louisville.edu
  twitter: Swimberly
# {% include icon.html icon="fa-solid fa-users" %}Team

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
