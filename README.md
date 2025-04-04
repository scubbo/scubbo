Pronouns: He/Him

**This account is mostly unused - the majority of my repositories are in my [self-hosted Gitea instance](https://gitea.scubbo.org)[^contribution], and my prose on my [blog](https://blog.scubbo.org).**

# Professional History

After graduating with a degree in Mathematics and spending a year with a small web development company, I worked for 10 years with Amazon - 4 with Amazon Video in London, and 6 with Amazon Music in San Francisco, ending up as the Tech Lead for the Music Metrics and Data Platform organization. Upon recognizing the inevitable incipient burnout, I took 6 months off of work to recuperate. Since I'd been interested in resiliency and quality development practices while at Amazon (in my spare time I wrote the first version of what eventually became Amazon's Load Test coordination tool, and I led the Incident Analysis group in Music alongside my day job), I've moved into an SRE role at LegalZoom as of January 2023.

# Personal Work

I run a homelab as a testbed for tinkering and learning, mostly with k8s-/GitOps-related tools. Currently I'm trying to figure out how to [Crossplane](http://crossplane.io/)-ify All The Things.

I blog about technology and other things [here](https://blog.scubbo.org). The majority of my own code lives on my [personal Gitea instance](https://gitea.scubbo.org/) rather than on GitHub itself - this account is just for collaborating with others.

# References

A small collection of articles that I found formative and helpful. Several of these links direct to `news.ycombinator.com` or `lobste.rs`, news and articles aggregation sites that often have productive commentary in the comments. You can link through to the actual article by clicking the title.

## All Time Greats

If you're short on time or energy, just read these:

* [Manual Work Is A Bug](https://queue.acm.org/detail.cfm?id=3197520)
* [Many More Much Smaller Steps](https://www.geepawhill.org/series/many-more-much-smaller-steps/)
* [Code Only Does What It Says](https://news.ycombinator.com/item?id=23749676)

## Writing Practices

It is not a mistake that this is the first section, above anything specifically related to Software Engineering. Written language is the greated superpower that humanity has access to (with "collaboration" being a close second - and effective collaboration, not coincidentally, leverages writing), and honing your talent there is the greatest skill you can cultivate.

* [Make Better Documents](https://www.anildash.com/2024/03/10/make-better-documents). Fittingly enough for a document that advocates for good naming/titling and for leading readers through a journey of discovery, just skimming the headings gives solid advice.
* [What I Think About When I Edit](https://evaparish.com/blog/how-i-edit). Echoes of Stephen King's "10% rule" - "_Whenever you finish a piece of writing, check its word count then go back through it and ruthlessly remove at least 10% of the words_"
* [Diátaxis - The Grand Unified Theory Of Documentation](https://diataxis.fr/). A structural framework identifying the differing types of documentation by the goals they aim to achieve. Through the novel cutting-edge technology of "hyperlinks", we can create short focused effective pieces of writing that form something greater than the sum of the parts.
* (See also [Writing Maintainable Code is a Communication Skill](https://news.ycombinator.com/item?id=29396515), linked below)

## The Philosophy and High-Level Practice of Software Engineering

* [Manual Work Is A Bug](https://queue.acm.org/detail.cfm?id=3197520). If I could make every person in tech read one thing, it would...well, it would probably be something about implicit bias and differing perspectives based on different experiences, [the non-neutrality of tech](https://newsletter.danhon.com/archive/s08e12-this-is-your-regular-reminder/), and/or caution around solutionism, followed by somethhing on the importance of earnestly and openly listening to your customers (but not, necessarily, being dictated to them when they want a [faster horse](https://hbr.org/2011/08/henry-ford-never-said-the-fast)). But this would be a very close third!
  * As a helpful early-intermediate step in the process of Automating All The Things, consider [Do-Nothing Scripts](https://news.ycombinator.com/item?id=29083367).
* [Is High Quality Software Worth The Cost?](https://martinfowler.com/articles/is-quality-worth-cost.html). The article "[unasks the question](https://en.wikipedia.org/w/index.php?title=Mu_(negative)&oldid=1066685582#In_popular_culture)", by demonstrating that the "cost" of High Quality Software is in-fact negative (over the long - but not _very_ long - term).
* [The Cult Of Best Practice](https://news.ycombinator.com/item?id=25990929). TL;DR if you just tell me something is a Best Practice, but cannot articulate _why_ (on which dimension it is better, or what weights you're applying to the various criteria of the tradeoff), I will assume that you are simply parroting an idea without understanding it.

## Software Development Life Cycle

Content related to the processes of understanding, editing, committing, reviewing, pushing, and deploying code.

* [Code Only says What It Does](https://news.ycombinator.com/item?id=23749676) (not what it was intended to do) - without historical contexct, it is not possible to distinguish between "_code that was incorrectly implemented_" (and which happens to still work, or to only fail in small and insignificant ways, or whose failure is mitigated by other aspects of the system, or whose failure-triggering-inputs happen only rarely), and "_code that was correctly implemented against a mental model that differs from yours_" (or "_...a mental model that was once accurate, but no longer is_")
  * On a related note, [this article](https://rachelbythebay.com/w/2021/09/05/clever) expands on the quotation "_Debugging is twice as hard as writing the code in the first place. Therefore, if you write the code as cleverly as possible, you are, by definition, not smart enough to debug it_"
* [Writing Maintainable Code Is A Communication Skill](https://news.ycombinator.com/item?id=29396515) - asserts that maintainable code is that which clearly communicates "_How?_", "_What?_", and "_Why?_" to a reader (albeit some of that context might more-properly belong in commit messages than in the code _itself_)
* [What Does Debugging Look Like?](https://jvns.ca/blog/2019/06/23/a-few-debugging-resources) - one key concept not explicitly listed here; "_If your code was working how you believe, expect, and assume that it does/should, then you wouldn't be debugging it. Ergo, at least one of your beliefs, expectations, or assumptions is wrong. Prove everything_"
* [Structural And Behavioural Changes](https://medium.com/@kentbeck_7670/bs-changegs-e574bc396aaa) - pairs well with [Many More Much Smaller Steps](https://www.geepawhill.org/2021/09/29/many-more-much-smaller-steps-first-sketch)
* [How To Write A Good Commit Message](https://chris.beams.io/posts/git-commit) - a drastically under-rated skill. Like linters/auto-formatters, good commit messages are not going to magically make your bad code good - but both have an absurdly-high rate-of-return on the effort that they take. Use of imperative vs. indicative mood is pure bike-shedding, but "_Use the body to explain what and why, not how_" is Unarguable Physical Fact and I will fite you IRL.
* A dyad from Slack on Codde Reviews;
  * [Submitting](https://slack.engineering/on-empathy-pull-requests-979e4257d158)
  * [Reviewing](https://slack.engineering/how-about-code-reviews-2695fb10d034)
* [How To Make Your Code Reviewer Fall In Love With You](https://mtlynch.io/code-review-love) combines a lot of concepts from the preceding few links.
* (Tweet thread) "[Including Delivery/Deployment in the Definition of Done](https://threadreaderapp.com/thread/147369536494364290.html)" - spotlights the unhelpful practice of "_busyness accounting_", of measuring "_how hard people are working_" rather than "_how much is delivered_". This is unhelpful because it continues to hide inefficiencies and friction in the system. Rather, we should bravely admit our failures-to-deliver (hand-in-hand with leadership cultivating a psychologically-safe environment to do so), and use them as prompts to improve the aspects of thhe system that led to that failure.
  * Note too that "_You Get What You ~~Measure~~ Incentivize_"

## Resiliency, Observability, and Operation of Software Systems

* The [SRE Book](https://landing.google.com/sre/sre-book/toc/index.html), especially the chapter on [SLIs, SLOs, and SLAs](https://sre.google/sre-book/service-level-objectives/). Say it with me, now - "_if it doesn't include a response, it's not an SLA, it's an SLO_".
  * If you're more of an audiovisual learner, [this video](https://www.youtube.com/watch?v=tEylFyxbDLE) is a great intro to the concepts
* [Notes On The Perfidy Of Dashboards](https://charity.wtf/2021/08/09/notes-on-the-perfidy-of-dashboards) - highlights that, without the ability to correlate between _events_, dashboards only allow aggregate high-level pattern-matching, not actual debugging and investigation.
  * Be warned that Charity Majors has a tendency to say controversial things which are technically-true-but-misleading - in that the way that _she_ interprets it is correct; but the way that a reasonable listener, unfamiliar with the shibboleth, would interpret it is incorrect. For example, "_You should deploy on Fridays_" - what she _really_ means is "_you should improve your resiliency to the point where deploying on Fridays is not a risky action_". This is an undeniably effective attention-grabbing strategy, and clearly a good way to become a Thought Leader™️; but if you, like me, find it more important to educate your audience than to generate clicks, you may find it grating. Hold your nose and power through - she does know what she's talking about, even if she presents it perversely.
* [Google's DiRT](https://queue.acm.org/detail.cfm?id=2371516) - "_the unexpected happens. We cannot do much to prevent it, but there is a lot we can do to be prepared for it[...] by intentionally causing failures in [critical systems and business processes], and to fix them before such failures happen in an uncontrolled manner_"
* [You Reap What You Code](https://ferd.ca/you-reap-what-you-code.html) - a wide-ranging article on Operations, Observability, Complexity, and Human Interfaces.
* [Howie, the Post-Incident Guide](https://www.jeli.io/howie-the-post-incident-guide) - Lots of crossover with the practice of writing Incident Reports/RCAs.

## Career Practices

* [Keep A Brag Doc](https://jvns.ca/blog/brag-documents). Actually, almost everything that Julia Evans writes is excellent - this merely happens to be a standout piece of Career Advice.
* [Meeting Everyone On A New Team](https://news.ycombinator.com/item?id=24529176)
* [The Software Engineer's Guide to Asserting Dominance in the Workplace](https://medium.com/feature-creep/the-software-engineer-s-guide-to-asserting-office-dominance-ddea7b598df7). Do not actually do this.
* [Being Glue](https://noidea.dog/glue). A description of the many types of technical work that are often (unfairly and inaccurately) perceived as having "low impact", and what to do when you are someone who is doing that work. Partly this falls into "High-Level Practice", since it is describing a phenomenon that occurs _during_ the process of "owning and developing code" - an important one to be conscious of. However, I put it in "Career Practices" because being a "Glue" Engineer can be a career pitfall - it is highly important and rewarding work that is naturally-invisible, and so engineers who find themselves in this role find it hard to get the recognition required to advance their careers.
* [How to Mentor Software Engineers](https://news.ycombinator.com/item?id=29795034)
* [Onboarding Engineers](https://leadership.garden/onboarding-engineers). Note also the [Blue Tape List](https://randsinrepose.com/archives/the-blue-tape-list), a recognition that fresh eyes are your most valuable assets for catching issues in your tools and processes that tenured employees might subconciously gloss over - this goes doubly for the onboarding process, which is _only_ ever experienced by newbies (and so, needs to be constantly reworked to ensure it remains up-to-date and free from dependencies on Implicit Knowledge)

## Productivity Practices

* [Efficiency Is The Enemy](https://fs.blog/2021/05/slack) - an exploration ofthe fact that a fully-packed calendar/to-do list makes you _less_ flexible and agile. There needs to be some "slack in the system" to allow it(/you/your team) to adjust to high-value unforeseen opportunities.
  * See also [The Most Important Thing To Understand About Queues](https://blog.danslimmon.com/2016/08/26/the-most-important-thing-to-understand-about-queues) for a mathematical perspective. If you find yourself nitpicking the statement about induction, see [this HN comment](https://news.ycombinator.com/item?id=30601286)
* [The Only Out-Of-Office Auto-reply You Will Ever Need](https://www.theladders.com/career-advice/the-only-out-of-office-autoreply-you-need)
* [It's Now Your Fault They Don't Know About It](https://rachelbythebay.com/w/2022/03/02/wrong) - outlines a particularly toxic interaction pattern with coworkers. It's implied in the article, but, explicitly - when you identify thhis pattern, by all means try to call it out (tactfully) as early as possible, but don't hold out much hope that they will change their behaviour. Rather, find the most benficial way to work _around_ their intransigency, while maintaining your own peace of mind - from the [Hacker News comments](https://news.ycombinator.com/item?id=30542528) "_What I find scary is that if you work in a sufficiently toxic environment/cultur for long enough, that very behaviour that you try to fight against and change begins to seep into your everyday actions. I've seen myself go from 'positive and helpful' to 'apathetic and helpful' to 'not caring at all' to 'chippy, negative, and unhelpful' before_"

# Contact and Socials

[Mastodon](https://fosstodon.org/@scubbo) is my main Social Media app nowadays. I'm reachable via email at `me@scubbo.org`.

[^contribution]: Though if you're looking at the contribution-graph, note that an upgrade in early 2025 nuked the history of the pretty ~~green~~ blue squares that we crave so much.
