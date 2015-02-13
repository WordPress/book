## 18. Shuttle

As people experimented with how to make money with WordPress, experiments also took place in the interface design. WordPress inherited its look from b2. Between 2005 and 2006, [wp-design mailing list](http://lists.wordpress.org/pipermail/wp-design/) members overhauled the admin screens, in a project called Shuttle. Their aim: to create a coherent brand for WordPress by redesigning wp-admin. 

The group focused on an aesthetic refresh to reimagine and modernize wp-admin -- as opposed to a functional refresh --  i.e., iterating the design rather than re-architecting the interface or adding new features. They started work in the wake of WordPress 1.5, which came out with a set of admin screens in need of some love. 

![WordPress 1.5, Strayhorn](../../Resources/images/18/admin1_5.jpg) 

Unlike WordPress Core development, the Shuttle group communicated via private mailing list. This list was open to other members but the list archives weren't public. To get involved, a contributor had to be added to the group, and the group had to agree to add the new member. Discussions among members indicate that they weren’t keen for too many people to join.

This highlights one of the tensions between design -- which is usually a private process that leads to a finished design presented to the world -- and free software development. Linus's Law ([as outlined by Eric Raymond](http://www.catb.org/esr/writings/homesteading/cathedral-bazaar/ar01s04.html)) is that "given enough eyeballs, all bugs are shallow." If there is a problem, get lots of eyes on it; it will be transparent to someone. This approach works with bugs or a coding problem with a clear answer.

Design, however, is much more subjective, and the Shuttle project designers felt that opening up the design process to anyone would lead to a "too many cooks" situation. "A mailing list like that," [recalls Chris Davis now](http://archive.wordpress.org/interviews/2013_11_18_Davis.html#L91), "would become so much noise and so little signal so quickly that there would be no way we could move forward." 

To avoid this scenario, the group remained small, with three main designers (Michael, Joen, and Khaled) and coders responsible for realizing the design vision. The group worked from a set of PSDs and sent designs around among themselves. They offered feedback on each other's work and iterated on the design. They worked on design specific elements, mainly the Post screen (`post.php`). Over the project, 28 different versions circulated via the mailing list.

Version 8

![Shuttle version 8](../../Resources/images/18/shuttlev8.jpg) 

Version 14

![Shuttle version 14](../../Resources/images/18/shuttlev14.jpg) 

Version 21

![Shuttle version 21](../../Resources/images/18/shuttlev21.jpg) 

Version 26

![Shuttle version 26](../../Resources/images/18/shuttlev26.jpg) 
 
As the design process continued, elements of Shuttle were implemented in WordPress. One of the earliest Shuttle designs increased the size of the title field in the `post.php` edit screen.

In WordPress 1.5:

<img alt="WordPress post functionality in 1.5" src="../../Resources/images/18/write_post_title_1_5.jpg" width="600px" />

In Shuttle:

<img alt="Shuttle design February 2005" src="../../Resources/images/18/write_post_title_shuttle.jpg" width="600px" />

WordPress 2.0:

<img alt="WordPress 2.0 write post screen" src="../../Resources/images/18/write_post_title_2_0.jpg" width="600px" />

Pods in the `post.php` screen, which collapsed elements such as post status, categories, and author, was another iteration.

In WordPress 1.5:

<img alt="Functionality on Write screen in WordPress 1.5" src="../../Resources/images/18/pods_wp_1_5.jpg" width="200px" />

In version 8 of Shuttle:

<img alt="Version 8 of Shuttle with mocked up pods" src="../../Resources/images/18/pods_shuttlev8.jpg" width="200px" />

In WordPress 2.0:

<img alt="WordPress 2.0 Pods" src="../../Resources/images/18/pods_wp_2.jpg" width="200px" />

When WordPress 2.0 shipped with Shuttle-inspired changes, the feedback wasn’t entirely positive. [Molly Holzschlag wrote that](https://web.archive.org/web/20060203042213/http://www.molly.com/2006/01/05/wordpress-20-and-akismet/) "what WP2.0 has gained in interface appeal it's lost in some practicality too." For the Shuttle team, the problem with WordPress 2.0 was the [piecemeal implementation of their vision](http://lists.wordpress.org/pipermail/wp-design/2006-January/000559.html).

The project was beset by other problems. Despite having a closed mailing list to avoid the "too many cooks" problem, that problem arose anyway. The group's structure made no one person responsible for the project's overall vision. Ideas were discussed and sent around. When one reads the mailing list now it feels like a design-focused discussion forum rather than a team with a clear task. As the group discovered, having a group of designers, each with their own ideas, can cause as many problems as opening a design mailing list up to a bunch of hackers.

It took the group a long time to complete work. They discussed minor design elements such as rounded corners and gradients for lengthy periods, rather than pose fundamental questions about WordPress users' needs and wants. "I don’t know if we were cooperating enough on getting a unified feel and a unified understanding of everything before we were trying to actually apply our ideas to the problem," [says Michael now](http://archive.wordpress.org/interviews/2013_11_06_Heilemann.html#L74). Besides that, the contributors had jobs that absorbed their time, so work happened in fits and starts. While the original plan was to complete the admin redesign within three months (by mid-April 2005) this slid to September. The team eventually [missed the deadline for WordPress 2.0](http://lists.wordpress.org/pipermail/wp-design/2005-November/000502.html) in late 2005. The next deadline (for inclusion in WordPress 2.1, which itself never materialized) was the end of January, though it was March 2006 before a complete set of mockups arrived.

It was then that Khaled sent out a complete set of screenshots with his vision for the new WordPress admin:

![Shuttle Dashboard](../../Resources/images/18/shuttlefinal/Dashboard.jpg) 

![Shuttle Write Screen](../../Resources/images/18/shuttlefinal/Write.jpg) 

The rest of the group loved the designs. They set the developers to coding. As with the rest of the project, development dragged on. In mid-April, [Michael Heilemann withdrew from the project](http://lists.wordpress.org/pipermail/wp-design/2006-April/000721.html), saying that he had to prioritize other commitments. The same month, [Khaled asked](http://lists.wordpress.org/pipermail/wp-design/2006-April/000723.html) whether Matt or Ryan would ever get around to implementing the design. [The response](http://lists.wordpress.org/pipermail/wp-design/2006-April/000730.html) placed the redesign as a medium priority. Changes would be iterative. 

On May 14th 2006, [Khaled posted to his blog](https://web.archive.org/web/20061105004935/http://www.brokenkode.com/archives/shuttle-launched/), finally sharing the complete set of designs with the WordPress community, bringing the Shuttle project to a close. He was still under the impression that the mockups would be implemented in due course. They never were. Khaled and other members of the group felt disenfranchised. They drifted away from the community. Chris Davis and Michael Heilemann made the switch from WordPress to the Habari project (which was conceived in September 2006).

The biggest failure around the Shuttle project, wasn't the designs, nor even design implementation, but the process itself. To solve one problem, the group closed itself off from the community but in doing so new problems arose. Cut off from the rest of the community they lost touch with the development process. The project's closed nature meant that when life took over and activity slowed there was no opportunity for another enthusiastic party to take on the work. The wider community had diverging feelings about the project -- its secret nature gave it a sense of mystery. There was hype and an expectation for a spectacular WordPress redesign. But for others there was growing resentment that a blessed group of designers was working on something that everyone had a stake in.

In one of the final emails on the wp-design mailing list, [Matt outlined](http://lists.wordpress.org/pipermail/wp-design/2006-May/000732.html) some of the things that he learned about design-oriented free software projects:

> * Work should not be done in private
> * Design by committee doesn't work, better to break up tasks and let individual people focus on one section
> * Focus on lots of incremental changes, rather than giant redesigns (you end up in the same place, and probably sooner)
> * Document the process and decisions along the way
> * Code concurrently with the designs (and iterate)
> * Don't hype it, expectations get out of control
> * Avoid scope creep of features into designs
> * Set a deadline and stick to it

These things influenced the relationship between design and development, and future design projects tried to avoid the difficulties faced by the Shuttle group.
