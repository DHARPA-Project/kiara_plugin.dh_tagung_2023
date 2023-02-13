# [**kiara**](https://dharpa.org/kiara.documentation) plugin: dh_tagung_2023

This package contains a set of commonly used/useful modules, pipelines, types and metadata schemas for [*Kiara*](https://github.com/DHARPA-project/kiara).

## Description

Examples, code and documentation for the DH Tagung 2023 kiara workshop.

## Package content

{% for item_type, item_group in get_context_info().get_all_info().items() %}

### {{ item_type }}
{% for item, details in item_group.item_infos.items() %}
- [`{{ item }}`][kiara_info.{{ item_type }}.{{ item }}]: {{ details.documentation.description }}
{% endfor %}
{% endfor %}

## Links

 - Documentation: [https://DHARPA-Project.github.io/kiara_plugin.dh_tagung_2023](https://DHARPA-Project.github.io/kiara_plugin.dh_tagung_2023)
 - Code: [https://github.com/DHARPA-Project/kiara_plugin.dh_tagung_2023](https://github.com/DHARPA-Project/kiara_plugin.dh_tagung_2023)