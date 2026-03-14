---
layout: default
---

# 0x41434f

I am a software engineer and mental health worker building toward a career in Computational Psychiatry and Health Policy.

I am currently finishing my medical school prerequisites with the goal of becoming a Consultation-Liaison Psychiatrist. My background includes a BS in Computer Science with a Cybersecurity focus, 7+ years as an engineer and venture capital analyst, and hundreds of hours on the floor of an acute psychiatric hospital.

I am the founder of [Stratification Labs](https://0x41434f.github.io/essays/the-stratification-mandate/), where we build [Psykick](https://psykicksv1.vercel.app/) and [Psychify](https://psychify-dz8w.vercel.app/) to reduce administrative burden and end trial-and-error psychiatry.

---

## Recent essays (new)

- February 15, 2026 — The Policy Floor
  - What surprised me was not how broken the system is. It was how precisely incentives produce outcomes like short visits, prior auth delays, and coverage gaps.
- January 15, 2026 — The Machine Doesn't Know
  - After a patient death with an active CPAP, the hospital adopted safety protocols that could have existed before.
- October 10, 2025 — Understanding Involuntary Holds
  - The legal code defines custody, but not the care pathway; that gap is where patients get lost.

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
