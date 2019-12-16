# Vivliostyle Releases

for latest release, go to [vivliostyle.org](https://vivliostyle.org/download).

## Canary release

- **viewer:** <https://vivliostyle.github.io/viewer>
- **archive:** <https://vivliostyle.github.io/viewer/vivliostyle-canary.zip>

## Tagged releases

{% for release in site.data.releases %}
### {{ release.version }}

- **viewer:** <https://vivliostyle.github.io/viewer/{{ release.tag }}>

{% endfor %}
