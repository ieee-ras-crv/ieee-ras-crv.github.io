---
title: "Activities"
layout: single
classes: wide
permalink: /activities/
author_profile: true
toc: true
toc_sticky: true
---

#### Upcoming Workshops
<table>
  {% for workshop in site.workshops %}
    <tr>
    <td>{{ workshop.date | date: "%m/%d/%y" }}</td>  
    <td>{{ workshop.conference }}</td>  
    <td><a href="{{ workshop.website }}">{{ workshop.name }}</a></td>
    </tr>
  {% endfor %}
</table>

#### Upcoming Special Issues
<table>
  {% for issue in site.special_issues %}
    <tr>
    <td>{{ issue.date | date: "%m/%d/%y" }}</td>  
    <td>{{ issue.conference }}</td>  
    <td><a href="{{ issue.website }}">{{ issue.name }}</a></td>
    </tr>
  {% endfor %}
</table>


#### Past Workshops
<table>
  {% for workshop in site.workshops_past %}
    <tr>
    <td>{{ workshop.date | date: "%m/%d/%y" }}</td>  
    <td>{{ workshop.conference }}</td>  
    <td><a href="{{ workshop.website }}">{{ workshop.name }}</a></td>
    </tr>
  {% endfor %}
</table>

#### Past Special Issues
<table>
  {% for issue in site.special_issues_past %}
    <tr>
    <td>{{ issue.date | date: "%m/%d/%y" }}</td>  
    <td>{{ issue.conference }}</td>  
    <td><a href="{{ issue.website }}">{{ issue.name }}</a></td>
    </tr>
  {% endfor %}
</table>
