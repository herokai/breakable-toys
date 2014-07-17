ou can’t do anything really well unless you love it, and if you love to hack you’ll inevitably be working on projects of your own.

—Paul Graham, Hackers & Painters
We can all benefit by doing occasional “toy” programs, when artificial restrictions are set up, so that we are forced to push our abilities to the limit.

—Donald Knuth, The Art of Computer Programming
Context

Experience is built upon failure as much as (if not more than) success.

Problem

You work in an environment that does not allow for failure. Yet failure is often the best way to learn anything. Only by attempting to do bold things, failing, learning from that failure, and trying again do we grow into the kind of people who can succeed when faced with difficult problems.

Solution

Budget for failure by designing and building toy systems that are similar in toolset, but not in scope to the systems you build at work.

If experience is built upon failure as much as success, then you need a more or less private space where you can seek out failure. In juggling, the three-ball juggler who never attempts five balls never makes the step up. Yet the one who gets backaches from having to pick up dropped balls for hours on end will eventually get it right. The same lesson applies to software. Just as the three-ball juggler would not attempt to juggle five balls during a performance, software developers need a safe place to make mistakes.

As a teenager working in Nova Scotia, Steve Baker was looked upon as a leader and an expert within his small development organization. Steve described how these expectations impacted him: “Everyone expected me to already know the right way to do it. Since I couldn’t use those projects as a learning experience, I had to stop learning.” This was similar to Ade’s consulting experiences, where he couldn’t afford to be wrong and he couldn’t just walk away from people who were depending on him to always be right. Ade knew that in order to learn, he needed the freedom to drop the ball. Like countless software developers before him, Ade used Breakable Toys to help him learn.

When implementing the Breakable Toys pattern, make your systems relevant and useful to your life as an apprentice. For example, build your own wiki, calendar, or address book. Your solutions might be massively overengineered for the problem they’re solving, and probably could easily be replaced by something off the shelf. However, these projects are where you are allowed to fail. They’re the projects where you can try ideas and techniques that might lead to catastrophic failure. But the only one who can be hurt by their failure is you.

A classic example of the use of this pattern is the multitude of people who have built their own wikis. A personal wiki is a great tool for the apprentice because you can use it to Record What You Learn. Wikis make good Breakable Toys because they can be incredibly simple[29] and you can Use the Source to find countless examples to look. Over time, maintaining a wiki can teach you about HTTP, REST, parsing, web design, caching, full-text search, databases, and concurrency. If you stick with it long enough, it will also teach you about data migration when you eventually add a feature that requires a different storage format and you don’t want to throw away all your data.

Other examples of Breakable Toys include games like Tetris and Tic-Tac-Toe (one of our ex-colleagues is in the habit of writing a game in every new language he learns), blogging software, and IRC clients. The essential point is that building the toy involves learning new things, giving you an opportunity to gain a deeper understanding of your tools in an environment that is both safe (since you are the only or most important user) and where there is still room for you to better serve your own needs as a user than even the slickest of commercial alternatives.

These are your Breakable Toys. As you carry them with you from job to job, some of them will become living embodiments of your craftsmanship. Despite that, remember that they’re toys and as such should be fun. If they’re not fun, then after the initial burst of enthusiasm they will gather dust while you focus your energies on the things you actually enjoy building.

Often these toys are simple reimplementations of industry-standard tools that give you a deeper understanding of the forces that led to the current design of that tool. There’s even the possibility that one of your toys will take on a life of its own and acquire other users. In those cases you may find yourself having to seek out a new breakable toy.

Linus builds a toy OS[30]

 From: torvalds@klaava.Helsinki.FI (Linus Benedict Torvalds)
 Newsgroups: comp.os.minix
 Subject: What would you like to see most in minix?
 Summary: small poll for my new operating system
 Message-ID: <1991Aug25.205708.9541@klaava.Helsinki.FI>
 Date: 25 Aug 91 20:57:08 GMT
 Organization: University of Helsinki

 Hello everybody out there using minix -

 I’m doing a (free) operating system (just a hobby, won’t be big and
 professional like gnu) for 386(486) AT clones.  This has been brewing
 since april, and is starting to get ready.  I’d like any feedback on
 things people like/dislike in minix, as my OS resembles it somewhat
 (same physical layout of the file-system (due to practical reasons)
 among other things).

 I’ve currently ported bash(1.08) and gcc(1.40), and things seem to work.
 This implies that I’ll get something practical within a few months, and
 I’d like to know what features most people would want.  Any suggestions
 are welcome, but I won’t promise I’ll implement them :-)

               Linus (torvalds@kruuna.helsinki.fi)

 PS.  Yes - it’s free of any minix code, and it has a multi-threaded fs.
 It is NOT protable (uses 386 task switching etc), and it probably never
 will support anything other than AT-harddisks, as that’s all I have :-(.
The Breakable Toys pattern is similar to Be the Worst, but that pattern is about finding a team where you can grow. Breakable Toys is more about deliberately creating opportunities to learn by stepping beyond your boundaries and single-handedly building complete software projects. It is also related to The White Belt and Confront Your Ignorance, but is less focused on letting go of your previous knowledge.

Action

Use your favorite tools to build the world’s simplest wiki while still maintaining the highest standards of quality. The initial version doesn’t need to have anything more than a simple user interface that lets you view and edit plain-text files. Over time, you can add more features and find interesting ways to distinguish your wiki from the thousands that already exist. Do not be constrained by existing implementations; instead, let your professional interests guide you. For instance, you might have an interest in search engines; in this case your wiki could experiment with ranking algorithms or tagging. It really doesn’t matter what you decide to do, as long as you experiment and learn.
