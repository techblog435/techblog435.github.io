---
title: Visualizing the UET Spirit
date: 2026-04-02
categories: [University, Engineering]
tags: [uet, matplotlib, seaborn, data-viz]
description: Reflections on my first official event as a CE student and a deep dive into data storytelling.
image:
  path: /assets/img/welcome.jpg
---

## The Senior’s Welcome: Reflections on my first official event as a CE student

Entering UET as a Computer Engineering student has been a whirlwind of excitement. The Senior's Welcome was my first official introduction to the culture here. It wasn't just an event; it was a transition into a community of innovators. Meeting the seniors gave me a clear vision of the path ahead—one filled with late-night coding, complex hardware labs, and a lot of collaborative spirit.

---

## Data Storytelling with Matplotlib: Using line plots and bar charts to uncover hidden trends

Beyond the social aspect of university, I've been diving deep into how we communicate data. **Matplotlib** is the first tool every engineer should master. It allows us to take raw numbers and turn them into a narrative.

Whether it's tracking my study hours or analyzing CPU performance, simple line plots and bar charts are essential for spotting trends that aren't visible in a spreadsheet.

```python
import matplotlib.pyplot as plt

# Visualizing my first week's focus hours
labels = ['Coding', 'Math', 'Physics', 'Labs']
hours = [15, 10, 8, 12]

plt.figure(figsize=(8, 5))
plt.bar(labels, hours, color='skyblue')
plt.title('Weekly Study Distribution (CE Student Life)')
plt.ylabel('Hours Spent')
plt.show()
