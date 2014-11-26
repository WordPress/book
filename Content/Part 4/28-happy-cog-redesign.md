## 28. Happy Cog Redesign

Now and then, people were still asking of the Shuttle designs would be implemented. WordPress was in need of an admin redesign. The project turned to [design studio Happy Cog, who were to redesign the admin](http://lists.automattic.com/pipermail/wp-hackers/2007-November/016123.html). The founder of Happy Cog, Jeffrey Zeldman, led the project with WordPress's logo designer Jason Santa Maria, and UX designer Liz Danzico making up the rest of the team.

Whereas Shuttle was primarily focused on aesthetics, Happy Cog was to identify and correct information architecture problems, and update and improve WordPress' look and feel. Despite the user-first ethos of the project, the admin screens had become cluttered over time, as new features were added in a relatively haphazard way. The change between the WordPress 1.5 and WordPress 2.3 shows all of the features that have been stuffed into the Pods introduced by Shuttle. If the project took its user-first approach seriously, a redesign of the admin was needed, one that focused on user experience as much as design aesthetics.

<img alt=“WordPress 1.5 write screen“ src="../../Resources/images/28/wp_1_5.png” width=“800px” />

<img alt=“WordPress 2.3 write screen“ src="../../Resources/images/28/wp_2_3.png” width=“800px” />

It was agreed that Happy Cog would produce the designs and the WordPress project would write the code. The scope of the project included user research and an audit of the current interface to identify WordPress' strengths and weaknesses, followed by a new structural design and a new interface design. These designs would then be passed over to the WordPress developers for final implementation.

An unusual aspect of the redesign for a traditional design agency is that the client was a free software project. The team at Happy Cog was mostly sheltered from the goings-on of the community, by both Matt and Jeffery, but that didn't mean that they weren't aware that this was an entirely different type of client. Jason Santa Maria says now:

> Any other client will have customers and their own community, but you really have to just manage the people inside of a company, whereas when you’re dealing with an open source project, you deal with the people that you’re talking with, but there’s this whole gamut of other people that you will only ever get to talk to a small portion of. I think that that’s really difficult.

> Plus, I think that on an open source project like this, it’s inherently different, not just because it’s more of a CMS than an informational website — the design needs are different — but it’s just a different kind of way to work, knowing that whatever you do probably isn’t going to stick around for very long. It’s going to continue to evolve and continue to be adapted. Usually, in the very near-term as well, not even 3-4 months from now, but next week.

The first stage of the process was an audit and usability review of WordPress. Liz Danzico carried out research and produced a 25 page research audit about WordPress. WordPress needed an admin that didn’t intrude on the user. In the audit, she quotes [a post written by Mark Jaquith](http://markjaquith.wordpress.com/2007/02/21/engine-awareness/) in which he says "That’s when I know WordPress is doing its job: when people aren’t even aware they’re using it because they’re so busy using it!"

Liz spoke to Mark Riley, whose experience in the support forums gave him direct access to users' complaints. One of the major problems he highlighted was the clutter that had appeared in the write screen between WordPress 1.2 and WordPress 2.0. Features had been added haphazardly and then tucked into modules using the pods introduced by the Shuttle project. There were lots of actions that a user could take on the Write screen, many of which were confusing or hidden.

Discussion focused on the structure of the navigation, both in terms of the labelling, position, and grouping of functionality. Should they go with an object-oriented navigation (Posts, Pages, Comments, etc) or an action-oriented navigation (Write, Manage, etc). Liz's first hunch, supported by the newly-launched Tumblr, was that users preferred navigating by nouns. She felt that WordPress’ verb structure was confusing. In the first versions of the navigational structure, both a noun version and a verb version were produced. In the end, however, and after limited user testing, the team went with a mixture of nouns and verbs - Write, Manage, Design, Comments. This meant that the functionality for different content types was scattered over different menu items - to write a post, for example, the user would go to "Write" but to manage a post they would navigate to "Manage". 

The Happy Cog team provided extensive and detailed proposals and research for WordPress, all of which was fed back to Matt as the client. Their reports display a sensitivity to web users, and an appreciation of making WordPress more streamlined and simple. 

When it came to the design stage, Jason Santa Maria was tasked with putting together three designs to present to Matt, who would choose one to move forward. 

He designed three early mockups:

<img alt="Happy Cog design 1" src="../../Resources/images/28/happy-cog-design-a.jpg" />

<img alt="Happy Cog design 2" src="../../Resources/images/28/happy-cog-design-b.jpg" />

<img alt="Happy Cog design 3" src="../../Resources/images/28/happy-cog-design-c.jpg" />

The design that Matt chose was the visually lighter one. Jason had taken a lot of the heavy blues introduced by Shuttle and lightened the interface up. The lighter blues were complemented by an orange accent colour.

When the design was finally signed off, WordPress trunk started to transform. As change happened [community feedback](http://lists.automattic.com/pipermail/wp-hackers/2008-February/017849.html)(http://lists.automattic.com/pipermail/wp-hackers/2008-February/017849.html) was [posted to wp-hackers](http://lists.automattic.com/pipermail/wp-hackers/2008-February/017850.html). Was the admin actually more usable? Major changes broke familiar patters. Some comments make comparisons with Shuttle, with community members [still asking for the Shuttle interface](http://weblogtoolscollection.com/archives/2008/01/02/wordpress-24-admin-preview/#comment-1207158). 

Just prior to the release, [a sneak peek was posted to the development blog](http://wordpress.org/development/2008/03/25-sneak-peek/), and WordPress users installed the release candidate to get a better look. The response was similar to that of the rest of the community. Regular WordPress users were surprised by the move of the functionality on the Write screen. For some, it was [a step backwards in terms of usability](http://www.neatorama.com/2008/04/21/wordpress-25-admin-backend-category-shenanigans-and-how-to-fix-it/#!vG29i). 

<img alt="The write screen in the WordPress 2.5 admin" src="../../Resources/images/28/2_5_admin.jpg" />

WordPress 2.4 was the first version to fall significantly behind with the new 120 day release cycle. 2.2 and 2.3 were mostly on schedule, but the Happy Cog redesign brought in major changes to the codebase that meant delaying the release. Rather than just delaying release, a version was skipped, [moving straight from WordPress 2.3 and WordPress 2.5](http://lists.automattic.com/pipermail/wp-hackers/2008-January/016993.html), which was scheduled for release in March. 

But there were bigger problems with the release cycle than the delay. The failure to consult the community created an admin redesign from which the community felt disenfranchised. The community has a stake in the software and its defining look was created without consultation. In some ways, the redesign was destined to fail before it even began. With no participation, no process, there was no way to assure community buy-in. Jeffrey Zeldman, reflecting on the process now says:

> It worked for us, from our perspective, that we were a small team reporting to a single client who had life or death approval over everything. We had to please one user: Matt. He could say yes or no. We completely bypassed the community. That enabled us to get a design done that we felt was crisp and focused and achieved certain goals. And that sounds great. Except that, because the community wasn't involved, inevitably, the design then became unpopular because nobody got their say in it. And if I could go back and do it again, I would involve them up front, and find ways to get my feedback without it turning into a committee clustercuss. 

As with Shuttle before it, there were problems with the design process in the context of the free software project. Free software projects are collaborative enterprises; when part of that process is put behind closed doors to avoid the problems of working by committee, new problems arise. however much a project tries to avoid it, that committee does exist and will always have its say.
	
