

## 22. Speeding up the Release Cycle

Shuttle wasn’t the only piece of the project dragging on. More than a year elapsed between Shuttle-inspired WordPress 2.0 and the next version, WordPress 2.1. [Matt describes](http://ma.tt/2010/11/one-point-oh/) the time as “a dark time in WordPress development history, a lost year.” It was time for a streamlined development process.

WordPress's approach to new versions gives each major release two numbers: 1.5, 2.0, 2.9, 3.4, 4.0. Patch releases get an additional decimal point (2.0.1, for example). Many other software projects, like Drupal, give each major release a round number; over a period of years, the version number climbs. Decimalization avoids that, althought it took WordPress a while to settle on regular numbering.

The release cycle was sporadic in the early days. Version numbers jumped haphazardly. Some releases arrived in a few months, while 265 days went by between 1.2 and 1.5 -- the codebase had so many changes that WordPress skipped the interim version numbers, [going straight from 1.2 to 1.5](http://wordpress.org/news/2004/12/version-skip/). Version 1.6 was inflated to 2.0, because of the number of features in it and because 314 days had elapsed between the releases. But the delay between 2.0 (released December 31st, 2005) and 2.1 (released January 22nd, 2007) was the longest to date.  

The mailing list was active, and more developers than ever were attracted to the project. WordPress had been downloaded 1.5 million times. But despite active conversation, no one was shipping code. The [release post for WordPress 2.1, with its a plethora of new features](http://wordpress.org/news/2007/01/ella-21/), demonstrates the constant desire to slip in one more feature rather than waiting for the next release. Feature-packed releases brought myriad improvements, but at a cost: delay.

The delay frustrated contributors not just because of long the release cycles, but because commit access was still restricted to Matt and Ryan. Each free software project approaches commit access differently, and WordPress has a mixture of people who support a controlled Linux-style commit policy and those favoring open access. For many developers, the restrictive commit policy was partly to blame for delays. 

Ryan argued that [a defined funnel](http://lists.wordpress.org/pipermail/wp-hackers/2006-March/005192.html) avoided situations in which “bridge-burning arguments happen in the repository rather than in ticket comments." When committers are limited, approach and implementation discussions take place before any code touchs the main repository, where it’s difficult to remove. An open commit policy makes development more agile but brings its own challenges. "Loose control leads to spaghetti code and flame wars over inconsequential issues," wrote Douglas Daulton, [a supporter of the funnel](http://lists.wordpress.org/pipermail/wp-hackers/2006-March/005195.html), in a wp-hackers post.

In the context of these discussions, Ryan [codified a commit process that remains part of development today](http://lists.wordpress.org/pipermail/wp-hackers/2006-March/005190.html):

- Every commit must be accompanied by a ticket.
- Before being committed, the code is reviewed by at least two people -- one for a code review and the other for an integration/architecture review.
- These reviews are carried out by trusted contributors.

By March, 2006, incremental, positive changes were evident. Ryan proposed a focused #wordpress-dev IRC channel to facilitate discussion around development as a compelement to the #wordpress channel, which had become a place for general chatter and support. Mark Jaquith [pointed to the Bug Gardening scheme's success](http://lists.wordpress.org/pipermail/wp-hackers/2006-March/005189.html) in opening Trac up; extending privileges to to “bug gardeners” responsible for triaging tickets distributed the workload, leading to "a whole slew of people who are autonomously fixing bugs, submitting  patches, and having them committed." The Trac mailing list was another positive change, transforming Trac from simple bug-tracking to a place for focused discussion and curtailing wp-hackers' tendency to wander down conversational rabbit holes. 

As work on WordPress 2.1 went on, Ryan suggested [getting WordPress 2.0 into Debian stable](http://lists.wordpress.org/pipermail/wp-hackers/2006-October/008871.html), the official version of the  Debian open-source operating system. WordPress was already in the testing and unstable distributions, which each contain packages lined up for inclusion in the stable version. To be included in Debian stable, WordPress 2.0 would need to be maintained for three to five years, including backporting security issues to ensure that all previous versions remained stable. Mark Jaquith took on the task of maintaining the WordPress 2.0 branch, and the project committed to maintaining it for three years, until 2010. 

Shortly after he began leading the legacy branch, [Mark Jaquith received commit access](https://core.trac.wordpress.org/changeset/4270). Mark had been involved with WordPress since 2004, coming to the project from Movable Type. In his two years of work he’d made many contributions, including the successful bug gardening scheme. It was a sign that the funnel was starting to broaden, and the beginning of a period when -- slowly but surely -- more committers were added.

Commit access was offered sparingly; it wasn’t given out based on coding expertise or how much work a developer had done. Adding a new committer meant trusting them to uphold the project’s user-first ethos. “It’s not just that you’ve shown a commitment to contributing,” [says Peter Westwood](http://archive.wordpress.org/interviews/2013_07_02_Westwood.html#L122) ([westi](http://profiles.wordpress.org/westi)), “but you also have shown an understanding of the ethos of the community and their shared beliefs, and their philosophies.”

Adding another committer didn't speed up the development cycle, so the team took a more serious look at WordPress's development process -- or lack thereof. A discussion on [moving to a 120 Day release cycle](http://lists.wordpress.org/pipermail/wp-hackers/2006-October/008907.html) started on wp-hackers, and Matt shared his thoughts on what a release timeline should look like:	

> 2 months of crazy fun wild development where anything goes.
> 1 month of polishing things a little bit, and performance.
> Feature freeze.	
> 1 month of testing, with a public beta release at the beginning.	

Community response was positive. A 120-day structure provided a concrete deadline, and the shorter release cycles  meant that a feature need not hold up a release, as the next version would arrive predictably. (In theory -- in practice this often depended on what the feature was, who had spearheaded it, and how far along it was.) WordPress 2.1 was the first version to ship with a concrete release date for the next version: [April 23rd for WordPress 2.2](http://wordpress.org/news/2007/01/ella-21/). 

Publicizing release dates gave the project firm deadlines, which came to be seen as a promise -- a release date promise that users could plan around. The project didn’t quite make the next deadline but was only a few weeks off; WordPress 2.2 [released on May 16th, 2007](http://wordpress.org/news/2007/05/wordpress-22/). 

