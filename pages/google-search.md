---
title: Google CSE
layout: page
permalink: /search/google.html
# optional Google search page, see docs/google.md
# set google-cse-id in _config.yml
---

## Búsqueda de Google en el Sitio Web

<div class="alert alert-primary" role="alert">
  TENGA EN CUENTA: "CSE" es un servicio gratuito que provee Google. Los resultados dependerán de la forma en que este tercero indexa este sitio web y sus resultados pueden variar con cada consulta e incluir publicidad.
</div>

<script>
  (function() {
    var cx = '{{ site.google-cse-id }}';
    var gcse = document.createElement('script');
    gcse.type = 'text/javascript';
    gcse.async = true;
    gcse.src = 'https://cse.google.com/cse.js?cx=' + cx;
    var s = document.getElementsByTagName('script')[0];
    s.parentNode.insertBefore(gcse, s);
  })();
</script>
<gcse:search></gcse:search>
