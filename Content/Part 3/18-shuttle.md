## 18. Shuttle

As people experimented ways to make money with WordPress, design changes were underway in the interface. Between 2005 and 2006, [wp-design mailing list](http://lists.wordpress.org/pipermail/wp-design/) the WordPress community organized the "Shuttle" project to overhaul WordPress's admin screens. Their aim: to create a coherent, distinct look for WordPress by redesigning wp-admin, which had inherited its design from b2. 

The group's aesthetic refresh reimagined and modernized wp-admin, iterating on the design without re-architecting the interface or adding new features. They started work in the wake of WordPress 1.5, which came out with a set of admin screens ripe for improvement. 

![WordPress 1.5, Strayhorn](../../Resources/images/18/admin1_5.jpg) 

Just as dealing with spam revealed tensions in the development process, Shuttle's work highlighted a pressure point: squaring coherent design and free software development. Design decisions, which are usually highly subjective and individual, seem not to lend themselves to a public process. To work effectively, Shuttle would have to tweak their methods.

 Linus's Law, ([outlined by Eric Raymond](http://www.catb.org/esr/writings/homesteading/cathedral-bazaar/ar01s04.html)), is that "given enough eyeballs, all bugs are shallow." If there's a bug in the software, make it available to many people; someone will see the solution. For an issue with a defined answer, this can speed up progress considerably. Design being more subjective, however, Shuttle designers worried that an open process would lead to too many cooks in the kitchen, and that competing opinions would lead to stalemate. 
 
Unlike WordPress's core developers, the Shuttle group communicated via private mailing list. This list was open, but list archives weren't public. To be involved, a contributor had to be added to the group, and the group had to agree to add the new member. Discussions among members indicate that they deliberately tried to keep the group limited. "An open mailing list would become so much noise and so little signal so quickly that there would be no way we could move forward," [recalls Chris Davis now](http://archive.wordpress.org/interviews/2013_11_18_Davis.html#L91). 

The group remained small, with three main designers (Michael, Joen, and Khaled) and coders responsible for realizing the design vision. The group sent designs around among themselves, offered feedback on one another's work, and iterated on the design. They focused on specific elements, mainly the Post screen (`post.php`). Over the course of the project, 28 versions circulated among this group.

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

Another iteration of the `post.php` screen collapsed elements like post status, categories, and author.

In WordPress 1.5:

<img alt="Functionality on Write screen in WordPress 1.5" src="../../Resources/images/18/pods_wp_1_5.jpg" width="200px" />

In version 8 of Shuttle:

<img alt="Version 8 of Shuttle with mocked up pods" src="../../Resources/images/18/pods_shuttlev8.jpg" width="200px" />

In WordPress 2.0:

<img alt="WordPress 2.0 Pods" src="../../Resources/images/18/pods_wp_2.jpg" width="200px" />

When WordPress 2.0 shipped with Shuttle-inspired changes, the feedback wasn’t entirely positive. [Molly Holzschlag wrote that](https://web.archive.org/web/20060203042213/http://www.molly.com/2006/01/05/wordpress-20-and-akismet/) "what WP2.0 has gained in interface appeal it's lost in some practicality too." For the Shuttle team, the problem with WordPress 2.0 was the [piecemeal implementation of their vision](http://lists.wordpress.org/pipermail/wp-design/2006-January/000559.html).

The project was beset by other problems. Despite the closed mailing list, progress stalled without a clear leader -- one person charged with the project's overall vision. When one skims the mailing list's archives today, it reads like a design-focused discussion forum rather than the communications of a focused team with a clear task. As the Shuttle team discovered, a group of independent designers, each with their own ideas, can trip up design work as surely as a mailing list full of hackers.

It took the group a long time to complete work. They discussed minor design elements like rounded corners and gradients for lengthy periods, rather than examining fundamental questions about WordPress users' needs and wants. "I don’t know if we were cooperating enough on getting a unified feel and a unified understanding of everything before we were trying to actually apply our ideas to the problem," [says Michael now](http://archive.wordpress.org/interviews/2013_11_06_Heilemann.html#L74). Besides that, the contributors had jobs that absorbed their time, so work happened in fits and starts. While the original plan was to complete the admin redesign within three months, by mid-April 2005, this slid to September. The team eventually [missed the deadline for WordPress 2.0](http://lists.wordpress.org/pipermail/wp-design/2005-November/000502.html) in late 2005. The next deadline (for inclusion in WordPress 2.1, which itself never materialized) was the end of January, though it was March 2006 before a complete set of mockups arrived.

It was then that Khaled sent out a complete set of screenshots with his vision for the new WordPress admin:

![Shuttle Dashboard](../../Resources/images/18/shuttlefinal/Dashboard.jpg) 

![Shuttle Write Screen](../../Resources/images/18/shuttlefinal/Write.jpg) 

The rest of the group loved the designs, and the developers began coding. Still, development dragged on. In mid-April, [Michael Heilemann withdrew from the project](http://lists.wordpress.org/pipermail/wp-design/2006-April/000721.html), saying that he had to prioritize other commitments. The same month, [Khaled asked](http://lists.wordpress.org/pipermail/wp-design/2006-April/000723.html) whether Matt or Ryan would ever get around to implementing the design. [The response](http://lists.wordpress.org/pipermail/wp-design/2006-April/000730.html) placed the redesign as a medium priority. Changes would be iterative. 

On May 14th 2006, [Khaled posted a complete set of designs to his blog](https://web.archive.org/web/20061105004935/http://www.brokenkode.com/archives/shuttle-launched/), bringing the Shuttle project to a close. He was still under the impression that the mockups would be implemented in due course. They never were. Khaled and other members of the group felt disenfranchised. They drifted away from the community. Chris Davis and Michael Heilemann made the switch from WordPress to the Habari project.

The biggest failure of Shuttle project wasn't the designs or implementation, but the process itself. To solve one problem, the group closed itself off from the community -- which created a new set of problems. Isolated from the larger community, they lost touch with the development process. The project's closed nature limited opportunities for other enthusiastic designers to step in and move the work forward. For each person excited to see a spectacular WordPress redesign, there was another person resentful that a blessed group of designers was working on something  everyone had a stake in.

In one of the final emails on the wp-design mailing list, [Matt outlined](http://lists.wordpress.org/pipermail/wp-design/2006-May/000732.html) some of the things that he learned about design-oriented free software projects:

> * Work should not be done in private
> * Design by committee doesn't work, better to break up tasks and let individual people focus on one section
> * Focus on lots of incremental changes, rather than giant redesigns (you end up in the same place, and probably sooner)
> * Document the process and decisions along the way
> * Code concurrently with the designs (and iterate)
> * Don't hype it, expectations get out of control
> * Avoid scope creep of features into designs
> * Set a deadline and stick to it

These tenets influenced the relationship between WordPress design and development, helping future design projects avoid the difficulties faced by the Shuttle group.
