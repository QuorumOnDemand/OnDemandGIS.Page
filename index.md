---
layout: default
title: Download On Demand GIS Add-In Tool
---

{% assign prod_version = site.data.version_production.latest %}
{% assign test_version = site.data.version_test.latest %}
{% assign vprod = 'v' | append: prod_version %}
{% assign vtest = 'v' | append: test_version %}

<p align="center">
	<br>
	<a href="https://quorumondemand.github.io/OnDemandGIS.Page/Production/{{ vprod }}/OnDemandGIS.esriAddinX" style="display:inline-block;padding:1em 2em;background:#1abc9c;color:#fff;font-weight:bold;border-radius:6px;text-decoration:none;font-size:1.2em;">⬇️ Download Production Add-In ({{ vprod }})</a>
</p>

<p align="center">
	<br>
	<a href="https://quorumondemand.github.io/OnDemandGIS.Page/Test/{{ vtest }}/OnDemandGIS.esriAddinX" style="display:inline-block;padding:1em 2em;background:#e67e22;color:#fff;font-weight:bold;border-radius:6px;text-decoration:none;font-size:1.2em;">⬇️ Download Test Add-In ({{ vtest }})</a>
</p>
