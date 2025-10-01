---
content_type: page
description: This syllabus section provides the course description and information
  on meeting times, prerequisites, grading, and using LaTeX for problem sets.
hide_download: true
hide_download_original: null
learning_resource_types: []
ocw_type: CourseSection
title: Syllabus
uid: 0586d482-62a8-cf61-256c-d4f0a5379180
---

Course Meeting Times
--------------------

Lectures: 2 sessions / week, 1.5 hours / session

One optional 2 hour open-problem session / week

Course Description
------------------

Data structures play a central role in modern computer science. You interact with data structures even more often than with algorithms (think Google, your mail server, and even your network routers). In addition, data structures are essential building blocks in obtaining efficient algorithms. This course covers major results and current directions of research in data structures:

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
Time Travel
{{< tdclose >}}
{{< tdopen >}}
We can remember the past efficiently (a technique called persistence), but in general it's difficult to change the past and see the outcomes on the present (retroactivity). So alas, Back To The Future isn't really possible.
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Geometry
{{< tdclose >}}
{{< tdopen >}}
When data has more than one dimension (e.g. maps, database tables).
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Dynamic Optimality
{{< tdclose >}}
{{< tdopen >}}
Is there one binary search tree that's as good as all others? We still don't know, but we're close.
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Memory Hierarchy
{{< tdclose >}}
{{< tdopen >}}
Real computers have multiple levels of caches. We can optimize the number of cache misses, often without even knowing the size of the cache.
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Hashing
{{< tdclose >}}
{{< tdopen >}}
Hashing is the most used data structure in computer science. And it's still an active area of research.
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Integers
{{< tdclose >}}
{{< tdopen >}}
Logarithmic time is too easy. By careful analysis of the information you're dealing with, you can often reduce the operation times substantially, sometimes even to constant. We will also cover lower bounds that illustrate when this is not possible.
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Dynamic Graphs
{{< tdclose >}}
{{< tdopen >}}
A network link went down, or you just added or deleted a friend in a social network. We can still maintain essential information about the connectivity as it changes.
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Strings
{{< tdclose >}}
{{< tdopen >}}
Searching for phrases in giant text (think Google or DNA).
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Succinct
{{< tdclose >}}
{{< tdopen >}}
Most "linear size" data structures you know are much larger than they need to be, often by an order of magnitude. Some data structures require almost no space beyond the raw data but are still fast (think heaps, but much cooler).
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Prerequisites
-------------

The prerequisite for this course is [_6.046, Design and Analysis of Algorithms_](/courses/6-046j-design-and-analysis-of-algorithms-spring-2012), or an equivalently thorough undergraduate algorithms class from another school (e.g., covering much of [![Buy at MIT Press](/images/mp_logo.gif)](https://mitpress.mit.edu/9780262533058) CLRS). I recommend that you take [_6.854, Advanced Algorithms_](/courses/6-854j-advanced-algorithms-fall-2008), the broad entry-level graduate course in Theory / Algorithms—it normally makes sense to start there before jumping into deeper graduate courses. If you haven't taken 6.854, you must have a strong understanding of algorithms at the undergraduate level, such as receiving an A in 6.046, having done relevant research, involvement in computer competitions, etc.

Grading
-------

There are three requirements, other than attending lectures:

*   Scribing one, maybe two, lectures. Note in particular that scribe notes are due on the day of the lecture. The entire calendar for the course has been posted, so you can select a lecture that interests you. We will circulate a sign-up sheet during the second week. Listeners may also be required to scribe one lecture.
*   Lightweight homework {{% resource_link 32329e90-b031-e2c2-c47c-2a321cdafb3f "assignments" %}}. Problems will be posted weekly, and will not be distributed otherwise.
*   Research-oriented {{% resource_link 688482c7-4a32-ee28-b5a4-8a7265d39b83 "final project" %}} (paper and presentation). We allow theoretical, experimental, and survey final projects.

LaTeX Help
----------

Homework solutions, scribe notes, and final projects must be typeset in LaTeX. If you are not familiar with LaTeX, there is no need to worry. Start with this good introduction, ["The Not So Short Introduction to LaTeX 2" (PDF - 2.04MB)](http://tug.ctan.org/info/lshort/english/lshort.pdf). You need to know very little to start writing problem sets in LaTeX: just skim through the mathematics section in the introduction, and [download this template](https://courses.csail.mit.edu/6.851/spring12/hw-template.tex).