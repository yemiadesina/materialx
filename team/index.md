---
title: Team
nav:
  order: 3
  tooltip: About our team
---


# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: director" %}

{% include list.html data="members" component="portrait" filters="role: researcher" %}

{% include list.html data="members" component="portrait" filters="role: masters" %}

{% include list.html data="members" component="portrait" filters="role: undergrad" %}

{% include list.html data="members" component="portrait" filters="role: elevateIntern" %}

{% include list.html data="members" component="portrait" filters="role: ^(?!director$|researcher$|masters$|undergrad$|elevateIntern$).*" %}

{% include section.html background="images/background.jpg" dark=true %}

At our forefront, we envision a collaborative space nurtured by the dynamic confluence of varied perspectives and expertise. We are on the lookout for passionate scientists and engineers to join our vibrant and diverse team, where innovation meets dedication to craft the future of sustainable construction.

{%
  include button.html
  type="links"
  tooltip="Join our team"
  text="Join our team"
  link="/join"
%}
