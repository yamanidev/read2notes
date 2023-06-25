## To look up
- Turing machine?
- What does it mean when we say that a programming language is Turing-equivalent?

*If you want to make money at some point, remember this, because this is one
of the reasons startups win. Big companies want to decrease the standard
deviation of design outcomes because they want to avoid disasters. But when
you damp oscillations, you lose the high points as well as the low. This is not a
problem for big companies, because they don't win by making great products.
Big companies win by sucking less than other big companies.*

*So if you can figure out a way to get in a design war with a company big enough
that its software is designed by product managers, they'll never be able to keep
up with you. These opportunities are not easy to find, though. It's hard to
engage a big company in a design war, just as it's hard to engage an opponent
inside a castle in hand- to- hand combat. It would be pretty easy to write a better
word processor than Microsoft Word, for example, but Microsoft, within the
castle of their operating system monopoly, probably wouldn't even notice if
you did.*

*The place to fight design wars is in new markets, where no one has yet
managed to establish any fortifications. That's where you can win big by taking
the bold approach to design, and having the same people both design and
implement the product. Microsoft themselves did this at the start. So did Apple.
And Hewlett- Packard. I suspect almost every successful startup has.*

---

*The fact that hackers learn to hack by doing it is another sign of how different
hacking is from the sciences. Scientists don't learn science by doing it, but by
doing labs and problem sets. Scientists start out doing work that's perfect, in
the sense that they're just trying to reproduce work someone else has already
done for them. Eventually, they get to the point where they can do original
work. Whereas hackers, from the start, are doing original work; it's just very
bad. So hackers start original, and get good, and scientists start good, and get
original.*

*The other way makers learn is from examples. To a painter, a museum is a
reference library of techniques. For hundreds of years it has been part of the
traditional education of painters to copy the works of the great masters,
because copying forces you to look closely at the way a painting is made.*

*Writers do this too. Benjamin Franklin learned to write by summarizing the
points in the essays of Addison and Steele and then trying to reproduce them.
Raymond Chandler did the same thing with detective stories.*

---

*It's unrealistic to expect that the specifications for a program will
be perfect. You're better off if you admit this up front, and write programs in a
way that allows specifications to change on the fly.*

*A good programming language should, like oil paint, make it easy to change your mind. Dynamic typing is a win here because you don't have to commit to specific data representations up front. But the key to flexibility, I think, is to make the language very abstract. The easiest program to change is one that's short.*

---

*The word "defeatist," for example, has no particular political connotations now. But in Germany in 1917 it was a weapon, used by Ludendorff in a purge of those who favored a negotiated peace. At the start of World War II it was used extensively by Churchill and his supporters to silence their opponents. In 1940, any argument against Churchill's aggressive policy was "defeatist." Was it right or wrong? Ideally, no one got far enough to ask that.*

Fashion in ideas seem to propoagate when a nervous group doesn't like some things to be said.

*When Milton was going to visit Italy in the 1630s, Sir Henry Wootton, who had been ambassador to Venice, told him that his motto should be "i pensieri stretti & il viso sciolto." Closed thoughts and an open face. Smile at everyone, and don't tell them what you're thinking. This was wise advice. Milton was an argumentative fellow, and the Inquisition was a bit restive at that time. But the difference between Milton's situation and ours is only a matter of degree. Every era has its heresies, and if you don't get imprisoned for them, you will at least get in enough trouble that it becomes a complete distraction.*

*A Dutch friend says I should use Holland as an example of a tolerant society. It's true they have a long tradition of comparative open- mindedness. For centuries the low countries were the place to go to say things you couldn't say anywhere else, and this helped make the region a center of scholarship and industry (which have been closely tied for longer than most people realize). Descartes, though claimed by the French, did much of his thinking in Holland.*

---

*Viaweb was written by just three people. 7 I was always under pressure to hire more, because we wanted to get bought, and we knew that buyers would have a hard time paying a high price for a company with only three programmers. (Solution: we hired more, but created new projects for them.)*

*When you can write software with fewer programmers, it saves you more than money. As Fred Brooks pointed out in The Mythical Man- Month , adding people to a project tends to slow it down. The number of possible connections between developers grows exponentially with the size of the group. 8 The larger the group, the more time they'll spend in meetings negotiating how their software will work together, and the more bugs they'll get from unforeseen interactions. Fortunately, this process also works in reverse: as groups get smaller, software development gets exponentially more efficient. I can't remember the programmers at Viaweb ever having an actual meeting. We never had more to say at any one time than we could say as we were walking to lunch.*

*If there is a downside here, it is that all the programmers have to be to some degree system administrators as well. When you're hosting software, someone has to be watching the servers, and in practice the only people who can do this properly are the ones who wrote the software. At Viaweb our system had so many components and changed so frequently that there was no definite border between software and infrastructure. Arbitrarily declaring such a border would have constrained our design choices. And so although we were constantly hoping that one day ("in a couple months") everything would be stable enough
that we could hire someone whose job was just to worry about the servers, it
never happened. I don't think it could be any other way, as long as you're still actively developing the product. Web- based software is never going to be something you write,
check in, and go home. It's a live thing, running on your servers right now. A bad bug might not just crash one user's process; it could crash them all. If a bug in your code corrupts some data on disk, you have to fix it. And so on. We found that you don't have to watch the servers every minute (after the first year or so), but you definitely want to keep an eye on things you've changed recently. You don't release code late at night and then go home.*

---

*There are only two things you have to know about business: build something users love, and make more than you spend. If you get these two right, you'll be ahead of most startups. You can figure out the rest as you go.*

*As for building something users love, here are some general tips. Start by making something clean and simple that you would want to use yourself. Get a version 1.0 out fast, then continue to improve the software, listening closely to users as you do. The customer is always right, but different customers are right about different things; the least sophisticated users show you what you need to simplify and clarify, and the most sophisticated tell you what features you need to add.*

---

*Technical advances tend to come from unorthodox approaches, and small companies are less constrained by convention.*

*Big companies can develop technology. They just can't do it quickly. Their size makes them slow and prevents them from rewarding employees for the extraordinary effort required. So in practice big companies only get to develop technology in fields where large capital requirements prevent startups from competing with them, like microprocessors, power plants, or passenger aircraft. And even in those fields they depend heavily on startups for
components and ideas.*

*Use difficulty as a guide not just in selecting the overall aim of your company, but also at decision points along the way. At Via web one of our rules of thumb was run upstairs . Suppose you are a little, nimble guy being chased by a big, fat, bully. You open a door and find yourself in a staircase. Do you go up or down? I say up. The bully can probably run downstairs as fast as you can. Going upstairs his bulk will be more of a disadvantage. Running upstairs is hard for you but even harder for him.
What this meant in practice was that we deliberately sought hard problems. If there were two features we could add to our software, both equally valuable in proportion to their difficulty, we'd always take the harder one. Not just because it was more valuable, but because it was harder . We delighted in forcing bigger, slower competitors to follow us over difficult ground. Like guerillas, startups prefer the difficult terrain of the mountains, where the troops of the central government can't follow. I can remember times when we were just exhausted after wrestling all day with some horrible technical problem. And I'd be delighted, because something that was hard for us would be impossible for our competitors.
This is not just a good way to run a startup. It's what a startup is. Venture capitalists know about this and have a phrase for it: barriers to entry . If you go to a VC with a new idea and ask him to invest in it, one of the first things he'll ask is, how hard would this be for someone else to develop? That is, how much difficult ground have you put between yourself and potential pursuers? 7 And you had better have a convincing explanation of why your technology would be hard to duplicate. Otherwise as soon as some big company becomes aware of it, they'll make their own, and with their brand name, capital, and distribution clout, they'll take away your market overnight. You'd be like guerillas caught in the open field by regular army forces.*

*One way to put up barriers to entry is through patents. But patents may not provide much protection. Competitors commonly find ways to work around a patent. And if they can't, they may simply violate it and invite you to sue them. A big company is not afraid to be sued; it's an everyday thing for them. They'll make sure that suing them is expensive and takes a long time. Ever heard of Philo Farnsworth? He invented television. The reason you've never heard of him is that his company was not the one to make money from it. The company that did was RCA, and Farnsworth's reward for his efforts was adecade of patent litigation. Here, as so often, the best defense is a good offense. If you can develop technology that's simply too hard for competitors to duplicate, you don't need to rely on other defenses. Start by picking a hard problem, and then at every decision point, take the harder choice*

---

*Because of the circumstances in which they encounter it, children tend to misunderstand wealth. They confuse it with money. They think that there is a fixed amount of it. And they think of it as something that's distributed by authorities (and so should be distributed equally), rather than something that has to be created (and might be created unequally).*

*In fact, wealth is not money. Money is just a convenient way of trading one form of wealth for another. Wealth is the underlying stuff—the goods and services we buy. When you travel to a rich or poor country, you don't have to look at people's bank accounts to tell which kind you're in. You can see wealth —in buildings and streets, in the clothes and the health of the people.*

*Where does wealth come from? People make it. This was easier to grasp when most people lived on farms, and made many of the things they wanted with their own hands. Then you could see in the house, the herds, and the granary the wealth that each family created. It was obvious then too that the wealth of the world was not a fixed quantity that had to be shared out, like slices of a pie. If you wanted more wealth, you could make it.*

*This is just as true today, though few of us create wealth directly for ourselves (except for a few vestigial domestic tasks). Mostly we create wealth for other people in exchange for money, which we then trade for the forms of wealth we want.*

---

*GOOD DESIGN IS SIMPLE. You hear this from math to painting. In math it means that a shorter proof tends to be a better one. Where axioms are concerned, especially, less is more. It means much the same thing in programming. For architects and designers, it means that beauty should depend on a few carefully chosen structural elements rather than a profusion of superficial ornament. (Ornament is not in itself bad, only when it's camouflage
on insipid form.) Similarly, in painting, a still life of a few carefully observed and solidly modelled objects will tend to be more interesting than a stretch of flashy but mindlessly repetitive painting of, say, a lace collar. In writing it means: say what you mean and say it briefly.*

*GOOD DESIGN IS TIMELESS. In math, every proof is timeless unless it contains a mistake. So what does Hardy mean when he says there is no permanent place for ugly mathematics? He means the same thing Kelly Johnson did: if something is ugly, it can't be the best solution. There must be a better one, and eventually someone else will discover it.
Aiming at timelessness is a way to make yourself find the best answer: if you can imagine someone surpassing you, you should do it yourself. Some of the greatest masters did this so well that they left little room for those who came after. Every engraver since Dürer suffers by comparison.
Aiming at timelessness is also a way to evade the grip of fashion. Fashions almost by definition change with time, so if you can make something that will still look good far into the future, then its appeal must derive more from merit than fashion.*

*In math and engineering, recursion, especially, is a big win. Inductive proofs are wonderfully short. In software, a problem that can be solved by recursion is nearly always best solved that way. The Eiffel Tower looks striking partly because it is a recursive solution, a tower on a tower.*

*At an art school where I once studied, the students wanted most of all to develop a personal style. But if you just try to make good things, you'll inevitably do it in a distinctive way, just as each person walks in a distinctive way. Michelangelo was not trying to paint like Michelangelo. He was just trying to paint well; he couldn't help painting like Michelangelo.*

*Today's experimental error is tomorrow's new theory. If you want to discover great new things, then instead of turning a blind eye to the places where conventional wisdom and truth don't quite meet, you should pay particular attention to them.*

---

*Languages evolve slowly because they're not really technologies. Languages are notation. A program is a formal description of the problem you want a computer to solve for you. So the rate of evolution in programming languages is more like the rate of evolution in mathematical notation than, say, transportation or communications. Mathematical notation does evolve, but not with the giant leaps you see in technology.*

*Most data structures exist because of speed. For example, many languages today have both strings and lists. Semantically, strings are more or less a subset of lists in which the elements are characters. So why do you need a separate data type? You don't, really. Strings only exist for efficiency. But it's lame to clutter up the semantics of a language with hacks to make programs run faster. Having strings in a language seems to be a case of premature optimization.*

*The word "essay" comes from the French verb "essayer," which means "to try." An essay, in the original sense, is something you write to try to figure something out. This happens in software too. I think some of the best programs were essays, in the sense that the authors didn't know when they started exactly what they were trying to write.*

*Wasting programmer time is the true inefficiency, not wasting machine time. This will become ever more clear as computers get faster.*

*How far will this flattening of data structures go? I can think of possibilities that shock even me, with my conscientiously broadened mind. Will we get rid of arrays, for example? After all, they're just a subset of hash tables where the keys are vectors of integers. Will we replace hash tables themselves with lists?*

---

John McCarthy developed Lisp in 1958, yet modern programming languaes are only now catching up with his ideas. How is that possible? Isn't technology by definition progressive? How is something that old still relevant? Paul answers:
*It's because Lisp was not really designed to be a programming language, at least not in the sense we mean today. What we mean by a programming language is something we use to tell a computer what to do. McCarthy did eventually intend to develop a programming language in this sense, but the Lisp we actually ended up with was based on something separate that he did as a theoretical exercise—an effort to define a more convenient alternative to the Turing machine. As McCarthy said later.
Another way to show that Lisp was neater than Turing machines was to write a universal Lisp function and show that it is briefer and more comprehensible than the description of a universal Turing machine. This was the Lisp function eval..., which computes the value of a Lisp expression....Writing eval required inventing a notation representing Lisp functions as Lisp data, and such a notation was devised for the purposes of the paper with no thought that it would be used to express Lisp programs in practice.*

*But in late 1958, Steve Russell, 3 one of McCarthy's grad students, looked at this definition of eval and realized that if he translated it into machine language, the result would be a Lisp interpreter. This was a big surprise at the time. Here is what McCarthy said about it later:*

*Steve Russell said, look, why don't I program this eval..., and I said to him, ho,
ho, you're confusing theory with practice, this eval is intended for reading, not for computing. But he went ahead and did it. That is, he compiled the eval in
my paper into IBM 704 machine code, fixing bugs, and then advertised this as a
Lisp interpreter, which it certainly was. So at that point Lisp had essentially the
form that it has today....*

*Suddenly, in a matter of weeks, McCarthy found his theoretical exercise transformed into an actual programming language—and a more powerful one than he had intended.*

*So the short explanation of why this 1950s language is not obsolete is that it was not technology but math, and math doesn't get stale. The right thing to compare Lisp to is not 1950s hardware but the Quick sort algorithm, which was discovered in 1960 and is still the fastest general- purpose sort.*

*When it was first developed, Lisp embodied nine new ideas. Some of these we now take for granted, others are only seen in more advanced languages, and two are still unique to Lisp. The nine ideas are, in order of their adoption by the mainstrea.*
1. *Conditionals. A conditional is an if-then- else construct. We take these for granted now, but Fortran I didn't have them. It had only a conditional go to closely based on the underlying machine instruction.*
2. *A function type. In Lisp, functions are a data type just like integers or strings. They have a literal representation, can be stored in variables, can be passed as arguments, and so on.*
3. *Recursion. Lisp was the first high- level language to support recursive functions.*
4. *Dynamic typing. In Lisp, all variables are effectively pointers. Values are what have types, not variables, and assigning values to variables means copying pointers, not what they point to.*
5. *Garbage- collection.*
6. *Programs composed of expressions. Lisp programs are trees of expressions, each of which returns a value. This is in contrast to Fortran and most succeeding languages, which distinguish between expressions and statements.*
	*This distinction was natural in Fortran I because you could not nest statements. So while you needed expressions for math to work, there was no point in making anything else return a value, because there could not be anything waiting for it.*

	*This limitation went away with the arrival of block- structured languages, but by then it was too late. The distinction between expressions and statements was entrenched. It spread from Fortran into Algol and then to both their descendants.*
7. *A symbol type. Symbols are effectively pointers to strings stored in a hash table. So you can test equality by comparing a pointer, instead of comparing each character.*
8. *A notation for code using trees of symbols and constants.*
9. *The whole language there all the time. There is no real distinction between read-time, compile-time, and runtime. You can compile or run code while reading, read or run code while compiling, and read or compile code at runtime.*

	*Running code at read- time lets users reprogram Lisp's syntax; running code at compile- time is the basis of macros; compiling at runtime is the basis of Lisp's use as an extension language in programs like Emacs; and reading at runtime enables programs to communicate using s-expressions, an idea recently reinvented as XML.*

*As for number 8, this may be the most interesting of the lot. Ideas 8and 9 only became part of Lisp by accident, because Steve Russell implemented something McCarthy had never intended to be implemented. And yet these ideas turn out to be responsible for both Lisp's strange appearance and its most distinctive features. Lisp looks strange not so much because it has a strange syntax as because it has no syntax; you express programs directly in the parse trees that get built behind the scenes when other languages are parsed, and these trees are made of lists, which are Lisp data structures.*

*Expressing the language in its own data structures turns out to be a very powerful feature. Ideas 8 and 9 together mean that you can write programs that write programs. That may sound like a bizarre idea, but it's an everyday thing in Lisp. The most common way to do it is with something called a macro.*

*The term "macro" does not mean in Lisp what it means in other languages. A Lisp macro can be anything from an abbreviation to a compiler for a new language. If you really want to understand Lisp, or just expand your programming horizons, I would learn more about macros.*

---

*Let's start by acknowledging one external factor that does affect the popularity of a programming language. To become popular, a programming language has to be the scripting language of a popular system. Fortran and Cobol were the scripting languages of early IBM mainframes. C was the scripting language of Unix, and so, later, were Perl and Python. Tcl is the scripting language of Tk, Visual Basic of Windows, (a form of) Lisp of Emacs, PHP of web servers, and Java and Javascript of web browsers.*

*There is one thing more important than succinctness to a hacker: being able to do what you want. In the history of programming languages, a surprising amount of effort has gone into preventing programmers from doing things considered to be improper. This is a dangerously presumptuous plan. How can the language designer know what the programmer will need to do? I think language designers would do better to consider their target user to be a genius who will need to do things they never anticipated, rather than a bumbler who needs to be protected from himself. The bumbler will shoot himself in the foot anyway. You may save him from referring to variables in another module, but you can't save him from writing a badly designed program to solve the wrong problem, and taking forever to do it.*

*Good programmers often want to do dangerous and unsavory things. By unsavory I mean things that go behind whatever semantic facade the language is trying to present: getting hold of the internal representation of some high-level abstraction, for example. Hackers like to hack, and hacking means getting inside things and second- guessing the original designer.*

*A really good language should be both clean and dirty: cleanly designed, with a small core of well understood and highly orthogonal operators, but dirty in the sense that it lets hackers have their way with it. C is like this. So were the early Lisps. A real hacker's language will always have a slightly raffish character.*

*A good programming language should have features that make the kind of people who use the phrase "software engineering" shake their heads disapprovingly. At the other end of the continuum are languages like Pascal, models of propriety that are good for teaching and not much else.*

*To be attractive to hackers, a language must be good for writing the kinds of programs they want to write. And that means, perhaps surprisingly, that it has to be good for writing throwaway programs.*

*A throwaway program is a program you write quickly for some limited task: a program to automate some system administration task, or generate test data for a simulation, or convert data from one format to another. The surprising thing about throwaway programs is that, like the "temporary" buildings built at so many American universities during World War II, they often don't get thrown away. Many evolve into real programs, with real features and real users.*

*Perl is a striking example of this idea. It was not only designed for writing throwaway programs, but was pretty much a throwaway program itself. Perl began life as a collection of utilities for generating reports, and only evolved into a programming language as the throwaway programs people wrote in it grew larger. It was not until Perl 5 (if then) that the language was suitable for writing serious programs, and yet it was already massively popular.*

---

*To write good software you must simultaneously keep two opposing ideas in your head. You need the young hacker's naive faith in his abilities, and at the same time the veteran's skepticism. You have to be able to think how hard can it be ? with one half of your brain while thinking it will never work with the other.*

*People who do good work often think that whatever they're working on is no good. Others see what they've done and think it's wonderful, but the creator sees nothing but flaws. This pattern is no coincidence: worry made the work good.*

*To get good design you have to get close, and stay close, to your users. You have to calibrate your ideas on actual users constantly. One of the reasons Jane Austen's novels are so good is that she read them out loud to her family. That's why she never sinks into self-indulgently arty descriptions of landscapes, or pretentious philosophizing. (The philosophy's there, but it's woven into the story instead of being pasted onto it like a label.) If you open an average "literary" novel and imagine reading it out loud to your friends as something you'd written, you'll feel all too keenly what an imposition that kind of thing is
upon the reader.*

*What people outside the software world may not realize is that Worse is Better is found throughout the arts. In drawing, for example, the idea was discovered during the Renaissance. Now almost every drawing teacher will tell you that the right way to get an accurate drawing is not to work your way slowly around the contour of an object, because errors will accumulate and you'll find at the end that the lines don't meet. Instead you should draw a few quick lines in roughly the right place, and then gradually refine this initial sketch.*

