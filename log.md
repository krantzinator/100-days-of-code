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

**Thoughts:** Drop It was fairly cut and dry. Steamroller is proving challenging because I'm not sure why my `mapFn` is behaving the way it is. If I use the arrow function (as in the current version), the items `console.log()` as their number value. If I use `mapFn(this.x)` isntead, the items `console.log()` as `undefined`. I'm trying to find more examples of how the mapped function operates within `Array.from()`. Maybe the pollyfill will make more sense when I am not so tired. I also want to look at `Function.prototype.apply()` tomorrow and see if this would be useful.

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
