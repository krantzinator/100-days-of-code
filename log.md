# 100 Days Of Code - Log

### Day 1: May 9, 2017

**Today's Progress**: FreeCodeCamp's algorithm on Smallest Common Multiples

**Thoughts:** Very math-heavy for 10pm fighting sickness. I think I have a decent start, but next is going to be some sort of loop (recursion?) to do these calculations for every number in the range.

**Link to work:** [Smallest Common Multiples](https://github.com/krantzinator/freecodecamp-course/tree/master/fed-algorithms/smallest-common-multiple)


### Day 2: May 10, 2017

**Today's Progress:** FCC's algorithms: Smallest Common Multiples and Finders Keepers

**Thoughts:** In typical FCC fashion, after the SCM algorithm took me two hours to solve, the following challenge (Finders Keepers) took me less than two minutes. The challenge was literally to implement the Array.prototype.filter() function, and return only the first item filtered. I didn't even add my solution to my github because it seemed too simple? I guess I'll add it for propriety or whatever.

**Link to work:** [Smallest Common Multiples](https://github.com/krantzinator/freecodecamp-course/tree/master/fed-algorithms/smallest-common-multiple), [Finders Keepers](https://github.com/krantzinator/freecodecamp-course/tree/master/fed-algorithms/finders-keepers)

### Day 3: May 11, 2017

**Today's Progress:** FCC's algorithms: Drop It and Steamroller (started)

**Thoughts:** Drop It was fairly cut and dry. Steamroller is proving challenging because I'm not sure why my `mapFn` is behaving the way it is. If I use the arrow function (as in the current version), the items `console.log()` as their number value. If I use `mapFn(this.x)` instead, the items `console.log()` as `undefined`. I'm trying to find more examples of how the mapped function operates within `Array.from()`. Maybe the pollyfill will make more sense when I am not so tired. I also want to look at `Function.prototype.apply()` tomorrow and see if this would be useful.

**Link to work:** [Drop It](https://github.com/krantzinator/freecodecamp-course/tree/master/fed-algorithms/drop-it), [Steamroller](https://github.com/krantzinator/freecodecamp-course/tree/master/fed-algorithms/steamroller)

### Day 4: May 12, 2017

**Today's Progress:** FCC's algorithms: finished Steamroller and started Binary Agent (set up files, started reading on converting binary to decimal)

**Thoughts:** This was a hard one. I'm traveling this weekend, and I've been up since 4am with no naps or coffee. Finishing up Steamroller wasn't too bad though, since I still remembered the ideas I had from yesterday on things to try. Binary Agent looks like it'll be another 2+ hour challenge, since I'll have to invest a bit of time into understanding the process of what I'm trying to automate.

**Link to work:** [Steamroller](https://github.com/krantzinator/freecodecamp-course/tree/master/fed-algorithms/steamroller), [Binary Agent](https://github.com/krantzinator/freecodecamp-course/tree/master/fed-algorithms/binary-agents)

### Day 5: May 13, 2017

**Today's Progress:** FCC's algorithms: Binary Agents; also went back and made Smallest Common Multiples more efficient

**Thoughts:** I spent a decent amount of time trying to work out a way to convert binary to decimal, before learning about `parseInt()`. After I had that piece it was fairly straightforward to finish the solution. I do tend to default to `forEach()` though, and will start challenging myself to get practice on other iterator functions in JavaScript. I also added a line to the SCM algorithm so that it made sense for me to start by finding the LCM of the two largest numbers in the range, rather than the two smallest.

**Link to work:** [Binary Agent](https://github.com/krantzinator/freecodecamp-course/tree/master/fed-algorithms/binary-agents), [Smallest Common Multiples](https://github.com/krantzinator/freecodecamp-course/tree/master/fed-algorithms/smallest-common-multiple)

### Day 6: May 14, 2017

**Today's Progress:** FCC's algorithms: Everything Be True, Arguments Optional

**Thoughts:** Posting this late, as I worked on these in an airport waiting lounge. Yesterday was so hectic, I was really proud of myself for squeezing in 45 minutes to work on algorithms while at the airport. (To fulfill the 1-hour requirement, I then spent at least 15 minutes mulling over this Closures concept ;) Seriously, Closures is blowing my mind. I think I could have hacked together a solution at the airport if I really wanted to, but I wanted time to mull this over and try to get it to sink in to that level in your brain where you _get_ something. Plus, I was also feeding a baby after the aforementioned 45 minutes, so it was complicated to type! Closures though -- this is a new concept for me. I'm still in awe of it.

**Link to work:** [Everything Be True](https://github.com/krantzinator/freecodecamp-course/tree/master/fed-algorithms/everything-be-true), [Arguments Optional](https://github.com/krantzinator/freecodecamp-course/tree/master/fed-algorithms/arguments-optional)

### Day 7: May 15, 2017

**Today's Progress:** FCC's algorithms: Arguments Optional

**Thoughts:** Working through the solution took about 30 minutes (love using console.log with jasmine-node to find errors in my code!). I spent the rest of the time getting lost in JavaScript documentation. I wanted to find a way to use BIFs rather than the stringed `if` statements. Instead, I learned that MDN has whole writings on the finer points of JavaScript 2016! One of these was on the Closures concept, and I also looked over W3School's explanation of Closures. I know \#100Days is all about writing code and you're not supposed to count reading time, but I am. So there :). Today I am still a bit distracted, both from the sheer levels of exhaustion from yesterday and because of a personal matter from this afternoon, and I count deepening my understanding of this concept as a win. Although I still don't see how to replace those nested `if` statements, but maybe sleeping on it will help. Or maybe I'll come back to it in a couple of weeks and see if future-me has learned a few more things!

**Link to work:** [Arguments Optional](https://github.com/krantzinator/freecodecamp-course/tree/master/fed-algorithms/arguments-optional)

### Day 8: May 16, 2017

**Today's Progress:** FCC's algorithms: Validate US Telephone Numbers and Record Collection (incomplete)

**Thoughts:** FCC tells me I already completed Record Collection, but why not do it again. I work with JSON objects a fair amount at work, and I could always use more practice. I tend to forget sometimes if I'm working with a JSON or Ruby objects. The RegEx algorithm wasn't challenging per-say, although I'm sure it could be cleaned up. But then again, isn't RegEx always a bit messy? I'm excited to finish the Record Collection tomorrow. And I'm excited that at the 35 minute mark I thought about phoning it in, but kept pushing until I am here, at 57 minutes. Woot! OK my stomach hurts; chugging water and going to bed.

**Link to work:** [Validate US Telephone Numbers](https://github.com/krantzinator/freecodecamp-course/commit/7ec6f2947b792cc5bfe527e98c173cc5ceefffbb), Record Collection [commit 1](https://github.com/krantzinator/freecodecamp-course/commit/96d875ba452aeb1390a703422dff3862027e8397) and [commit 2](https://github.com/krantzinator/freecodecamp-course/commit/ad2a6768bab6298b1d2fcb089dbe7362c2c08d4c)

### Day 9: May 17, 2017

**Today's Progress:** FCC's algorithms: Record Collection and Symmetric Difference (incomplete)

**Thoughts:** My new Record Collection solution looks basically the same as my old Record Collection solution. Have I really made no progress? Or maybe that is one of the more efficient ways of solving the problem? I'll go with the latter. I had a cider tonight whilst workingo n Symmetric Difference, and I am remiss to say that my tolerance is shit and therefore I did not make very good headway with this algorithm. I started down a path I knew would take a lot of refactoring/redirection once complexities were introduced. Le sigh.

**Link to work:** [Record Collection](https://github.com/krantzinator/freecodecamp-course/commit/3d11a14ed5e355287817131b9fc2fc738799e297), [Symmetric Difference](https://github.com/krantzinator/freecodecamp-course/commit/617bca6b15783c19c19b1c0a000e36b6b4fc985f)

### Day 10: May 18, 2017

**Today's Progress:** None, really, but I did work more on Symmetric Difference

**Thoughts:** I'm finaly pushing through until I understand this `reduce` stuff. Spent a good amount of time reading through different descriptions and examples of it. I understand the logic, I do. I mean, I know what it does. I am still pushing for that conceptual knowledge of _why_, and how it can be used.

**Link to work:** [Symmetric Difference (this is pure crap)](https://github.com/krantzinator/freecodecamp-course/commit/c647c1e310a91e19fa895252b3a37e079741336f)

### Day 11: May 19, 2017

**Today's Progress:** Finally finished Symmetric Difference

**Thoughts:** Holy cannoli. I thought I understood `Array.prototype.reduce`, but I **do not.** I get the simple case, but apparently going beyond doing one simple action with the accumulator and active value was a serious brain workout. I want to know how to translate the polyfills, because I read through the `reduce` polyfill a few times trying to really ingrain what was happening. I'm closer to full understanding, but this is a difficult one for me to grasp.

**Link to work:** I started from the beginning, in true TDD fashion. Symmetric Difference [commit 1](https://github.com/krantzinator/freecodecamp-course/commit/f4005b55f11358c468d8d6109d0896774ea32ad4), [commit 2](https://github.com/krantzinator/freecodecamp-course/commit/e6c02a20efdf7f3f6adc9e31d123f82212c77e9f), [commit 3](https://github.com/krantzinator/freecodecamp-course/commit/4a90ed2996171efd82949d72994c783cc37914c6), [commit 4](https://github.com/krantzinator/freecodecamp-course/commit/a5be621e0e814fe2e66abd92c3e4a0464ee2ec92)

### Day 12: May 20, 2017

**Today's Progress:** Mocked out the next algorithm in FCC; tested out Twitch setup

**Thoughts:** I'm losing a sickness fight right now, so rather than try to make my brain work, I am chugging ginger+tumeric tea and doing things that don't take a whole lot of critical thinking skills. Hope to be rested back up by tomorrow. Once I'm healthy, I'm going to do a livestream of Ghost vs Pelican in preparation for moving my personal site off of Jekyll.

**Link to work:** [Exact Change](https://github.com/krantzinator/freecodecamp-course/commit/93264b94bac2a5ea79afdb3db5fd364409121ebc)

### Day 13: May 21, 2017

**Today's Progress:** Finally made good on a goal to livestream a comparison of Ghost vs Pelican!

**Thoughts:** Don't watch this. I spend ~25 minutes installing Ghost and trying to find where in their docs they let me edit things in my text editor (spoiler: they don't; it's all through the admin panel). Then the rest of the time is spent trying to fix Pelican and vi errors. Womp womp.

**Link to work:** [Livestream](https://www.twitch.tv/videos/146082529)

### Day 14: May 22, 2017

**Today's Progress:** Reinforced my knowledge of `.filter()` and `.reduce()`, mainly

**Thoughts:** I wanted to make sure I fully understood what was happening with my Symmetric Difference solution. The console-logging I set up had me confused, and thinking maybe I really didn't understand this `reduce()` business after all. Turns out combining `reduce()` and `filter()` just, ya know, makes things a little more complex. Once I stepped through it clicked. Then I started reading up on Objects for the next algorithm (Exact Change), and learned that there is a `.isFrozen()` method, which of course made me think of Elsa, and then spawned [this mildly entertaining moment on Twitter](https://twitter.com/rustbeltrachel/status/866808655638929409).

**Link to work:** Not much today; included the result of some console-logging on my [Symmetric Difference](https://github.com/krantzinator/freecodecamp-course/tree/master/fed-algorithms/symmetric-difference) solution, and I am starting to think through what I want my approach to be on [Exact Change](https://github.com/krantzinator/freecodecamp-course/tree/master/fed-algorithms/exact-change)

### Day 15: May 23, 2017

**Today's Progress:** Read up on prototypical inheritance and proper use of `.bind()`; took `.bind()` out of my code and started over again with Exact Change algorithm

**Thoughts:** Made a lot of crappy progress, then scrapped it and started over. It's valuable to see what doesn't work, though, right?

**Link to work:** [Exact Change](https://github.com/krantzinator/freecodecamp-course/commit/6218823a9bd6d0418893b9e8cd74e582754a10cf)

### Day 16: May 24, 2017

**Today's Progress:** Nothing fancy; trying to understand how/why everything in JavaScript is an object, and objects themselves are the same kind of objects as arrays, which doesn't make sense to how I had categorized things in my mind because you can't use the same methods on arrays and objects, so how are they the same?

**Thoughts:** See above

**Link to work:** [Exact Change](https://github.com/krantzinator/freecodecamp-course/tree/master/fed-algorithms/exact-change)

### Day 17: May 25, 2017

**Today's Progress:** Downloaded VSCode, started an Angular project by way of Treehouse

**Thoughts:** Man, the break from algorithms is nice. It's nice to build something, put pieces together, see how it works. I have some ideas on solving that algorithm, and I'm, in a way, looking forward to getting back to it. But also really enjoying this building thing, too. Playing with Typescript has been fun, too. I've heard buzzwords for a while now about "statically typed" and "strongly typed" languages. Now I understand what that means; and I've got to say, I like how Typescript lets you declare types for a variable. I see the benefits to both -- it's nice to not have to worry about it, but it's also nice to have that layer of built-in error-catching.

**Link to work:** [Angular project](https://github.com/krantzinator/treehouse_photo_blog)

### Day 18: May 26, 2017

**Today's Progress:** Working through Angular on Treehouse

**Thoughts:** I'm understanding the inner workings of an Angular app structure.

**Link to work:** [Angular app - newest commit](https://github.com/krantzinator/treehouse_photo_blog/commit/678f61baf56ad2e7bbe7b4caad2fa3288a8a832f)

### Day 19: May 27, 2017

**Today's Progress:** Ember work through Big Nerd Ranch's Front End Web Dev book

**Thoughts:** I need to whiteboard the Ember setup. When I get back around internet, I want to draw out a comparison of how Angular vs Ember apps are structured.

**Link to work:** [BNR app](https://github.com/krantzinator/front-end-dev-book/commit/352854ec9bc05fb94c11f1cbcd6bf40cc0a568ab)

### Day 20: May 28, 2017

**Today's Progress:** Finished up the BNR FEWD book and accompanying Ember app

**Thoughts:** I'll be real, it's been hard to focus on code this weekend -- but not because of the holiday. New problems in my life, new people I need to help...but on the coding side, this has been interesting. Ember's structure is so complex. I say that having not used a ton of frameworks, but Ember seems very heavy. Underneath my `app` I have `adapters`, `components`, `controllers`, `helpers`, `models`, `routes`, `styles`, and `templates`. and of course all the other base stuff, like `config` and `vendor` and the bower stuff. The templates pull from the models and feed the controllers which interact with the routes and the components, and it seems like excessive compartmentalizing. I know Ember was created to solve specific problems, and includes all of this because it helps you avoid complexity in other ways. I think I haven't yet encountered enough of the complexities it solves to really appreciate what it is doing. When I get back to internet, I want to look up the source code of applications that use Ember and see some of its problem-solving capabilities in action.

**Link to work:** [BNR app](https://github.com/krantzinator/front-end-dev-book/commit/ca173a1015040c64f005064773bccdb7eda9b0d3)

### Day 21: May 29, 2017

**Today's Progress:** For mental and physical health reasons, I am taking a break today. A 'sick day', as it were.

### Day 22: May 30, 2017

**Today's Progress:** Still feeling sick, so did a very modest amount of Angular work

**Thoughts:** Hit a compatibility bug! Woot. Worked on solving it for ~15 minutes, but I really need to get sleep tonight since I'm still sick. Also, I participated in the #DevDiscuss twitter chat, and I tweeted one thing and have an overflow of mentions and likes. This is a very active Twitter chat! Check it out.

**Link to work:** [Angular app](https://github.com/krantzinator/treehouse_photo_blog/commit/cf28deddf5d12f65873d99d777895251b07ae05f)

### Day 23: May 31, 2017

**Today's Progress:** More Angular and npm things

**Thoughts:** Today was fun again. I learned about peer dependencies and how they work, because somewhere along the lines I got one of my angular modules listed in a different version than the rest of the angular modules in my `package.json`. Did some `npm uninstall` magic, changed the version number, and reinstalled my dependencies. Fixed!
I also took a few notes:
  - Angular uses the constructor function to instantiate components and wire up dependencies _(side note: had a fun conversation on the AkronWIT Slack channel today about Ruby classes and when you need to use instantiation and when you are good with defining methods with `self` and not needing to instantiate. Describing the conversation as "fun" is not even a little bit sarcastic! I love that community.)_
  - "@" indicates the import is coming from Angular's namespace
  - when creating a component, you add dependencies by setting them as parameters of the constructor function
  - `--save` flag with `npm install` ensures the package gets included in your `package.json`
  - `--save-exact` is optional but best practice for working on teams or with a continuous integration service; it ensures your package is added to `package.json` exactly as you stipulate, and not with the default version npm dictates (probably usually the most recently stable versions of things?)

**Link to work:** [Angular app](https://github.com/krantzinator/treehouse_photo_blog/commit/f848eb8793cd5fa6f5014c60ce574d83b59e0f30)

### Day 24: June 1, 2017

**Today's Progress:** More Angular

**Thoughts:** I now see some of the value Ember adds. I do like the `ember generate` command, as creating new components and their various pieces in Angular takes a small amount of extra time that adds up.

**Link to work:** [Angular app](https://github.com/krantzinator/treehouse_photo_blog/commit/9625ced6e15d3be4b379616c8e49cf428c592c27)

### Day 25: June 2, 2017

**Today's Progress:** More Angular

**Thoughts:** I learned that `ngStyle` doesn't work the same in Chrome as in Firefox. Not sure why as I have to get ready for work now, but I'll look into this tomorrow.

**Link to work:** [Angular app](https://github.com/krantzinator/treehouse_photo_blog/commit/f8e07de3ac15fd67b55fc9a995a6dfff2b4b32e7)

### Day 26: June 3, 2017

**Today's Progress:** Starting my own Angular app

**Thoughts:** I've only just downloaded the base Angular starter app, and am figuring out where to start with my project. I'm sure this app will move at a snail's pace as I work through the docs. Also, either the sickness I had earlier this week is really sticking around with a vengeance, or we've picked up something entirely new from daycare. Yay daycare. So definitely did not do a full hour today, and I'm OK with that.

**Link to work:** Nothing to show yet.

### Day 27: June 4, 2017

**Today's Progress:** Still poking around this Angular app

**Thoughts:** I really did not want to code today. The last week has been stressful, the coming week is going to be stressful, my throat is still sore, and so I spent an hour on twitter putting off today's code. And then when I realized I could have gone to bed already had I started coding instead of twittering, I buckled down. It took a while to find out how to actually **start** an Angular project. Apparently the Quickstart option off of Angular.io isn't actually something you want to turn into an application? So I kept looking, and found `angular2-seed` and used that. Indeed, the layout of this base app looks a lot more useful in understanding Angular's pieces, and starting to form my own app. The rest of today's time was spent reading through this seed code base and grasping what's happening. I noticed a few cool things with Angular's form validation. I also wondered why every component has to have its own CSS file, when (at least in this initial seed) all the CSS files are the same. In this case, all the CSS files are also empty. Maybe if you have components share CSS, would something like that go in the `shared` directory? Or is `shared` only for shared services? I think it's only for shared services. I haven't looked any of these questions up yet, I'm still contemplating them on my own. I presume keeping the CSS files separate within each component is a better long-term plan, because you'll likely have different CSS as time goes on. But then, why build something before you need it? But then again, I also assume one of the benefits of Angular is how cleanly separated it keeps its various pieces, and this of course lends to that separation. This is a bit rambly. I warned you my brain is distracted. I'm getting how `app.routes` and `app.module` work. Oh you know, it looks like there's an `app.component.html` and an `app.component.ts`. I assume this answers my CSS question -- global CSS would go in an `app.component.css`, which this seed project does not include, but that a quick glance back at my last Angular project shows is, in fact, a viable option. I can now go to bed happy. I want to read through some Angular projects code bases. If you have some to recommend, let me know.

**Link to work:** It's nothing fancy. I changed some text, nothing much else yet. Lots of code reading done today. [Angular app](https://github.com/krantzinator/angular-list-app)

### Day 28: June 5, 2017

**Today's Progress:** Deleted a bunch of stuff out of the Angular seed app!

**Thoughts:** I really wanted to not spend a lot of time coding today. I am so excited for next week's Monday to be here you don't even know. But I'm mostly healthy now, and back to the trend of getting sucked into code stuffs. The power of taking the first step! Anyway, I did more Angular stuff. Deleting a piece of code out of the angular2-seed was more of a learning experience than I realized. I had to dig the tiniest bit into the construction of an Angular app and remove all connections the old component had to its old life. Then, and only then, would `npm start` let me view my running app. I love the feeling of a mental model coming together in your head!

**Link to work:** [Angular app - today's commit](https://github.com/krantzinator/angular-list-app/commit/7b9678b1b33a9aef8cbdf3099d0e85cbe013f496), [blog post on angular ramblings](http://rachelkrantz.com/blog/2017/06/05/angular-ramblings/)

### Day 29: June 6, 2017

**Today's Progress:** Lots of code reading; started new Angular app (see below)

**Thoughts:** OK so apparently, the `angular2-seed` app I had started with is outdated. Which _does_ make sense, since we are now up to Angular 4. I found a typo in the `package.json` and was so excited, but I see there are a few unaccepted PRs, as well as a top issue asking if the repo is dead wherein people commented that all the cool kids use `quickstart` now. Ugh, FINE. I glanced at `quickstart` again, and what do you know, it makes more sense to me now than it did a couple of days ago. I guess this coding every day thing is _working_ or something. As mentioned above, today was largely code reading, as I dug into the Angular source code briefly to see if I could make heads or tails of it, and also played around ever so slightly with the `angular2-seed` setup before nixing that project and moving on with my life. I swear to you, I'm going to start writing more soon. Ironically, my eagerness to jump in and start writing without doing a tutorial is what hosed me -- I skipped the initial Quickstart walkthrough in the docs, thinking, "Nah I'll learn by immersion!" Which, I mean, is sort of working? Moral of the story: tutorials aren't _all_ bad, especially when you're starting with a new framework. In fact, that is their express purpose in life.

**Link to work:** [Foreal foreal Angular app](https://github.com/krantzinator/shopping-list)

### Day 30: June 7, 2017

**Today's Progress:** _actually_ coding in my very first Angular app

**Thoughts:** This got fun today! I successfully pulled myself out of a rabbit hole or two I started to go down in analyzing Angular's architecture (alliteration FTW), and I also successfully forced myself to start small. I am building one piece at a time, not the final application all at once. Random notes: I'm not sure what all these `.js` files do in this Quickstart-based repo (since Typescript, `.ts`, is the language used). I will figure that out later. I'm going to get into the magic of Angular forms over these next few days. Other thing I want to figure out is why I get 404 errors from `systemjs`. After a rough start, I'm liking the Angular docs, and Angular in general. We shall see.

**Link to work:** [Angular app](https://github.com/krantzinator/shopping-list/commit/218f97fc9dd04ee6819674a2f546421cbc2b7653)

### Day 31: June 8, 2017

**Today's Progress:** dissected object behavior

**Thoughts:** Objects. Just when I think I get them, something new happens.

**Link to work:** I don't think I pushed up any code from this. I did a lot of editing, `npm start`-ing, deleting, and reading docs.

### Day 32: June 9, 2017

**Today's Progress:** trying a few things with objects and Angular and seeing what happens

**Thoughts:** I have this problem where I can't do the simple thing because I want to understand the full picture. That's where I'm at right now. I'm working through this slowly as I branch out with each piece and figure out the connecting pieces. I'm slowly putting this puzzle together.

**Link to work:** [Angular app](https://github.com/krantzinator/shopping-list/)

### Day `null`: June 10, 2017

**Today's Progress/Thoughts:** I was in a wedding on this day, and I meant to code, I really did. But 14 hours of driving in the previous days + baby + all day wedding responsibilities == mass levels of exhaustion. My brain was worthless, and I collapsed into bed without showering. I have found my programming limit.

### Day 33: June 11, 2017

**Today's Progress:** Fixed bugs! Added CSS styles! Drank coffee! (in reverse order)

**Thoughts:** Today was fun -- again! It's amazing what being relatively well-rested will do for you. Only has ~8 hours of car time today, so ooh lah lah. Back home, and feeling good. Ran into my old nemesis CSS again, but this time was nicer as I was able to refer back to the `position` stuff I learned from Big Nerd Ranch's Front End Dev book. Realized I had typos of mixing up `:` and `=` with my variable declarations and object/function assignments under my `AppComponent`. I've put in a couple of hours tonight, and am doing the "quit while you're ahead" thing. I've been following Angular's docs so far, but tomorrow I'm going to off-road a bit and add some collapse functionality to my `<span class="topic">`.

**Link to work:** [Angular app](https://github.com/krantzinator/shopping-list/commit/6d7ba7387d39488982aec6ae1ce63229669c6052)

### Day 34: June 12, 2017

**Today's Progress:** troubleshooting and doc reading

**Thoughts:** Spent some time poking around a React app someone asked me to look at. Then I dove into figuring out a way to collapse elements within Angular. All the internet searches kept turning up Bootstrap, along with why using bootstrap with angular is tricky. I am trying to avoid Bootstrap at the moment, and tried to work out a solution with just angular. Started down the directives rabbit hole, then came back around to editing the component's template directly. Once I have the template html/css working, I may pull it out into a directive.

**Link to work:** [Angular app](https://github.com/krantzinator/shopping-list/)

### Day 35: June 13, 2017

**Today's Progress:** lots of reading!

**Thoughts:** Researched a bit more on bootstrap/angular and if it's a good idea. Asked some people for input, and I'm going to work to implement ngBootstrap tomorrow. Didn't get to it today, as I also spent time reading through a Stir Trek talk on Angular I wish I had gone to, and a very basic summary of Angular written by the Ionic team. I like interspersing my building with reading, as one of the most fun and powerful ways for me to learn is to introduce myself to a concept that is completely foreign (tutorials, reading things people wrote on the topic such as slides from talks), try using that stuff (building), then reading more (or re-reading) things and intros people wrote on the topic. After using something for the first time, and not quite grasping the full picture, I find reading explanations on the very things I've used brings on all those "ohhhh" light bulb moments that stick. I had a few of those "aha" moment today.

**Link to work:** None today

### Day 36: June 14, 2017

**Today's Progress:** added ng-bootstrap to my angular project

**Thoughts:** I'm sick (I get sick a lot, don't I? I might try to do too much and not sleep enough...), so it's an abbreviated day. I spent some time trying to figure out what the ng-bootstrap docs mean when they say to install Bootstrap 4, since other things I had read said not to use Bootstrap's jQuery with Angular. I couldn't find more specific instructions, so I just included the cdn for the CSS in the app's index files, then I installed ng-bootstrap. I'll play with it tomorrow and see if that worked.

**Link to work:** [Angular app](https://github.com/krantzinator/shopping-list/)

### Day `null`: June 15, 2017

**Thoughts:** I didn't mean to do another sick day so soon, but today I spent 2 hours talking with a project team I'm on, as well as being point-person for all things baby since my husband is working late tonight. Oh, and I've got all this congestion and scratchy throat and stuff. I'm trying to rationalize it by saying, you know, I talked about programming things in that meeting. Or database schemas anyway. But yeah. Basically, I need to sleep now.

### Day 37: June 16, 2017

**Today's Progress:** I did work, but didn't log it. I swear. I lost a day in here somewhere with my logging, but I promise you I did not miss two days in a row.

### Day 38: June 17, 2017

**Today's Progress:** algorithm work

**Thoughts:** Man, it is really tough to stick with this right now! I am moving, so weekends are terrible for getting things done as I'm packing + keeping tabs on a baby. I really didn't think I'd get to this today, but I did. High five! I dug more into the algorithm from FCC on calculating change from a drawer. I implemented functionality to first assess if there are sufficient funds to give change, and then check if it's a wash (i.e. return "Closed"). I still need to work out the mechanics of counting how many of each type of currency I need to return in change, but I'm on a good roll here and I'm practicing this concept of "quit while you're ahead" so I'm going to stop now, as I think I'm on a good track. More tomorrow!

**Link to work:** [Exact Change algorithm](https://github.com/krantzinator/freecodecamp-course/fed-algorithms/exact-change)

### Day 39: June 18, 2017

**Today's Progress:** algorithm work

**Thoughts:** Oh JavaScript. Why does `typeof` an array return `'object'`. Other than that, making good progress on this. Last thing left to do is make sure there is enough change in the till for the particular currency; otherwise, will need to supplement with other types of change. Feeling good.

**Link to work:** [Exact Change algorithm](https://github.com/krantzinator/freecodecamp-course/fed-algorithms/exact-change)

### Day 40: June 19, 2017

**Today's Progress:** algorithm work

**Thoughts:** Had a few problems with floats and integers. Then when I thought I had my code done, had some troubles translating it into code FreeCodeCamp can verify. THEN I realized I had skipped a test and actually my setup causes a stackoverflow when there isn't the correct amount of change (even if there is, technically, _enough_ change). I got lost in this tonight. Emphasis on lost. But at least it's fun again! I'm forcing myself to sleep because I know I'll feel like crap in the morning, and also I'm at the stage where I need to step away so I can come back and see the solution in two minutes or less.

**Link to work:** [Exact Change algorithm](https://github.com/krantzinator/freecodecamp-course/fed-algorithms/exact-change)

### Day 41: June 20, 2017, part 1

**Today's Progress:** FINISHED THAT DAMN EXACT CHANG ALGORITHM

**Thoughts:** Floating numbers suck. I was also unnecessarily using a recursive statement, which was quite the heavy stack load. Oops. I've heard/read that a best practice is to _always_ have an `else` statement if you have an `if` statement. I often ignore that advice, but I do so thinking of the advice and choosing to ignore it. I am going to stop ignoring that advice now. It's good advice, Brent.

**Link to work:** [Exact Change algorithm](https://github.com/krantzinator/freecodecamp-course/fed-algorithms/exact-change)

**More notes:** Forgot to include all the links I've used to read about how annoying floating point math is annoying. [StackOverflow: Is floating point math broken?](https://stackoverflow.com/questions/588004/is-floating-point-math-broken), [Floating point guide](http://floating-point-gui.de/basic/), [What Every Computer Scientist Should Know About Floating-Point Arithmetic](http://docs.oracle.com/cd/E19957-01/806-3568/ncg_goldberg.html)

### Day 42: June 21, 2017

**Today's Progress:** just playin' around

**Thoughts:** I started playing with angular-cli yesterday, and continued today. Partially inspired by a post I saw on how you should practice all of the small, setup pieces of ~React~ Angular until they are second nature. So I made this repo to do that in. Changing little things here and there over and over as I move forward and cement this stuff in my brain.

**Link to work:** [more angular](https://github.com/krantzinator/angular-experiments)
