---
title: "{{shortTitle}}"
tags:
  - Book
citekey: "{{citekey}}"
author: '[[{{authors | replace(" ","_")}}]]'
---

> [!Citation]
> {{bibliography}} {%- for attachment in attachments %} [{{attachment.title}}]({{attachment.url}})  {%- endfor %}

## Excerpts

| Page | Quote | Notes |
| ---- | ----- | ----- |
|      |       |       |

## Zotero Metadata

> [!Abstract]
> {%- if abstractNote %}
> {{abstractNote}}
> {%- endif %}

>[!Metadata]
{% for type, creators in creators | groupby("creatorType") -%}
{%- for creator in creators -%}
> **{{"First" if loop.first}}{{type | capitalize}}**:: {%- if creator.name %} {{creator.name}}  {%- else %} {{creator.lastName}}, {{creator.firstName}}  {%- endif %}  {% endfor %}{%- endfor %}
> **Title**:: {{title}}
> ShortTitle:: {{shortTitle}}
> **Year**:: {{date | format("YYYY")}}   
> **Citekey**:: {{citekey}} {%- if itemType %}  
> **itemType**:: {{itemType}}{%- endif %}{%- if itemType == "journalArticle" %}  
> **Journal**:: *{{publicationTitle}}* {%- endif %}{%- if volume %}  
> **Volume**:: {{volume}} {%- endif %}{%- if issue %}  
> **Issue**:: {{issue}} {%- endif %}{%- if itemType == "bookSection" %}  
> **Book**:: {{publicationTitle}} {%- endif %}{%- if publisher %}  
> **Publisher**:: {{publisher}} {%- endif %}{%- if place %}  
> **Location**:: {{place}} {%- endif %}{%- if pages %}   
> **Pages**:: {{pages}} {%- endif %}{%- if DOI %}  
> **DOI**:: {{DOI}} {%- endif %}{%- if ISBN %}  
> **ISBN**:: {{ISBN}} {%- endif %}
