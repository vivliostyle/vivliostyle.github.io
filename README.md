# Vivliostyle Releases

for latest release, go to [vivliostyle.org](https://vivliostyle.org/download).

## Tagged releases

{% for release in site.data.releases reversed %}
### {{ release.version }}

- **viewer:** <https://vivliostyle.github.io/viewer/{{ release.tag }}>
- **archive:** <https://github.com/vivliostyle/vivliostyle/releases/download/{{ release.tag }}/vivliostyle-{{ release.version }}.zip>

{% endfor %}

## Other release channels

### Stable release

- **viewer:** <https://vivliostyle.org/viewer/>
- **archive:** <https://vivliostyle.org/downloads/vivliostyle-latest.zip>

### Canary release

- **viewer:** <https://vivliostyle.github.io/vivliostyle/viewer/>
- **archive:** <https://vivliostyle.github.io/vivliostyle/downloads/vivliostyle-canary.zip>
