---
layout: home
---

# 0x41434f

I am a software engineer and mental health worker building toward a career in Computational Psychiatry and Health Policy.

I am currently finishing my medical school prerequisites with the goal of becoming a Consultation-Liaison Psychiatrist. My background includes a BS in Computer Science with a Cybersecurity focus, 7+ years as an engineer and venture capital analyst, and hundreds of hours on the floor of an acute psychiatric hospital.

I am the founder of [Stratification Labs](https://psykicksv1.vercel.app/), where we build [Psykick](https://psykicksv1.vercel.app/) and [Psychify](https://psychify-dz8w.vercel.app/) to reduce administrative burden and end trial-and-error psychiatry.

---

## Essays

These essays document my journey from a personal crisis to a new mission in mental health. They are best read in order.

{% for post in site.posts reversed %}
**{{ post.date | date: "%B %-d, %Y" }}** — [{{ post.title }}]({{ post.url | relative_url }})
{% if post.summary %}*{{ post.summary }}*{% endif %}

{% endfor %}

---

*Feel free to reach out if you want to talk about mental health policy, computational psychiatry, or what it is like to work the floor of a psychiatric hospital.*
