---
layout: default
title: Malta Microsoft AI User Group (MMAUG)
---

Quick links:

- [Community Governance and Operational Process (PDF)](./Community%20Governance%20and%20Operational%20Process.pdf)
- [Code of Conduct](./code-of-conduct.html)
- [GitHub repository](https://github.com/maltamsaiusergroup/maltamsaiusergroup)

{% capture profile_readme %}{% include_relative README.md %}{% endcapture %}
{% assign readme_lines = profile_readme | split: '\n' %}
{% assign readme_body_lines = readme_lines | slice: 4, readme_lines.size %}
{{ readme_body_lines | join: '\n' | markdownify }}
