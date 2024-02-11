---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

1. **S. Baig**, T. Vahabzadeh, S. Ebrahimi, and J. Jatskevich, “Reconfigurable Star-Delta VBR Induction Machine Model for Predicting Soft-Starting Transients,” in Proc. IEEE Int. IOT, Electronics, and Mechatronics (IEMTRONICS) Conf., June 2022, pp. 1–7.
2. **S. Baig**, S. Ebrahimi, and J. Jatskevich, “Efficient Modeling of Adjustable Speed Drive Systems for Offline and Real-Time Simulators,” in Proc. IEEE 22nd Int. Symp. INFOTEH–JAHORINA (INFOTEH) Conf. , Mar. 2023, pp. 1–6.
3. T. Vahabzadeh, **S. Baig**, S. Ebrahimi, and J. Jatskevich, “Investigation of MIMO State Feedback Controller for Grid-Connected AC-DC Voltage Source Converters,” in Proc. IEEE Int. Conf. on Electrical, Computer and Energy Technologies (ICECET), July 2022, pp. 1–6.
4. Y. Zhang, **S. Baig**, T. Vahabzadeh, and J. Jatskevich, “Maximum Efficiency Volts-per-Hertz Control of Induction Motor Drives Considering Core Losses, Saturation, and Inverter Losses,” in Proc. IEEE Int. Conf. on Electrical, Computer and Energy Technologies (ICECET), July 2022, pp. 1–7.
5. **S. Baig**, S. Ebrahimi, J. Jatskevich, L. Wang, and A. Fani, “Wide-Band Constant-Parameter VBR Model of Three-Phase Induction Machines,” IEEE Trans. on Energy Convers. (under review), pp. 1–10.

