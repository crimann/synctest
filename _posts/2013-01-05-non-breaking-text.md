---
post_title: >
  Super/Duper/Long/NonBreaking/Path/Name/To/A/File/That/Is/Way/Deep/Down/In/Some/Mysterious/Remote/Desolate/Part/Of/The/Operating/System/To/A/File/That/Just/So/Happens/To/Be/Strangely/Named/Supercalifragilisticexpialidocious.txt
author: Michael Novotny
post_date: 2013-01-05 12:00:59
post_excerpt:
layout: post
permalink: http://www.test.dev/non-breaking-text/
---
Super/Duper/Long/NonBreaking/Path/Name/To/A/File/That/Is/Way/Deep/Down/In/Some/Mysterious/Remote/Desolate/Part/Of/The/Operating/System/To/A/File/That/Just/So/Happens/To/Be/Strangely/Named/Supercalifragilisticexpialidocious.txt

A few things to check for:
<ul>
	<li><span style="line-height: 1.714285714; font-size: 1rem;">Non-breaking text in the title, content, and comments should have no adverse effects on layout or functionality.</span></li>
	<li><span style="line-height: 1.714285714; font-size: 1rem;">Check the browser window / tab title.</span></li>
	<li><span style="line-height: 1.714285714; font-size: 1rem;">If you are a plugin or widget developer, check that this text does not break anything.</span></li>
</ul>
The following CSS properties will help you support non-breaking text.
<pre>-ms-word-wrap: break-word;
word-wrap: break-word;</pre>
&nbsp;