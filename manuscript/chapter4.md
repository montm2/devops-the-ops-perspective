# IT Ops Skills in a DevOps Environment
So let's say you've decided, at least in theory, to help take your organization onto a DevOps standing. You've read about some of the high-level capabilities that you, as an Operations person, need to provide to the organization.

How do you do it?

In a word, "glue."

I'll say it again: DevOps is a _philosophy_. Accounting remains a good example. The accounting industry agrees, more or less, on what constitutes good accounting, and that's where GAAP comes from. Similarly, the DevOps industry is slowly coalescing a feeling of what "good" DevOps "feels like."

But every organization does it their own way. Look at how any one organization handles their accounting, in detail, and you'll see plenty of differences between other organizations. Perhaps auditors work a little differently, or perhaps a different job role is responsible for different accounting duties. Some companies need fairly simplistic accounting, whereas others need incredibly complex accounting that demands hundreds of people working around the clock. Although they're all operating on the same _principles_, their implementations vary widely.

So it is with DevOps. 

In a small organization, accounting may be simple enough that off-the-shelf tools, like Quickbooks, are sufficient. In that size of an organization, DevOps might not even be a thing, because a company of that size might simply not be doing any "dev" to begin with. In a massive, multi-departmental enterprise, accounting might involve "off-the-shelf" tools that requires months and months of customization and tweaking. Similarly, DevOps in that same organization might involve customized tooling that uses generic building blocks... and a lot of custom glue.

Providing the operational infrastructure for a DevOps organization can be hacking at its finest. Yes, you'll find plenty of off-the-shelf technologies and products... but many of them will only get you to a certain point in your organization's goals. After that, it'll be a bit of customizing, a bit of "gluing" different tools together, and a bit of hacking around the rough edges. That will probably _always_ be the case, just as it's still the case that large new deployments of accounting tools _always_ take months and months. Nothing off-the-shelf can possibly fit every organization's needs, so you'll simply have to be prepared to do some customizing. Some hacking. Some gluing.

With that in mind, what are the right skills to have?

* The ability to learn quickly. You'll have to master new products and technologies on the fly.
* Creativity. You'll need to think of clever solutions to work around stumbling blocks. Don't expect everything to "just work" - it won't. 
* Deep understanding of your platform(s). Whether you're working on Microsoft Windows, a Linux distribution, or some other platform, you need to know _deeply_ how it works, because you're going to be interacting with it in the sub-basement level.
* Scripting. You're going to need to be _fluent_ in the leading systems programming ("scripting") language(s) used on your platform, because that's the "glue" you'll use to stick different technologies together into a cohesive, custom solution.

This DevOps stuff is not for beginners, nor is it for the faint of heart. This is, in my own personal belief, why companies create job titles like "DevOps Engineer." Most of the DevOps community quite justifiably freaks out about job titles like that, because they're often a demonstration that _someone in the organization doesn't get it_. DevOps isn't a job role. However, in an organization practicing DevOps, there certainly are some skills that will come in handy, especially on the Operations side. Someone possessing those skills might justifiably be called a "DevOps Engineer," which is perhaps less cumbersome than "IT person who knows enough to make all these bits stick together so we can get the DevOps-enabling capabilities we need." That'd be a big business card. "DevOps Engineer" is probably also a title less demeaning to one's co-workers than "Cleverest IT Person We've Got," which is also usually the case.

IT Ops folks working to provide DevOps-compatible capabilities are often the more experienced, cleverer folks on the team. They often have the broadest experience and knowledge, and they're often the ones most eager to tackle a challenge. 

By the way, notice how I phrased that. "...working to provide DevOps-compatible capabilities..." was a very deliberate phrase. A DevOps-practicing organization does need specific capabilities, and the Operations side provides some of them, in close collaboration with the Dev side. That doesn't mean you have a "DevOps Department," because that misses the point. "DevOps Engineer" as a job title is only legit if it means "Engineer Who Helps Provide Our DevOps-Related Capabilities." DevOps isn't something you _do_; it's something you _believe_, which in turn drives you to do things. If you believe in DevOps, your organization needs to behave in a certain way, and it needs certain tools to support those behaviors. 

There are new Development skills that need to be brought into a DevOps environment, too. Developers have to focus more on building code that _can_ be deployed, monitored, and managed in a DevOps-centric way. For example, in most Windows-centric environments, developers would often use the tools bundled into Visual Studio to create Windows Installer packages for applications. Those packages weren't always easy to deploy in an automated fashion, may have required (or thought they required) Administrator privileges, and other elements that simply made deploying the code difficult and even dangerous. To "do" DevOps, that has to change. Operations needs to give Development the ability to seamlessly slide code into production - but Development needs to write code that supports that model. The burden is on both groups, as a combined team, not just on Operations to make things simpler.

## Plan for Failure

> "Wait a damn minute," I can hear you saying, "sliding new code into production is what causes all the problems!" 

Agreed. _Any kind of change_ has the potential to create problems. The point of DevOps - and most particularly the Operations role in DevOps - is to _create an environment where you can fail quickly, and fix just as quickly_ (thanks to Chris Hunt for that). If DevOps means constantly pushing out small bits of code, then you have to be prepared to - in Facebook's language - "move fast and break things." Eventually some release is going to be problematic, and so the role of Operations is _not to slow things down to avoid the problem_ but rather to _hit the problem hard and fast_. Virtualization, as one example, gives us the ability to rapidly "roll back" entire operating environments to a "known good state," making the prospect of failure a little less frightening. _Plan for failure_, rather than trying to avoid failure entirely.

Ask yourself if you're the type of person who routinely plans for failure. For example, on every airline flight I take, I have a set of spare clothes in my carry-on, even if that's just my computer bag. I have a small stick of deodorant, because that's an item not included in airlines' amenity packs. I _assume_ there will be a failure in the trip, and I have simple plans in place to mitigate that failure. _Few_ people take these simple steps, though, and so when failure eventually does happen, they become angry, stressed, and uncomfortable - even when the causes of failure are completely outside human control, like weather. I plan longer layovers than most people - usually 2 hours domestically - and am often able to avoid a trip failure because of that extra margin.

In a DevOps environment, you have to accept that failure will occur. Your effort should go less into preventing that failure - especially through time-consuming "gates" that put a wall between coders and users - and instead put effort into being able to iterate and recovery quickly. In a true DevOps team, a buggy release doesn't mean you roll back to the last one - it means you release another one really quickly. That's moving forward, not rolling back, and having the capability to do that is the main hallmark of a DevOps-ready organization.



