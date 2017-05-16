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
