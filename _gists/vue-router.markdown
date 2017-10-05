---
layout: gist
title:  "Vue Router"
date:   2017-08-02 12:19:14 +010
author: "Sam"
categories: gist
tags:
  vue
  js
---

Used to loop through `entries` in a `channel` but only the ones for a specific entry type

{% highlight liquid %}
{% raw %}
{% set entries = craft.entries.section('pages') %}

{% for entry in entries %}
   {{ entry.title }}
{% endfor %}
{% endraw %}
{% endhighlight %}

Check out the Craft CMS docs [Craft CMS docs](https://craftcms.com/docs/introduction) for more info.
