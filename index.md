---
layout: home
title: CS 7650
nav_exclude: true
seo:
  type: Course
  name: Just the Class
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}

- Location: Instructional Center 103
- Time: MW 5:00 pm - 6:15 pm
- [Piazza](https://piazza.com/gatech/spring2025/cs7650/) (announcements, questions, discussion)
- [Gradescope](https://www.gradescope.com/courses/939711) (homework assignments, submission and grading)
- [Tentative Course Schedule](https://docs.google.com/spreadsheets/d/1LcEgP8g4MIU6f6DVFDcrTk1ppK7R-o5Ls1n8n8orfnw/edit?usp=sharing)

{% for module in site.modules %}
{{ module }}
{% endfor %}
