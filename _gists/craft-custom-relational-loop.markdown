---
layout: gist
title:  "Craft Custom Relational Loop"
date:   2017-10-02 12:19:14 +010
author: "Sam"
categories: gist
tags:
  craft
  twig
---

Used to loop through `entries` in a `channel` but only the ones for a specific entry type

{% raw %}
~~~ liquid
{% set entries = craft.entries.section('pages') %}

{% for entry in entries %}
   {{ entry.title }}
{% endfor %}
~~~
{% endraw %}

Check out the Craft CMS docs [Craft CMS docs](https://craftcms.com/docs/introduction) for more info.
