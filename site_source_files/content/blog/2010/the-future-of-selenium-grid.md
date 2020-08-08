+++
Description = "<p>As you likely know by now, after years of stewardship Philippe has stepped down as maintainer of Selenium Grid and has named me the new maintainer. In this post, I hope to address the most immediate questions about what this means for the future of Selenium Grid. Background I realize many of you may not […]</p>"
Title = "The Future of Selenium Grid"
Date = 2010-04-27
Author = "Kevin Menard"
AuthorLink = "https://twitter.com/nirvdrum"
tags = ["selenium","future","grid"]
categories = ["general"]
+++

<p>As you likely know by now, after years of stewardship Philippe has stepped down as maintainer of Selenium Grid and has named me the <a href="http://ph7spot.com/blog/new-selenium-grid-maintainer">new maintainer.</a>  In this post, I hope to address the most immediate questions about what this means for the future of Selenium Grid.</p>
<h2>Background</h2>
<p>I realize many of you may not know who I am.  I&#8217;ve been using Selenium in some capacity for close to five years now.  I love working on open source software and do so primarily through my membership in the Apache Software Foundation and through <a href="http://github.com/nirvdrum/">my GitHub account</a>.  I hang out on the #selenium channel with the handle &#8220;nirvdrum&#8221; and have a <a href="http://nirvdrum.com/">personal page</a> that includes some articles I&#8217;ve written and other things I&#8217;m involved with.  Perhaps more importantly, I also rely on Selenium Grid for <a href="http://mogotest.com/">my latest start-up</a> so I&#8217;m very keen on seeing the project mature and evolve.</p>
<h2>Project Resources</h2>
<p>The new canonical project repository on GitHub is the <a href="http://github.com/nirvdrum/selenium-grid/">nirvdrum fork</a>.  However, within in the next month or so the project will be migrated from git and GitHub to subversion and the <a href="http://code.google.com/p/selenium/">Selenium project on Google Code</a>.  As much as I personally prefer GitHub to Google Code, it makes the most sense from a community perspective for all Selenium projects to be hosted in the same location.  The move will be made after Selenium Grid stabilizes a bit more.  The <a href="http://seleniumhq.wordpress.com/2010/04/13/selenium-grid-1-0-6-released/">1.0.6 release</a> was the first step in that process, but there may be one or two more minor patch releases.  After the move, I&#8217;ll try to maintain a synchronized mirror of the code on GitHub so those that prefer to develop patches with git can continue to do so.</p>
<p>The canonical issue tracker is the <a href="http://code.google.com/p/selenium/issues/list">Selenium issue tracker</a> on Google Code.  We will not be using either JIRA or GitHub Issues.  I&#8217;ll try to migrate what I can over to the new tracker, but if I miss anything, please re-open the issue over there.</p>
<h2>Project Evolution</h2>
<p>Selenium Grid currently only works with Selenium 1.x, and consequently the 1.x compatibility interface in Selenium 2.  There is currently no support for WebDriver.  However, I fully intend to steer the product in that direction, while maintaining support for existing Selenium Grid installations (i.e., based on Selenium 1.x).</p>
<p>Since the project is moving to Google Code, all of the existing Selenium committers will have the ability to commit to the codebase.  This should make the project&#8217;s evolution a much more collaborative effort.  I&#8217;ll kickstart the process and likely lead the development effort, but the role of maintainer will be diminished (in a positive way) by allowing the entire core team equal access to the project.</p>
<p>Others are welcome to chime as well.  Selenium Grid development discussion will be taking place on the Selenium developers list.  Please continue to use the Selenium users list for usage and support inquiries.</p>
