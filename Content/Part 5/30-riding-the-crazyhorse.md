

## 30. Riding the Crazyhorse

WordPress 2.7 brought in what Ryan Boren describes as “the modern era of WordPress.” It also brought a new face to the WordPress project. When the reaction to WordPress 2.5's redesign was less than positive, it was unclear whether the problem was inherent to the user interface, or whether people didn’t like it because they felt cut out of the process. Jen Mylo ([jenmylo](http://profiles.wordpress.org/jenmylo)) [^fn-1], an old friend of Matt, was running a usability testing and design center at a New York agency in conjunction with Ball State University. The center ran usability studies and made use of the latest eye-tracking technologies. The agency’s clients included big companies like television networks such as ABC, NBC, and MTV. When a TV network didn’t have a product ready in time for a usability test window, Jen offered the slot to WordPress at cost. 

The usability review had three main stages done in two rounds. In Round 1, WordPress 2.5 was tested, and recommendations made on "low hanging fruit" improvements to the admin. Following that, the development team created a prototype (Test1515) based on the recommendations to see if they improved users' experiences. Finally, based on the Test1515 findings, the Crazyhorse prototype was created and tested in Round 2.

The research team used three main testing methods in Round 1:

1. Talk-aloud, in which the participants are asked to think aloud as they carry out tasks.
2. Morae Software screen activity and video recordings of participants, which enables researchers to watch remotely.
3. Eye-tracking technology to identify granular problems.

The [twelve participants](http://en.blog.wordpress.com/2008/05/20/new-york-usability-testing/) tested a range of activities within WordPress' admin. In Round 1, despite finding WordPress generally easy-to-use, the researchers identified a number of problems, including:

1. Verbs vs nouns: users found it difficult to conceptualize tasks as action-oriented (Write/Manage). Instead, they perceived content in a more object-oriented way. (Posts, Pages, Comments, etc.)
2. Users didn't spend time on the Dashboard. They used it as an entry point for other pages.
3. The write post screen caused problems for users. Tags and categories appeared below the fold, and some participants forgot to add categories and tags before publication, returning to the post screen to add them afterward. 
4. The comments screen was confusing. Users weren't aware that they had to click a commenter's name to edit a comment, and when asked to move a comment to spam they looked in the wrong place.
5. The difference between uploading and embedding media in the media uploader confused users.

They also discovered minor issues around settings, the media library, link categories, and tag management. Users also demonstrated a desire to have more control over the modules on the dashboard and the post edit screen, for example.

The [usability test report](https://github.com/WordPress/book/blob/master/Resources/articles/2008_07_Usability_Report_Crazyhorse.pdf) says the following:

> In addition to a laundry list of small interface issues that presented simple fixes, such as changing comment author links, we were faced with larger issues such as the desire for user-determined hierarchies on long/scrolling screens, ambiguity in the Write/Manage navigation paradigm, and a disconnect between the act of adding media to a post and the ability to manage it.

While minor changes were incorporated into the Test1515 prototype and tested, they were so minor that participants didn't have a strong reaction either way. The team decided to create a more drastic prototype -- dubbed Crazyhorse -- to achieve the following:

- maximize vertical space, 
- reduce scrolling, 
- increase access to navigation to reduce unnecessary screen loads, 
- enable drag and drop on screens that would most benefit from user control, and
- redesign management screens to take advantage of natural gaze paths.

<img alt="Crazyhorse sketches and navigation planning" src="../../Resources/images/30/crazyhorse-process.jpg" />

Jen and Liz Danzico, who continued to work on WordPress’ usability in the Crazyhorse project, created the design for the prototype. They sketched multiple ideas: front-end editing, accordion panes, and a top navigation. They chose the simplest prototype: a left hand navigation panel, similar to Google Analytics and other web apps.

WordPress [developers built the Crazyhorse prototype in a Subversion branch](http://lists.wordpress.org/pipermail/wp-hackers/2008-June/020652.html), [based on the prototype document](http://ma.tt/dropbox/2008/06/wordpress-prototype-1.1.pdf) which outlined the changes and their rationale. The project focused on user experience and functional development, so the prototype retained WordPress 2.5's visual styles. As in Round 1 testing, participants carried out tasks, and progress was assessed using talk-aloud, Morae, and eye-tracking. 

Most responses demonstrated a preference for Crazyhorse over WordPress 2.5 and every new feature tested provided actionable information for the next version of WordPress. 

Participants loved the navigation's new position, at the left-hand side of the screen, for example. They also preferred the object-oriented approach to organization. (Posts, Pages, Media, etc.) 

<img alt="Crazyhorse write screen prototype" src="../../Resources/images/30/crazyhorse-prototype-dashboard.jpg" />

The new Dashboard was considered more useful, and people liked the ability to customize it. They liked QuickPress, though they weren't sure if they would use it. With action links now positioned under the comments, users found it easier to edit and act on comments. 

<img alt="Crazyhorse write screen prototype" src="../../Resources/images/30/crazyhorse-prototype.jpg" />

The new Write screen had a drag and drop feature, which allowed users to decide which elements got prime screen real estate. They also liked having access to post comments and felt that the new media uploader -- with its clear integration with the media library -- was a huge improvement.

<img alt="The bottom publish bar in the crazyhorse prototype" src="../../Resources/images/30/crazyhorse-prototype-publish.jpg" />

A publishing bar that floated at the bottom of the screen received the only major negative reactions. Users tended to look at the bar a few times before realizing it contained the Publish button. Some users compared it to a banner ad or thought it was part of their browser. 

While Happy Cog and project Crazyhorse undertook user research, they ended up with quite different results. For Happy Cog, Liz conducted a series of interviews with community members. Later she conducted in-person user testing. The Crazyhorse project, however, used eye-tracking technology. This meant that the testers didn't have to rely solely on what participants said; instead they had insight into what the participants were looking at while they were making statements. Not only that, but gaze trails provided insight into how users navigated the screen with their eyes -- where were they drawn first? Were they missing important UI elements? Did they understand what they were seeing?

With the success of the prototypes, the design layer was the next step. When Crazyhorse was [first merged with trunk](https://core.trac.wordpress.org/ticket/7552) it was just a set of live wireframes. No design changes were presented, which prevented participants from being swayed by color or typeface preference. By the Automattic meetup in Breckenridge, Colorado, in 2008, Crazyhorse was ready for some color. 

At Automattic meetups, the company splits up into small groups to work on projects assigned at the beginning of the week. Everyone received assignments, and Matt Miklic, MT, ([iammattthomas](http://profiles.wordpress.org/iammattthomas)) [^fn-2] got Crazyhorse and free rein to give it the coat of paint it needed. Jen and MT spent the entire week redesigning the admin, producing many designs: a heavy blue reminiscent of Shuttle-inspired WordPress, and a version that used the light blue, grays, and orange of Happy Cog. In the end the two melded into a gray color scheme that became a feature of WordPress until 2013. Crazyhorse brought a huge number of changes to WordPress, with a completely transformed admin. To deal with all of these changes, Andrew Ozz ([azaozz](http://profiles.wordpress.org/azaozz)) was given commit access.

A marked distinction between the Happy Cog and Crazyhorse processes was Jen's connection with the community. She kept the community abreast of what was going on. The testing was carried out as an adjunct to the WordPress project, with little community involvement; the reason for testing was to verify actual usability flaws versus whether people simply didn't like the new design. If it had been just a matter of user color preferences, the Crazyhorse project would have come to nothing. But when it became obvious that the WordPress interface did need to change, a dialogue began in the community. The [designs](http://wordpress.org/news/2008/10/the-visual-design-of-27/) and the [usability report](http://wordpress.org/news/2008/10/usability-testing-report-25-and-crazyhorse/) were shared on the development blog. The team surveyed users on [navigation options](http://wordpress.org/news/2008/09/wordpress-27-navigation-options-survey/), and [the community discussed issues on the wp-hackers mailing list](http://lists.wordpress.org/pipermail/wp-hackers/2008-October/021944.html). When WordPress 2.7 released, the [launch post](http://wordpress.org/news/2008/12/coltrane/) lists the posts Jen and the developers wrote about the process. Up to that point, it is the only iteration of the WordPress admin to have such an information trail.

With the Crazyhorse project, WordPress' admin changed drastically -- twice in 2008 alone. When [screenshots of the changes made their way onto community blogs](http://weblogtoolscollection.com/archives/2008/09/02/first-look-at-wordpress-27/), the inevitable question was "why are they changing it again?" WordPress 2.5's design hadn't settled in before another huge change came about in 2.7. A change in the UI meant that users of varying skill levels needed to completely relearn how to use WordPress. Not only that, with the growing community of people who had created tutorials with screenshots and videos on how to use WordPress, every screenshot would need to be retaken, every video re-shot. However, when WordPress users started upgrading the [feedback was positive](http://lorelle.wordpress.com/2008/12/10/wordpress-27-available-now/#comments). Users loved the new interface; they found it intuitive and easy to use, finally demonstrating that it wasn't change they had been unhappy with just nine months earlier, but the interface itself.

<img alt="The write screen in the WordPress 2.7 admin" src="../../Resources/images/30/2_7_admin.jpg" />

There were other major changes in WordPress 2.7. The WordPress Plugin Repository arrived on the admin screen. Users no longer had to download a plugin and upload it using FTP. They could search the plugin directory for the features they needed right from their admin, and install the plugin with just a few clicks. This made it much easier for WordPress users to quickly find and install plugins, removing the barrier to entry that came with FTP. There were also improvements to WordPress’ documentation. In December 2006, Matt had posted to wp-hackers, [apologizing for his stance on inline documentation](http://lists.automattic.com/pipermail/wp-hackers/2006-December/009812.html). [Inline documentation patches](http://core.trac.wordpress.org/ticket/2474#comment:7) were [committed to core](http://core.trac.wordpress.org/ticket/2473#comment:3). In WordPress 2.7 [PHPDocumentor was added](http://lists.wordpress.org/pipermail/wp-docs/2008-October/001769.html), through a big push by Jacob Santos ([jacobsantos](https://profiles.wordpress.org/jacobsantos/)) and Jennifer Hodgdon ([jhodgdon](https://profiles.wordpress.org/jhodgdon)) to get WordPress functions documented in the code. There was also the beginning of an [official user handbook](http://lists.wordpress.org/pipermail/wp-docs/2009-January/001862.html).	

After completing the Crazyhorse redesign Jen joined Automattic to work on WordPress. At that time, the project was still small -- bigger than the early days of the cluster of bedroom hackers who built the platform, but not as big nor as diverse as it is today. There was a close group of Core developers who led the project working in IRC and a Skype chat room. In [October 2008, Jen first appeared on wp-hackers](http://lists.wordpress.org/pipermail/wp-hackers/2008-October/021899.html). She brought fresh eyes and a completely new perspective to the project. So far the project had been run by a group of hackers, many of whom were sympathetic to user needs, but who weren’t always able to put themselves in users' shoes. Jen had a background in user testing and user experience -- something largely absent in the community until she joined the project. “Having someone with an actual formal training in testing and user experience, it was just useful,” [says Mark Jaquith now]( http://archive.wordpress.org/interviews/2013_11_22_Jaquith.html#L7)1. “It was not just useful then, but it also changed us. Or at least it changed me. Where I started thinking in these ways as well and becoming better at stepping out of my own head.”

This new focus on user testing and user experience meant that the project was able to hone its focus on users. With the number of WordPress users growing, this meant ensuring that the software didn’t just work for a small group of bloggers but for everyone who wanted to install it.

[^Fn-1] At that time Jen Mylo’s name was Jane Wells. Her name changed in 2014.
[^fn-2] At that time Matt Miklic’s name was Matt Thomas. His name changed in 2014.
