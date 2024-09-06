---
layout: page
title: Home
description: A course covering the necessary background of neural-network-based deep learning for robot perception and manipulation – building on advancements in computer vision that enable robots to physically manipulate objects. CSCI5980 at the University of Minnesota.
nav_order: 1
permalink: /
---

<div class="banner-container">
<img src="/CSCI5980-F24-DeepRob/assets/images/umn_banner_F24.jpeg" alt="Banner" style="width:100%;">
<div class="banner-info">
	<!-- <div class="banner-title">DeepRob</div> -->
	<!-- <div class="banner-subtitle">Deep Learning for Robot Perception</div> -->
<!-- 	<img  src="{{site.baseurl}}/assets/logos/DeepRob.svg" alt="DeepRob"/> -->

<!-- <div class="banner-sub-info">
	<div class="banner-text">
	CSCI 5980
	</div>
	<div class="banner-text">
	Fall 2024 at the University of Minnesota
	</div>
</div> -->

</div>
</div>


<!-- # Deep Learning for Robot Manipulation
## CSCI5980 Fall 2024 at The University of Minnesota - Twin Cities
{: .fs-6 .fw-300 } -->
# Meeting Time: M, W 9:45AM-11:00PM CT - Applebay Hall 102
<!-- {: .fs-5 .fw-300 } -->

<!-- This website describes a course still in development to be offered in the Spring 2023 semester.
{: .text-red-300 .bg-yellow-200 .fs-4 .fw-500} -->

This course covers the necessary background of neural-network-based deep learning for robot perception – building on advancements in computer vision that enable robots to physically manipulate objects. During the first part of this course, students will learn to implement, train and debug their own neural networks. During the second part of this course, students will explore recent emerging topics in deep learning for robot perception and manipulation. This exploration will include analysis of research publications in the area, building up to reproducing one of these publications for implementation as a final course project.

This course is being offered at the University of Minnesota ([Karthik Desingh](https://karthikdesingh.com/)).

This course is being offered through a Distributed Teaching Collaborative between faculty at [the University of Minnesota](https://twin-cities.umn.edu/) ([Karthik Desingh](https://karthikdesingh.com/)) and [the University of Michigan](https://umich.edu/) ([Anthony Opipari](https://topipari.com), [Xiaoxiao Du](https://xiaoxiaodu.net/), [Chad Jenkins](https://ocj.name/))


This course builds on and is indebted to these existing courses (as a “star” and a "fork" in the open source sense):
- [University of Michigan - ROB 498-011 & 599-011: Deep Learning for Robot Perception](https://deeprob.org/w24/) instructed by ([Xiaoxiao Du](https://xiaoxiaodu.net/), ([Anthony Opipari](https://topipari.com), [Chad Jenkins](https://ocj.name/))
- [University of Minnesota - CSCI5980: Deep Learning for Robot Perception and Manipulation](https://rpm-lab.github.io/CSCI5980-Spr23-DeepRob) instructed by ([Karthik Desingh](https://karthikdesingh.com/), in collaboration with ([Anthony Opipari](https://topipari.com), [Chad Jenkins](https://ocj.name/)) from the University of Michigan.
- [University of Michigan - EECS 498-007 / 598-005: Deep Learning for Computer Vision](https://web.eecs.umich.edu/~justincj/teaching/eecs498/WI2022/schedule.html) instructed by [Justin Johnson](https://web.eecs.umich.edu/~justincj/)
- [Stanford - CS231n: Deep Learning for Computer Vision](http://cs231n.stanford.edu/index.html) instructed by [Fei-Fei Li](https://profiles.stanford.edu/fei-fei-li) and [Andrej Karpathy](https://karpathy.ai/)


<div class="staff-row" >
<div markdown="1" class="staff-column">

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

</div>
<div markdown="1" class="staff-column">

<!-- ## Collaborating Instructors

{% assign instructors = site.staffers | where: 'role', 'Collaborating Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %} -->

</div>
</div>

{% assign teaching_assistants = site.staffers | where: 'role', 'Instructional Aide' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
## Instructional Aides

<div class="staffer-table">
{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
</div>
{% endif %}
