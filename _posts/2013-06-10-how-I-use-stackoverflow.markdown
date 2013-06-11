---
layout: post
title: "How I Use Stack Overflow"
date: 2013-06-10 19:45
comments: true
external-url:
categories: [Stack Overflow]
---




>The problem with self directed learning is that our ability to learn is often constrained by the very problem we are trying to solve, our limited knowledge of a field.

One of the fundamental truths of the software industry is that self driven learning is a necessity for staying relevant.  Especially when working on evolving platforms like the web and mobile, things change fast.  The web frameworks of 2005 have little direct relevance to web development in 2013, and mobile development was a category that didn't really exist in 2005, at least not in a form recognizable to todays world.  If you want to be at the top of your field, or even anywhere close, learning and growing independent of whatever your current task happens to be is incredibly important.  But there are issues with this.

The problem with self directed learning is that our ability to learn is often constrained by the very problem we are trying to solve, our limited knowledge of a field. Some of these problems resolve themselves quite easily.  A beginning Javascript programmer may not know that he needs to include a script in order to use the jQuery syntax he's seen online, but he'll discover it very quickly when his script fails to run [^4].  However its quite possible to go on programming for years without realizing that its bad practice to couple your view and model too tightly, or even without gaining a deep understanding of how a web application model actually works. We create our models of how programming works, and its easy to stay inside those closed doors.

### Enter Stack Overflow

If the problem is that we don't ask the right questions, a Q&A site seems like a dubious solution.  But [Stack Overflow][so] has been the best tool I've ever found for self-directed learning. Its a crazy hybrid between a wiki, Q&A site, forum, and video game originally conceived by [Jeff Atwood][ja] and [Joel Spolsky][js] back in 2008.  With ambitions to become a comprehensive programming archive for the web,  the site has become a critical resource for programmers. In fact its the [92nd most visited website in the world][alexa] as of June 2013.

    TODO

### How To Learn

> Questions asked by other people that you can't answer are the best part of Stack Overflow

Stack Overflow really began making a difference in my work and learning though when I moved past asking questions and also began contributing.  At the end of 2012 I started making a serious effort to begin answering questions, both as a way to contribute back to the community that had benefited me so much, and as a way of learning about my primary language at work, Javascript.  

I was, and am, by no means a Javascript expert.  But I have learned a lot through the following process:

1. Browsing regularly through new questions under the javascript and coffeescript tags.

2. Picking out interesting [^2] questions that haven't been answered satisfactorally yet. [^1]  If there are good answers that I can't add to substantially, I'll upvote them.  If there are harmfully misleading or unhelpful answers I may downvote them with a comment.

3. If I know the answer to the question, I answer it, with an attempt to cite some sources for further information.  This happens sometimes, but much more often I don't know the answer off the top of my head.  This then is where learning takes place.  

4. If I don't know the answer I'll try to research it.  This may involve some combination of
    1. Making a test with jsFiddle and learning about the behavior hands on.
    2. Looking up the relevant spec on MDN, github, or library documentation
    3. Looking at related Stack Overflow questions to see if there are relevant resources or information there.
    4. Once I have an answer I'll return to the original question.  Sometimes, usually in fact, somebody else will have beaten me to a response. If that happens, I'll evaluate whether I can add value.  If I can, I'll answer, if not I'll upvote the best answer, and move on

    This for me is where Stack Overflow really begins to show benefits.  When I do the research to answer a question I usually learn many things along with whatever the specific question was. Questions asked by other people that you can't answer are the best part of Stack Overflow.  They are an opportunity to not just expand your field of knowledge, but also to think about problems and solutions that you had never even contemplated.[^3]




[^1]: Satisfaction is of course relative.  Sometimes the user who asked the question may be happy with an answer that I think is wrong or questionable, sometime I  may feel like the question has been answered well even if the original poster did not get the exact answer he was looking for. 

[^2]: Interesting for me means vanillaJS questions or referencing web technologies or libraries that I'm interested in.  I'll take a look at other questions, but I generally avoid trying to answer questoins that I feel would require real understanding of a framework to answer idiomatically if I don't already know the framework.

[^3]: Along with contemplating for the thousandth time why people try to use jQuery without including the library in a script tag first.

[^4]: And he'll probably ask a question on Stack Overflow about it first

[so]:http://stackoverflow.com/
[ja]: http://www.codinghorror.com/blog/
[js]: http://www.joelonsoftware.com/
[alexa]: http://www.alexa.com/siteinfo/stackoverflow.com