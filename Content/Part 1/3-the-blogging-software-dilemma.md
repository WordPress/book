## 3. The Blogging Software Dilemma

The internet brings people from different backgrounds, different countries, different cultures, together around a shared interest. On a small corner of the internet, the b2 community was one of the places where this happened. People supported one another because they were interested in two things - blogging and blogging software. 

The founders of WordPress were among those drawn into the community. From very different backgrounds, their similarities were drawn out by software. Matt Mullenweg, from Houston used his blog to write about politics, economics, and technology, weaving through that his passions - jazz music and photography.  Mike Little, from rainy Stockport, wrote about blogging technology, the books that he read, and his family. 

They both had very different entries into computing: Matt first started tinkering with computers at an early age, through his father who was a computer programmer. Mike, twenty-two years older than Matt, had his first experience of computers at school, cut short when a teacher caught he and his friends smoking in the paper room. 

It was a shared passion, however, that drew them both deeper into programming. Mike was involved in the Manchester music scene in the 1980s, working at a record shop and handing out ‘zines for nightclub manager and record producer Tony Wilson. He lived with a local glam rock band, and it was through them that computing came back into his life. The lead singer thought it would be cool to have stacks of televisions with graphics on either side of the stage. Mike borrowed a ZX Spectrum and used a couple of programs from  computing magazines: one of them bounced objects around the screen, the second created 3D text. He hacked them together until he got the words he wanted to bounce around a screen, but the plan fell flat when they couldn’t figure out how to output the program to multiple screens at the same time. Despite not being a total success, this incident further cemented his reputation for being the go-to guy for all things computing and music.

By the time he arrived at b2, Mike had nearly twenty years of programming experience. That first faltering step with the ZX Spectrum, had started a love affair with coding, which took him on a route through Basic, 6502 Assembler, Pascal, and C, learning PHP during the transition between PHP versions one and two.

In Houston, Matt set up his first business while studying at the High School for the Performing and Visual Arts (HSVPA). While Mike’s music passion was post-punk, for Matt it was jazz. He built computers and websites for his music teachers, including his saxaphone teacher, [David Caceres](http://web.archive.org/web/20020329153221/http://davidcaceres.com/). He also used the internet to connect other music fans in the Houston area, setting up a [forum on David Caceres'] (http://web.archive.org/web/20020202222327/http://davidcaceres.com/forum/) website. For this he used the forum software phpbb, which gave him his first taste of using PHP to create a dynamic website.


Since they both had experience in PHP, b2 was the perfect platform for publishing their content and for letting loose with their hacker tendencies. Matt did try out some other platforms. He tried Movable Type but it didn’t have pingbacks and comments were in pop-ups as opposed to being inline. Also Movable Type was written in Perl with a DBD database, which meant that customizing Movable Type was more difficult than a PHP platform.


PHP & MySQL allowed Mike and Matt to scratch both their blogging and their hacking itches. They could hack on their websites and customize them how they wanted. They shared those hacks and improements to the community. Matt and Mike’s first interaction was when Mike asked Matt about the gallery software he used on his blog. Other developers had their own itches to scratch. Developers were talking about building their own platforms. Others, in the absence of Michel, were considering a fork.
—


 b2 was free and open source software, licensed under the GPL; anyone could fork the code and make use of it, provided their fork retained the license. It was clear that Michel would not be back, No one was maintaining b2, no one was fixing security issues. The blogging software at the core of the growing community was no longer evolving. The web, and blogging, was moving forward, but b2 had lost its driving forces. In France, Francois Planque [forked b2 to create b2evolution](http://fplanque.net/Blog/devblog/2003/05/10/b2_evolution_new_features_summary). The lack of b2 development frustrated Francois and he wanted to continue to develop b2 for his own needs. 

In Cork, on the west coast of Ireland, Donncha Ó Caoimh, [donncha](http://profiles.wordpress.org/donncha/), forked b2 to create b2++, a multi-user blog platform. Donncha discovered b2 while searching for a platform to create a blog network for his Linux user group. He found b2 small, basic, and easy to modify. However, he made major modifications to [create blogs.linux.ie](http://web.archive.org/web/20030302025915/http://blogs.linux.ie/). b2++'s templating system used [Smarty](http://www.smarty.net/), which separated code and presentation, making it easier for users on the network to change their site's design. Donncha didn't consider b2++ as a fork of b2.  "A fork gives the impression that it was competing --- it wasn't competing because most of the things it did was add multi-user aspects to the project." b2 was a platform aimed at individual bloggers, but everything that Donncha did in b2++ created a better multi-user environment.




And on his blog, Matt wrote a post called "[The Blogging Software Dilemma](http://ma.tt/2003/01/the-blogging-software-dilemma/)," in which he proposes forking b2. He wrote:

> b2/cafelog is GPL, which means that I could use the existing codebase to create a fork, integrating all the cool stuff that Michel would be working on right now if only he was around. The work would never be lost, as if I fell of the face of the planet a year from now, whatever code I made would be free to the world, and if someone else wanted to pick it up they could. I've decided that this (sic) the course of action I'd like to go in, now all I need is a name. What should it do? Well, it would be nice to have the flexibility of Movable Type, the parsing of Textpattern, the hackability of b2, and the ease of setup of Blogger. Someday, right?

The next day, from Stockport, UK, Mike Little, [mikelittle](http://profiles.wordpress.org/mikelittle), responded:

> If you're serious about forking b2 I would be interested in contributing. I'm sure there are one or two others in the community who would be too. Perhaps a post to the b2 forum, suggesting a fork would be a good starting point.

Today, the post that started WordPress gets a lot of traffic as people link to it on the software’s anniversary. But for more than a year it sat there with just one post and one comment, a marker of the very early days of the project, when for a few months just Matt and Mike, In their homes at opposite sides of the Atlantic, wrote WordPress. It was, at the beginning, just two developers, working on a small script to make their blogs better. By forking b2 they could continue to use the software, and develop it for their own needs, to scratch their own itches. At that moment, in a small pocked of the internet, the right people connected. They may have been from completely different backgrounds, but a shared love of creating tools, playing with code, and publishing online, brought them together.

On April 1st, 2003, Matt created a [new branch of b2 on SourceForge](http://cafelog.cvs.sourceforge.net/viewvc/cafelog/), and, with the name coined by his friend Christine Tremoulet, called it WordPress.
