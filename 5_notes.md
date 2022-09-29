# Models

*Questions for Club*
- What is the role of a model? Just to persist data and have attributes?
- How much do we want to look like a plain old ruby object?
- DataMapper-style caching vs ActiveRecord style caching
- Yehuda Katz on activemodel
- Did anyone try using FileModel in Rails?
- @noah could you go more into the DataMapper style caching discussion on page 83? Exercise 2. I think it has something to do with ORM but I wasn't entirely sure

*Comparable things*
- Stone
- Og

*Things that fought me*
- I wasn't able to get my curl request behaving! I tried a lot and reviewed some examples but it wasn't coming through in the env. need to review. Link: https://reqbin.com/req/c-sma2qrvp/curl-post-form-example#:~:text=To%20post%20form%20data%20with,%2Dform%2Durlencoded%20content%20type.

*Comments/Topics for Club*
- Book club mania! There are two at shopify and brandon weaver is livestreaming a community one as well. I think we can all pat ourselves on the back and say we've started a revolution! Long live rebuild rails!
- Something a little different. I'm gonna put everyone on the spot. This isn't a mindless little work gathering. I want us to get to know each other a little better. Now that you can brace yourself for being called upon, I want to go around the room and have everyone share something they did this weekend. Even if it was
- File store
  * I've seen a lot of smaller projects rely on this. I was looking through hobix which was a 2004 webblogging tool developed by _why and it would seem that a lot of things like comments would've just been written/read from filestore which is interesting.
  * What's the speed comparison like?
- Alternatives
  * What if I kept everything as raw ruby objects with attr_accessor and just stored and loaded them with marshal.dump and marshal.load? Keep it hard to reason from the human eye and I could possibly pass encryption over it too?
- A little trouble tidying up my params
- Bonuses
  * Tidied up my errors a bit. (Show before and after slides, using ruby debugger)
- Alternative Model implementations
  * virtus
  * og
  * stone -- file implementation
- I love the tone of the book. e.g.:
  * > Take another bow. You’ve earned it.
  * Wish so many texts I just feel stupid sometimes
- I liked the note about the "include" from the inherited object so you don't have to specify the entire namespace. That's also something I think in frameworks that requires careful mastery
- I liked that we're getting more chances to play with `Dir` (page 78_)
- StrongParameters ref (80) -- Rails 4?
- Ha! sneaky way to implement #create without making us do a form in the web view ;) nice
- Also handy to show off curl. I think it's one of those tools you could go far in your career without necessarily developing a big muscle memory with it.
- _find_all_ methods! fun using plain old ruby! While leaning on all
- _find_all_by_ method missing was fun
- There was a comment about older ruby versions and responds_to? being used. I believe recently I saw a use case where you want to pair up your responds_to with method_missing?
