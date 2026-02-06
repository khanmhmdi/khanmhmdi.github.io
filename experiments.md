---
layout: page
title: AI Experiments & Lab Notes
permalink: /experiments/
---

This section documents my ongoing and completed experiments on AI systems, serving as a research lab notebook.

{% assign exps = site.experiments | sort: "date" | reverse %}
{% for exp in exps %}
### [{{ exp.title }}]({{ exp.url }})

- **Date:** {{ exp.date | date: "%Y-%m-%d" }}
- **Model:** {{ exp.model }}
- **Task:** {{ exp.task }}
- **Tags:** {{ exp.tags | join: ", " }}

{% endfor %}
