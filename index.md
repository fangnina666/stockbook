---
layout: default
title: 報告索引
---

# Daily Stock Reports

<div id="search-box">
  <input id="search-input" type="search" placeholder="搜尋報告全文…" style="width:100%;padding:8px;">
</div>
<div id="results"></div>
<hr>
<ul>
{% assign pages = site.pages | where_exp:'p','p.path contains "reports_his/"' | sort: 'name' | reverse %}
{% for p in pages %}
  <li><a href="{{ p.url | relative_url }}">{{ p.title | default: p.name | remove: ".md" }}</a></li>
{% endfor %}
</ul>

<script src="https://cdn.jsdelivr.net/npm/simple-jekyll-search@1.10.0/dest/simple-jekyll-search.min.js"></script>
<script>
  SimpleJekyllSearch({
    searchInput: document.getElementById('search-input'),
    resultsContainer: document.getElementById('results'),
    json: '{{ "/search.json" | relative_url }}',
    searchResultTemplate: '<div><a href="{url}">{title}</a></div>',
    noResultsText: '沒有結果'
  })
</script>
