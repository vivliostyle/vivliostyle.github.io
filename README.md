# Vivliostyle Releases

## Stable release

- **viewer:** <https://vivliostyle.org/viewer/>
- **archive:** <https://vivliostyle.org/downloads/vivliostyle-latest.zip>

## Canary release (equivalent to `master`)

- **viewer:** <https://vivliostyle.now.sh/>

## Release history

{% for release in site.data.releases reversed %}
### {{ release.version }}

- **viewer:** <https://vivliostyle.github.io/viewer/{{ release.tag }}/>
- **archive:** <https://github.com/vivliostyle/vivliostyle/releases/download/{{ release.tag }}/vivliostyle-{{ release.version }}.zip>

{% endfor %}

## Links

- [vivliostyle.org](https://vivliostyle.org/download/)
