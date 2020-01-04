# Vivliostyle Releases

## Stable release

- **viewer:** <https://vivliostyle.org/viewer/>
- **archive:** <https://vivliostyle.org/downloads/vivliostyle-latest.zip>

## Canary release (equivalent to `master`)

- **viewer:** <https://vivliostyle.now.sh/>
- **archive:** <https://vivliostyle.now.sh/vivliostyle-canary.zip>

## Release history

{% for release in site.data.releases reversed %}
### [{{ release.version }}](https://github.com/vivliostyle/vivliostyle/releases/tag/{{ release.tag }})

{% if release.tag < "2020" %}
- **viewer:** <https://vivliostyle.github.io/viewer/{{ release.tag }}/vivliostyle-viewer.html>
- **archive:** <https://github.com/vivliostyle/vivliostyle/releases/download/{{ release.tag }}/vivliostyle-js-{{ release.version }}.zip>
{% else %}
- **viewer:** <https://vivliostyle.github.io/viewer/{{ release.tag }}/>
- **archive:** <https://github.com/vivliostyle/vivliostyle/releases/download/{{ release.tag }}/vivliostyle-{{ release.version }}.zip>
{% endif %}

{% endfor %}

## Links

- [vivliostyle.org](https://vivliostyle.org/download/)
- [Source](https://github.com/vivliostyle/vivliostyle.github.io)
