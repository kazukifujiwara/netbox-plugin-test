# netbox-plugin-test

a sample plugin for netbox 

* project-name: netbox-plugin-test
* plugin_name: test_plugin

## Plugin Structure

[Netbox Documentation - Plugins Development](https://docs.netbox.dev/en/stable/plugins/development/)

```
project-name/
  - plugin_name/
    - api/
      - __init__.py
      - serializers.py
      - urls.py
      - views.py
    - migrations/
      - __init__.py
      - 0001_initial.py
      - ...
    - templates/
      - plugin_name/
        - *.html
    - __init__.py
    - filtersets.py
    - graphql.py
    - models.py
    - middleware.py
    - navigation.py
    - signals.py
    - tables.py
    - template_content.py
    - urls.py
    - views.py
  - README.md
  - setup.py
```
