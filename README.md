# Vivliostyle Relics

## Canary release

- **viewer:** https://vivliostyle.github.io/viewer
- **archive:** https://vivliostyle.github.io/viewer/vivliostyle-canary.zip

## Tagged releases

{% for release in site.data.releases %}
<h3>{{ release.version }}</h3>
<ul>
  <li>
    <b>viewer:</a> <a href="https://vivliostyle.github.io/viewer/{{ release.tag }}">https://vivliostyle.github.io/viewer/{{ release.tag }}</a>
  </li>
</ul>
{% endfor %}
