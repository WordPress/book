Prior to getting involved with b2, Mike Little had already contributed to free software projects. He’d submitted patches to the version control system CVS and the DJGPP compiler, and bug reports to database software MySQL. So when it came to choosing his blogging software, the license played a big part in his decision. Movable Type, for example, was not an option because it wasn’t GPL. With his background in coding, he had become accustomed to software-sharing and to working on someone else’s code to make it your own. But it was while he was working on DJGPP that he first learned about GNU and the ideas behind the GPL. “I learned about Richard Stallman and read his story,” he says. “he instilled those four principles that just sort of inspired me.”

The principles that inspired Mike have inspired thousands of software developers. They are ideas that resonate with hackers, that speak to freedom and a society based on sharing and collaboration. Communities, like WordPress, have grown up around the ethos which has influenced models of software development all over the world. 

The principles are the clauses written in to the General Public License (GPL). The license was written by Richard Stallman for software he released as part of the GNU software project[^fn-1]. Exasperated by proprietary licensing, which he saw as responsible for the decline of the hacker lab at MIT, he wanted to distribute software that he wrote with a license that protected software users’ freedoms. The GPL protects four user freedoms that constitute "free software." “Free" in this context does not apply to price; it refers to freedom, which is the underlying ethos that drives the Free Software Foundation.[^fn-2]

[Free software protects four essential freedoms](http://www.gnu.org/philosophy/free-sw.html):

- 0 The freedom to run the program, for any purpose.
- 1 The freedom to study how the program works, and change it so it does your computing as you wish.
- 2 The freedom to redistribute copies so you can help your neighbour
- 3 The freedom to distribute copies of your modified versions to others. 

These can be summarised as "the users have the freedom to run, copy, distribute, study, change and improve the software." The freedoms are protected for all users of the work. What this means in practice is that anyone can use a piece of free software - they can install it in as many places as they want and give it to whoever they want. They can hack on it, modifying it for their own needs. They can distribute any changes they make. When it comes to a piece of free software, the user has absolute freedom. 

It’s not enough, however, just to write freedoms into a license. Those user freedoms need to be protected. Otherwise, free software can be absorbed into proprietary software but the freedoms aren’t passed on. Developers get the benefits of free software but don’t pass on those benefits. In order to ensure that these freedoms are protected, the GPL employs what Stallman calls "copyleft”. This subverts the normal use of copyright laws to protect the terms under which the work can be distributed and redistributed. It's a method of making a work free and of requiring that all extended and modified versions of the work are free as well. In this way, the copyright holder can ensure that their work does not end up being part of a proprietary model.

Copyleft works in the following way:
1. The copyright holder asserts that they hold the copyright to the work
2. To this is added the terms of distribution. This says that anyone can use, modify, and redistribute the work, _provided they pass the same freedom on to everyone else_.

If a programmer wants to use a copyleft work in their own software, then that new work must provide the same freedoms as the original work. Copyright, which is so often use to inhibit freedom is turned on its head. It is used against itself, or, as [Stallman puts it](http://www.gnu.org/copyleft/) "we use copyright to guarantee their freedom." A copyleft license doesn't abandon copyright (i.e. by simply putting a work in the public domain), it asserts it and uses it. 

The GPL is often described as a viral license. This is because any code that is integrated with GPL code automatically adopts the license. The GPL spreads. For free software proponents this is important. It means that the body of work that constitutes the commons is self-sustainable and self-perpetuating, thus preserving freedom.

To see copyleft in action, simply open up the license that comes bundled with WordPress to this very day. The head contains the following:

> b2 is (c) 2001, 2002 Michel Valdrighi - m@tidakada.com -
  http://tidakada.com

> Wherever third party code has been used, credit has been given in the code's
  comments.

> b2 is released under the GPL

> and

> WordPress - Web publishing software

> Copyright 2003-2010 by the contributors

> WordPress is released under the GPL

It's the perfect example of how a copyleft license works. Michel asserted his original copyright for b2 and then distributed it under the GPL, which said that anyone was free to distribute and modify it, provided they pass those freedoms on. This meant that when it was originally forked, the developers had no choice but to license WordPress under the GPL. Michel's original intention to preserve b2's freedom worked. It also means that anything that includes WordPress source code must also be GPL, so all WordPress users, whatever form they use WordPress in, has the same freedoms. It also meant that when b2 was in danger of become vaporware, Mike and Matt were able to fork it and use the code as a base to continue development. The commons, of which the code was a constituent part, was continued. 


Mike’s passion for free software was an important bedrock for WordPress’ development. b2 was the first free and open source (FOSS) project that Matt had been involved in. While he developed strong opinions about the role of free software, it was in b2 and then in the early days of WordPress that he first learned about the free software ethos, particularly under the influence of Mike. “That’s the thing I really learned from Mike as well,” [says Matt in a 2010 interview](http://wordpress.tv/2010/03/09/mullenweg-little-wordpress-interview/). “b2 was the first open source project I was really involved with. I didn’t even really understand what that meant.”

The GPL compliments the user-first focus of development because the license emphasises the freedoms of users. This is perhaps one of the biggest misunderstandings around the license. When the GPL talks about freedom, it is talking about the freedom of users, not of developers. And often the freedom of users comes at the expense of developers. Developers who want to use a GPL code in their own software are restricted in the choice of license they can use to other copyright licenses. There are also restrictions upon what code they can integrate with their own GPL code. To use a library in WordPress, for example, that library must be GPL-compatible. This difference of emphasis with respect to the emphasis of freedoms has been a fault-line along which debates in the project have happened.

But even if there was a consensus amongst the project’s leaders that the license should be changed, the freedoms of WordPress users would continue to be protected by the fact of the sheer number of contributors. The WordPress codebase is created by thousands of people all over the world. Each person who writes code for WordPress retains their copyright but agrees to license the code under the GPL. This makes it virtually impossible for the creators of WordPress to ever changes the license. To do so, they would need to contact every single person who had ever contributed code to WordPress and ask them to agree to the change. This would include everyone from the most prolific contributors to those who contributed just one patch, from todays lead developers to Matt and Mike, and as far back as Michel. This means that WordPress will always remain free.


[^Fn-1] In his book, _Hackers: Heroes of the Computer Revolution_, Stephen Levy explores the Lab at MIT where Richard Stallman worked, and the decline of which led to him creating GNU and writing the GPL.

[^Fn-2] This choice of the word "free" in this context has dogged the FSF throughout its life. The uninitiated think that "free" refers to cost and the FSF often has to qualify it with the statement "free as in freedom, not as in beer". 
