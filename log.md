# 100 Days Of Code - Log

For the first project, I'm going to be working on a small guard-clauses library written with C#. The goal is to reach productivity on dotnet core, as well as learn how to create and publish a Nuget package.

### Day 1: April 22, 2019

**Today's Progress**: Created the repository locally, adding the production and test projects using `dotnet new`. Created a "gh-pages" branch, so I can create a GitHub Pages site when the time comes. Created a repo on GitHub, added it as a remote and pushed the code to it.

**Thoughts:** I'm struggling with making unit tests work under dotnet core. I keep getting weird compiling errors and restore failings.

### Day 2: April 23, 2019

**Today's Progress**: Wrote some tests for the main class and made them all pass. Wrote tests first. I was able to get the tests running using Visual Studio.

**Thoughts:** Need to understand better about how versioning works in .Net Core. Also, I need to see how to set up the build and test running via command line.

### Day 3: April 24, 2019

**Today's Progress**: Not a super productive day. Struggled a little bit with building the lib on Visual Studio, despite everything working fine via command line. Despite my troubles, I was able to write a couple of tests for a new method and made them pass by implementing said method.

**Thoughts:** TODO - Learn more about .NET Standard, .NET core, the various options for target framework and how those things relate to one another. My knowledge about all of this is close to zero, which is a shame.

### Day 4: April 25, 2019

**Today's Progress**: Technically, it's already the 26th. But since I haven't gone to bed yet, I can still consider it as "today". And, technically as well, I haven't made any real progress today. Still struggling with the build on Visual Studio. I've decided to give up on VS2017 and just install the newly-released 2019 version. I hope I can figure this "build failing on Visual Studio" situation out soon, because it's getting old really fast.

**Thoughts:** Maybe the best course of action is to just give up on Visual Studio altogether—at least for now—and just use Visual Studio Code.

### Day 5: April 27, 2019

**Today's Progress**: Skipped a day yesterday. It was a very busy day and unfortunately I couldn't find the time to code. Today I went back to the challenge, which made justice to the name. Tried to download both Git and .Net core on a very poor internet connection. After several failed attempts, I gave up on that. Then I decided to setup CI on GitHub by using Travis CI. After a couple of failed attempts, time is up. I will continue tomorrow.

**Thoughts:** Need to put more thought and effort into preparing beforehand, so poor infrastructure or a slightly busier day don't become impediments.

### Day 6: April 28, 2019

**Today's Progress**: Finally fixed my Visual Studio problems by installing Visual Studio 2019. Now I can build and test both via command line and via the IDE. Added a new test and wrote the production code to made it pass, commited and pushed to GitHub, so I have something to show for it.

**Thoughts:** TODO: Fix the build on Travis.

### Day 7: April 29, 2019

**Today's Progress**: Made good progress. Wrote some tests and made them pass. Wrote documentation tags for all the public methods. I'd say the first attempt at a public API for the main class is done. Tagged as version "0.1.0".

**Thoughts:** TODO: Still need to fix the build on Travis. Need to research versioning in .Net core. Soon I'll need to add a license, changelog, contributing guidelines and stuff like that.

### Day 8: April 30, 2019

**Today's Progress**: Not a lot of progress. Still struggling with Travis CI. I'm tired after a hard day, so my mind is not as focused as I wish it was.

### Day 9: May 1, 2019

**Today's Progress**: Today I've decided to take a break from my own project and work on someone else's instead. And that's what I did: I've sent a PR to the [NodaMoney project](https://github.com/remyvd/NodaMoney).

**Thoughts:** Reading (and contributing to) other people's code is always a great way of learning new stuff. Let's try to keep that in mind.

### Day 10: May 2, 2019

**Today's Progress**: Still taking a break from my project. While waiting for feedback on my PR sent to NodaMoney yesterday, today I've decided to help on [NodaTime](https://github.com/nodatime/nodatime). Submitted a [PR](https://github.com/nodatime/nodatime/pull/1368) containing some tests that are used to automatically create documentation.

**Thoughts:** Working on other projects is nice, but must remember not to overdo it. Main focus should still finish my own project(s).

### Day 11: May 3, 2019

**Yesterday's Progress**: Forgot to log the progress yesterday, so let's do it now. Still contributing to [NodaTime](https://github.com/nodatime/nodatime). Sent [one pull request](https://github.com/nodatime/nodatime/pull/1369) by lunch time, and [another one](https://github.com/nodatime/nodatime/pull/1373) in the evening.

**Thoughts:** Made a silly mistake with the first PR, and sent broken code. Note to self: don't rush. It's not great to waste maintainer's time.

### Day 12: May 4, 2019

**Today's Progress**: Another hour of coding, split up in two periods of 30 min. More PR's ([first](https://github.com/nodatime/nodatime/pull/1375) and [second](https://github.com/nodatime/nodatime/pull/1376)) sent to NodaTime.

**Thoughts:** I really like contributing to Open Source, but tend to do it in bursts of intensity. It'd be nice to find a way of doing it consistently.

### Day 13: May 5, 2019

**Today's Progress**: My [latest PR](https://github.com/nodatime/nodatime/pull/1375) to NodaTime required some fixes. So I've spent today's hour of coding implementing them.

**Thoughts:** Gotta go back to working on my library. Probably tomorrow.

### Day 14: May 6, 2019

**Today's Progress**: My previous PR sent to NodaTime is still waiting for review. Today I submitted [another one](https://github.com/nodatime/nodatime/pull/1377).

**Thoughts:** Gotta go back to working on my library. I didn't managed to do it today, because of reasons. I can try again tomorrow, but perhaps it makes sense to continue working on NodaTime and get back to my project on the weekend.

### Day 15: May 7, 2019

**Today's Progress**: Still working on my latest [pull request](https://github.com/nodatime/nodatime/pull/1377) sent to the NodaTime project.

**Thoughts:** As I predicted, I still haven't been able to focus on my own project again. It's probably better to only get back to it on Saturday.

### Day 16: May 9, 2019

**Today's Progress**: After skipping a day, I'm back to my own project, at least for a while. But today was not a productive day. Still fighting with Travis CI.

**Thoughts:** Documentation for these kind of tools could be a little more helpful.  

### Day 17: May 10, 2019

**Yesterday's Progress**: This is the log for yesterday, May 10. So, I'm happy that after many setbacks, I finally have some progress to show. I've created [a throwaway project](https://github.com/carlosschults/ci-demo) in order to experiment with Travis. And I was able to get it working. Haven't tried to run the tests, but I'll probably do it today.

**Thoughts:** It's better to code as early I can in the day, so I'm not tired. Will try to keep this in mind, even though somedays there's no other timeslot available other than "really late".

### Day 18: May 11, 2019

**Today's Progress**: It's already the 12th, technically, but since I haven't gone to bed yet I can still count as today, according to [the rules.](https://www.100daysofcode.com/faq/). So, progress! I edited the travis configuration for the throwaway project I had created. I successfully set up test running! Now, next step is to apply what I've learned to the main project.

### Day 19: May 12, 2019

**Yesterday's Progress**: Today is May 13th, so I'm actually logging for yesterday. More progress! I've successfully configured CI for the throwaway project using AppVeyor. Now I think I'm ready to set up CI for the main project.

**Thoughts**: Need a little bit more discipline about logging.

### Day 20: May 13, 2019

**Today's Progress**: Ok, finally some progress. Today I finally managed to fix the build on Travis CI. Tomorrow I plan to configure CI on AppVeyor and maybe set up code coverage as well.

### Day 21: May 14, 2019

**Today's Progress**: Configured CI on AppVeyor. Now the next step is to set up code coverage.

**Thoughts**: I gotta wrap-up this "setting up CI" thing and get back to writing code ASAP.

### Day 22: May 15, 2019

**Today's Progress**: A little bit of progress today. Finally, I stopped playing with CI and got back to writing actual code. I've implemented a new method in the main class of [the library](https://github.com/carlosschults/nshield), along with unit tests and documentation.

**Thoughts**: Gotta put some effort into not doing the challenge late at night. It's hard to focus when I'm that tired.

### Day 23: May 16, 2019

**Today's Progress**: Implemented a new method for the guard clause [library](https://github.com/carlosschults/nshield). Additionally, I've added a tag to mark the second (minor) version and pushed it to GitHub. Today I learned that GitHub automatically creates a new release for your project when you push a tag to it. I was wondering just how to do that.

**Thoughts**: Now I need to focus on getting this thing ready for Nuget.

### Day 24: May 18, 2019

**Today's Progress**: I'm back after missing a day. So, today I didn't really code at all. I only have one commit to show for today, and that's just the creation of a .txt file storing the version number for the library. Spent the remaining of the time research about how to create a nuget package.

### Day 25: May 19, 2019

**Today's Progress**: Ok, today I've definitely made some progress. I was able to create a nuget package for learning purposes by following the tutorial on Nuget's documentation. Nice! I'm continuing tomorrow.

**Thoughts**: After I'm done creating and publishing the project, I need to look into how to automate the whole publishing process.

### Day 26: May 20, 2019

**Today's Progress**: Instead of continuing with the whole nuget thing, I've decided to implement some more methods, alongs with their tests. I'm also performing mutation testing, using [Stryker.NET](https://github.com/stryker-mutator/stryker-net). I've used just a few times but it's already given me some great insights about my tests.

**Thoughts**: TODO - Write documentation for the created methods, fix the tests with surviving mutants and write overloads for the types not covered today.

### Day 27: May 22, 2019

**Today's Progress**: Some more methods, some more tests. I feel the library is getting closer and closer to being ready for version 1.0.

**Thoughts**: Life gets in the way. I've missed another day yesterday, and today I was "forced" to code late at night. I feel tired and it's hard to focus, but it's better than not coding at all.

### Day 28: May 23, 2019

**Today's Progress**: Added XML documentation to the methods that lacked them. Also, fixed some unit tests (and added a couple more) in order to improve my mutation testing results.
