---
layout: default
---

# 0x41434f

I am a software engineer and mental health worker building toward a career in Computational Psychiatry and Health Policy.

I am currently finishing my medical school prerequisites with the goal of becoming a Consultation-Liaison Psychiatrist. My background includes a BS in Computer Science with a Cybersecurity focus, 7+ years as an engineer and venture capital analyst, and hundreds of hours on the floor of an acute psychiatric hospital.

I am the founder of [Stratification Labs](https://0x41434f.github.io/essays/the-stratification-mandate/), where we build [Psykick](https://psykicksv1.vercel.app/) and [Psychify](https://psychify-dz8w.vercel.app/) to reduce administrative burden and end trial-and-error psychiatry.

---

## Essays

These essays document my journey from a personal crisis to a new mission in mental health. They are best read in order.

<ul>
{% for post in site.posts reversed %}
  <li>
    <strong>{{ post.date | date: "%B %-d, %Y" }}</strong> — <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    {% if post.summary %}<br><em>{{ post.summary }}</em>{% endif %}
  </li>
{% endfor %}
</ul>

---

*Feel free to reach out if you want to talk about mental health policy, computational psychiatry, or what it is like to work the floor of a psychiatric hospital.*

### Connect

[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=flat&logo=youtube&logoColor=white)](https://youtube.com/yourchannel) [![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:your@email.com) [![X](https://img.shields.io/badge/X-1DA1F2?style=flat&logo=x&logoColor=white)](https://x.com/yourhandle) [![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat&logo=instagram&logoColor=white)](https://instagram.com/yourhandle) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourname) [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/yourhandle)
*
