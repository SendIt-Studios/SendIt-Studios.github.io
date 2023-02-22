---
title: Revenge of the Babies
---

<nav>
    <ul>
    {% for entry in site.data.navigation %}
        {% if entry.url == current_page %}
            {% assign current = ' class="current"' %}
        {% else %}
            <!-- We have to declare it 'null' to ensure it doesn't propagate. -->
            {% assign current = null %}
        {% endif %}
        {% assign sublinks = entry.sublinks %}
        {% if sublinks %}
        <li{{ current }}>
            <a href="{{ site.baseurl }}{{ entry.url }}">{{ entry.title }}</a>
            <ul>
                {% for sublink in sublinks %}
                <li><a href="{{ site.baseurl }}{{ sublink.url }}">{{ sublink.title }}</a></li>
                {% endfor %}
            </ul>
        </li>
        {% else %}
        <li{{ current }}><a href="{{ site.baseurl }}{{ entry.url }}">{{ entry.title }}</a></li>
        {% endif %}
    {% endfor %}
    </ul>
</nav>

* [SendIt Studios Organization](https://github.com/SendIt-Studios)
* [M1 Project Board](https://github.com/orgs/SendIt-Studios/projects/2/views/1)

## Table of contents
* [Overview](#overview)
* [User Guide](#user-guide)
* [Milestones](#milestones)
* [Team Members](#team-members)

## Overview![img.png](img.png)

A game where babies are seeking revenge against those who stole candy from them because it was "too easy"...

The system provides the following:

* Top down, 2D/3D view
* Characters are looking for you so be stealthy
* Use the environment to find ways to get the candy
* Use your arsenal to distract or confuse the adults to leave candy vulnerable
* Controls:

## User Guide


## Team Members
* Nicholas Carr
    * [Portfolio](https://nicholasbcarr.github.io/)
* Eric Song
    * [Portfolio](https://jeanne8879.github.io/)
* Steven 
    * [Portfolio](https://gavinh123.github.io/)
* Gunwook
    * [Portfolio](https://lumd2000.github.io/)

![ci-badge](https://github.com/kanak-attack-manoa/kanak-attack-manoa/workflows/ci-kanak-attack-manoa/badge.svg)

