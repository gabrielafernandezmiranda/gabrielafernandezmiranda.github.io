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

Fernández-Miranda, G., Uriago-Rayo, J.S., Jiménez-Leal, W., Akle, V., Noguera, E., Mejía, N. & Amaya, S. (Under review). Compassion and decision fatigue among healthcare workers during COVID-19 pandemic in a Colombian sample.

Fernández-Miranda, G., & Aranguren-Romero, J.P. (Under review). La gestión emocional de la frustración en antropólogos (as) forenses que trabajan en la búsqueda de víctimas de desaparición forzada en Colombia.

Bermúdez, J.P., Berthelette, S., Anaya, A., Fernández-Miranda, G., & Rodríguez, D. (Under review). Positive and Negative Self-Control.

Aranguren-Romero, J.P., & Fernández-Miranda, G. (2021). [Gestionar la frustración: experiencias relacionales de antropólogas forenses en el contexto del conflicto armado colombiano](https://journals.openedition.org/nuevomundo/83956) {:target="_blank"}. Nuevo mundo, mundos nuevos. https://doi.org/10.4000/nuevomundo.83956

López-López, W., Correa-Chica, A., Sierra-Puentes, M., Castañeda, J., Fernández, G., Durán, M., & Castro, P. (2020). [Children’s Conceptualizations of Forgiveness, Reconciliation, and Peacebuilding in the Context of Armed Conflict](https://link.springer.com/chapter/10.1007/978-3-030-22176-8_13). En:
Balvin, N., & Chistie, D. (eds) Children and Peace. Peace Psychology Book Series. Springer, Cham.



{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
