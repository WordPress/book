## 28. Happy Cog Redesign

Shuttle had failed and WordPress' admin needed a redesign. Matt went to [design studio Happy Cog](http://lists.wordpress.org/pipermail/wp-hackers/2007-November/016123.html). Jeffrey Zeldman, Happy Cog founder, led the project with WordPress's logo designer Jason Santa Maria, and UX designer Liz Danzico.

Whereas Shuttle focused on aesthetics, Happy Cog identified and corrected information architecture problems, and updated and improved WordPress' look and feel. Despite the project's user-first ethos, the admin screens had become cluttered over time, as new features were added in a relatively haphazard way. The change between WordPress 1.5 and WordPress 2.3 shows the features stuffed into the Pods Shuttle had introduced. 

<img alt="WordPress 1.5 write screen" src="../../Resources/images/28/wp_1_5.png" width=“800px” />

*The Write screen in WordPress 1.5*

<img alt="WordPress 2.3 write screen" src="../../Resources/images/28/wp_2_3.png" width="800px" />

*The Write screen in WordPress 2.3*

Happy Cog produced designs and WordPress developers coded them. The project included user research and an interface audit to identify WordPress' strengths and weaknesses which informed new structural and interface designs. 

WordPress, as a free software project, was an unusual client for a traditional design agency. The Happy Cog team was mostly sheltered from the community, by both Matt and Jeffery, but they knew this was an entirely different type of client. [Jason Santa Maria says now](http://archive.wordpress.org/interviews/2014_01_22_Santa_Maria.html#L82):

> Any other client will have customers and their own community, but you really have to just manage the people inside of a company, whereas when you’re dealing with an open source project, you deal with the people that you’re talking with, but there’s this whole gamut of other people that you will only ever get to talk to a small portion of. I think that that’s really difficult.

> Plus, I think that on an open source project like this, it’s inherently different, not just because it’s more of a CMS than an informational website -- the design needs are different -- but it’s just a different kind of way to work, knowing that whatever you do probably isn’t going to stick around for very long. It’s going to continue to evolve and continue to be adapted. Usually, in the very near-term as well, not even three-four months from now, but next week.

An audit and usability review were among the first steps. Liz Danzico researched and produced a 25-page research audit on WordPress. WordPress needed an admin that didn’t intrude on the user. In the audit, she quotes [Mark Jaquith](http://markjaquith.wordpress.com/2007/02/21/engine-awareness/): "That’s when I know WordPress is doing its job: when people aren’t even aware they’re using it because they’re so busy using it!"

Liz spoke to Mark Riley, whose support forum experience gave him direct access to users' complaints. One of the major problems he highlighted was the clutter that had appeared in the write screen between WordPress 1.2 and WordPress 2.0. Features had been added haphazardly and then tucked into modules using the pods introduced by the Shuttle project. There were many actions a user could take on the Write screen -- many of which were confusing or hidden.

Discussion focused on navigation structure, including labelling, position, and functionality grouping. Should they go with an object-oriented navigation (Posts, Pages, Comments, etc.,) or an action-oriented navigation (Write, Manage, etc.,)? Liz's first hunch -- supported by the newly-launched Tumblr -- was that users preferred navigating by nouns. She felt WordPress’ verb structure was confusing. In the first navigational structure iterations, both a noun version and a verb version were produced. In the end, however, and after limited user testing, the team went with a mixture of nouns and verbs: Write, Manage, Design, Comments. This meant that the functionality for different content types was scattered over different menu items -- to write a post, for example, the user would go to "Write" but to manage a post they would navigate to "Manage." 

Happy Cog provided extensive and detailed proposals and research for WordPress, all of which was fed back to Matt as the client. Their reports display a sensitivity to web users, and an appreciation for simplifying and streamlining WordPress. 

When it came to the design stage, Jason Santa Maria created three designs to present to Matt, who would choose one to move forward. 

He designed three early mockups:

<img alt="Happy Cog design 1" src="../../Resources/images/28/happy-cog-design-a.jpg" />

*Mockup Number 1*

<img alt="Happy Cog design 2" src="../../Resources/images/28/happy-cog-design-b.jpg" />

*Mockup Number 2*

<img alt="Happy Cog design 3" src="../../Resources/images/28/happy-cog-design-c.jpg" />

*Mockup Number 3*

Matt chose the visually lighter design. Jason had taken Shuttle's heavy blue palette and lightened the interface. An orange accent color complemented the lighter blues.

When the design was finally signed off, WordPress trunk started to transform. As change happened [community feedback](http://lists.wordpress.org/pipermail/wp-hackers/2008-February/017849.html) was [posted to wp-hackers](http://lists.wordpress.org/pipermail/wp-hackers/2008-February/017850.html). Was the admin actually more usable? Major changes broke familiar patterns. Some comments make comparisons with Shuttle; a few community members [wanted to implement Shuttle's interface](http://weblogtoolscollection.com/archives/2008/01/02/wordpress-24-admin-preview/#comment-1207158). 

Just before release, [a sneak peek was posted to the development blog](http://wordpress.org/development/2008/03/25-sneak-peek/), and WordPress users installed the release candidate to get a better look. The response was similar to that of the rest of the community. Regular WordPress users were surprised by the functionality changes to the Write screen. For some, it was [a step backward for usability](http://www.neatorama.com/2008/04/21/wordpress-25-admin-backend-category-shenanigans-and-how-to-fix-it/#!vG29i). 

<img alt="The write screen in the WordPress 2.5 admin" src="../../Resources/images/28/2_5_admin.jpg" />

*The Write screen in the WordPress 2.5 admin*

WordPress 2.4 was the first version to fall significantly behind the 120-day release cycle. Versions 2.2 and 2.3 were mostly on schedule, but the Happy Cog redesign brought in major changes to the codebase that meant delaying the release. Rather than just delaying release, a version was skipped, [moving straight from WordPress 2.3 to WordPress 2.5](http://lists.wordpress.org/pipermail/wp-hackers/2008-January/016993.html), which was scheduled for release in March. 

But there were bigger problems with the release cycle than the delay. The community felt that they had not been consulted; they felt disenfranchised from the process. In some ways, the redesign was destined to fail before it even began. With no participation, no process, there was no way to assure community buy-in. Jeffrey Zeldman, reflecting on the process now says:

> It worked for us, from our perspective, that we were a small team reporting to a single client who had life or death approval over everything. We had to please one user: Matt. He could say yes or no. We completely bypassed the community. That enabled us to get a design done that we felt was crisp and focused and achieved certain goals. And that sounds great. Except that, because the community wasn't involved, inevitably, the design then became unpopular because nobody got their say in it. And if I could go back and do it again, I would involve them up front, and find ways to get my feedback without it turning into a committee clustercuss. 

As with Shuttle before it, problems surfaced in the free software project's design process. Free software projects are collaborative enterprises; when part of that process moves behind closed doors to avoid the problems of working by committee, new problems arise. However much a project tries to avoid it, that committee exists and must have its say.
	
