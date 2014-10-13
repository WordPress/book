## 28. Happy Cog Redesign

With the taxonomy system in place, the next major change was to be a new redesign of the admin screens, touted to appear in WordPress 2.4.  There was still the occasional question about whether the designs created by the Shuttle Group would be implemented, but by then the project had moved on and it was [design studio Happy Cod, who were to carry out a total redesign of the admin](http://lists.automattic.com/pipermail/wp-hackers/2007-November/016123.html). The founder of Happy Cog, Jeffrey Zeldman, led the project with WordPress's logo designer Jason Santa Maria, and UX designer Liz Danzico making up the rest of the team.

Whereas Shuttle was primarily focused on aesthetics, Happy Cog was brought in to both identify and correct information architecture problems and update and improve WordPress' look and feel. Despite the user-first ethos of the project, the admin screens became cluttered over time, as new features were added in a relatively haphazard way. The change between WordPress 1.5 and WordPress 2.3 was dramatic, with more and more being added to the post editing screen.[ perhaps add a comparison image here] It was clear that if the project wanted to be seen to be taking the user-first approach seriously, a redesign of the admin was needed, one that focused on the user experience as much as the design aesthetics.

In an unusual move for Happy Cog, they would produce the comps while the WordPress project would write the code. The scope of the project included user research and an audit of the current interface to identify WordPress' strengths and weaknesses, followed by a new structural design and a new interface design. These designs would then be passed over to the WordPress developers for final implementation.

The other unusual aspect of the project for a traditional design agency was that the client was an open source project. The team at Happy Cog was mostly sheltered from the goings-on of the community, by both Matt and Jeffery, but that didn't mean that they weren't aware that this was an entirely different type of client. Jason Santa Maria says now:[ maybe add a quote from Zeldman]

> Any other client will have customers and their own community, but you really have to just manage the people inside of a company, whereas when you’re dealing with an open source project, you deal with the people that you’re talking with, but there’s this whole gamut of other people that you will only ever get to talk to a small portion of. I think that that’s really difficult.

> Plus, I think that on an open source project like this, it’s inherently different, not just because it’s more of a CMS than an informational website — the design needs are different — but it’s just a different kind of way to work, knowing that whatever you do probably isn’t going to stick around for very long. It’s going to continue to evolve and continue to be adapted. Usually, in the very near-term as well, not even 3-4 months from now, but next week.

The first stage of the process was an audit and usability review of WordPress. During this stage, Liz Danzico carried out research and produced a 25 page research audit about WordPress. The intention was to create an admin which would get out of the way. She quotes [a post written by Mark Jaquith](http://markjaquith.wordpress.com/2007/02/21/engine-awareness/) in which he says "That’s when I know WordPress is doing its job: when people aren’t even aware they’re using it because they’re so busy using it!"

Liz spoke to Mark Riley, whose experience in the support forums meant that he had direct access to users' complaints. One of the major problems he highlighted was that more and more functionality had been packed into the write screen. Between  WordPress 1.2 and WordPress 2.0 the admin had become cluttered. Functionality had been added haphazardly and then tucked into modules using the pods introduced by the Shuttle project. This meant that there were all sorts of actions that a user could take on the Write screen, many of which were confusing or hidden.

A lot of the group’s discussion focused on the structure of the navigation, both in terms of the labelling, position, and grouping of functionality. Long discussions were had about whether to go with an object-oriented navigation (Posts, Pages, Comments, etc) or an action-oriented navigation (Write, Manage, etc). Liz's first hunch, supported by the newly-launched Tumblr, was that users preferred navigating by nouns. She felt that what was so confusing to users was that WordPress was organised by verbs. When it came to putting together the navigational structure, both a noun version and a verb version was used. In the end, however, and after limited user testing, the team went with a mixture of nouns and verbs - Write, Manage, Design, Comments. This meant that the functionality for different content types was scattered over different menu items - to write a post, for example, the user would go to "Write" but to manage a post they would navigate to "Manage". 

The Happy Cog team provided extensive and detailed proposals and research for WordPress, all of which was fed back to Matt as the client. Their reports display a sensitivity to web users, and an appreciation of making WordPress more streamlined and simple. 

When it came to the design stage, Jason Santa Maria was tasked with putting together three designs to present to Matt, who would choose one to move forward. 

He designed three early mockups for Matt to choose from:

<img alt="Happy Cog design 1" src="../../Resources/images/design/happy-cog-design-a.jpg" />

<img alt="Happy Cog design 2" src="../../Resources/images/design/happy-cog-design-b.jpg" />

<img alt="Happy Cog design 3" src="../../Resources/images/design/happy-cog-design-c.jpg" />

The design that Matt chose was the visually lighter one. Jason had taken a lot of the heavy blues introduced by Shuttle and lightened the interface up. The lighter blues were complemented by an orange accent colour.

When the design was finally signed off, WordPress trunk started to transform and [not everyone was pleased with the changes](http://lists.automattic.com/pipermail/wp-hackers/2008-February/017849.html) [with the changes](http://lists.automattic.com/pipermail/wp-hackers/2008-February/017850.html). There were questions about whether the admin would actually be more usable. There were major changes to the admin, that broken with many of the familiar patterns that had been set up by WordPress. Among the [most dissatisfied were those who had been involved with Shuttle](https://web.archive.org/web/20071024231530/http://www.brokenkode.com/archives/new-wordpress-admin/). Many of the comments made comparisons with Shuttle, with community members [emphatically requesting that Shuttle be the new interface](http://weblogtoolscollection.com/archives/2008/01/02/wordpress-24-admin-preview/#comment-1207158). 

Just prior to the release of 2.5, Matt [posted a sneak peek on the development blog](http://wordpress.org/development/2008/03/25-sneak-peek/). This spurred WordPress users into installing the release candidate to get a better look. The response was mixed. [One user talked about the things that bothered him](http://astheria.com/design/evaluating-the-wordpress25-interface) - moving functionality on the post screen to below the post field, for example, and the precedence of the design tab - things which people who used WordPress every day easily picked up on. For many people, especially experienced bloggers, it was [a step backwards in terms of usability](http://www.neatorama.com/2008/04/21/wordpress-25-admin-backend-category-shenanigans-and-how-to-fix-it/#!vG29i). 

<img alt="The write screen in the WordPress 2.5 admin" src="../../Resources/images/design/2_5_admin.jpg" />

While 2.2 was delayed due to removing taxonomies, the first version to fall significantly behind with the new 120 day release cycle was WordPress 2.4. 2.2 and 2.3 were mostly on schedule, but the Happy Cog redesign caused major changes to the codebase that meant delaying the release. Rather than straightforwardly delaying release, the development team decided to skip a version and [move straight from WordPress 2.3 and WordPress 2.5](http://lists.automattic.com/pipermail/wp-hackers/2008-January/016993.html), which was scheduled for release in March. This was the last time that a WordPress release was delayed.[ this closing could do with more work
]	


