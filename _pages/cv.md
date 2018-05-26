---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======

* Ph.D in Computer Science, Princeton University, 2018 - Present
* B.S. in Computer Science, UMass - Amherst, 2018

Work experience
======
* Summer 2017: Microsoft
  * Worked as a member of the Windows and Devices Group in the Core OS Development – Base Kernel – Kernel Core Team. The main technologies and tools used were C and WinDbg.
  * Ported the Windows 10 Segment Heap to run in kernel mode, and work with both paged and non-paged memory pool types
  * Made modifications to the existing Windows 10 Segment heap to meet the requirements of the existing memory pools
  * Ported the existing heap stress test to run in kernel mode 
* Summer 2016: Microsoft
  * Worked as a member of the Windows and Devices Group in the Core OS Development – Storage and File Systems – ReFS team. The main technologies and tools used were Microsoft C/C++, Visual Studio 2015 Enterprise and WinDbg 
  * Developed a tool for ReFS (Resilient File System), designed to detect storage leaks, as well as leaks in Cloned Data Blocks 
  * Developed a performance improvement in the mainline production code that improved end-to-end IOPS performance by 3% 
  
Skills
======
C, C++, Python, Java, JavaScript, Linux, UNIX, Windows, Operating Systems, Git

Publications
======
  {% assign sortedpubs = site.publications | sort: 'date' | reverse %}
  <ul>{% for post in sortedpubs %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  {% assign sortedteaching = site.teaching | sort: 'date' | reverse %}
  <ul>{% for post in sortedteaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
