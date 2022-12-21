---
layout: page
title: Communication
description: Information about Campuswire and Coursera.
---

# Communication

## Campuswire

- [Campuswire Link](https://campuswire.com/c/GFE888E31/feed)<br/>
- Campuswire passcode: 

## Staff Office Hour:

| Name | Office Hour time | Link |
|------|------------------|------|
{% for staffer in site.staffers %}
| {{ staffer.name }} | {{ staffer.officehour }} | {{ staffer.officehourlink }}
{% endfor %}