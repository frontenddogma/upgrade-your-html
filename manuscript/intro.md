# Intro

HTML is the backbone of the Web. Or one of the backbones of the Web. Or the backbone, again, for us as web developers, because we could build a website without JavaScript, even without CSS, but without HTML, _any_ HTML, no, we couldn’t.

As HTML is so important and yet also so easy, everyone writes HTML, and everyone says they can write HTML. And with that they don’t just mean they’re able to write HTML, but that they write _good_ HTML, where “good” means “high quality.”

That would be great news, because writing good HTML is actually [more important](https://meiert.com/en/blog/rules-for-html/) than writing good CSS or good JavaScript. At least from the view of [the first paradigm of web development](https://meiert.com/en/blog/two-paradigms/), which sees a benefit in separating concerns, and assumes, as the end goal, a large code base of many HTML templates and files with very few style sheets and scripts.

Alas, then, the problem is not that there’s also a new paradigm, in which components feature HTML and CSS and JavaScript (or ECMAScript, if we want to adjust terminology), but that _not_ everyone writes good HTML. And that has many reasons, of course.

The most important one, a very good reason, is that HTML isn’t actually that easy, because it really is complex. Want an example?

HTML&nbsp;5.2, which is the latest HTML recommendation over at the W3C (as opposed to the WHATWG, where HTML really is written—so normally, look at [that spec](https://html.spec.whatwg.org/multipage/)), contains [111 elements](https://meiert.com/en/indices/html-elements/) alone. _111._ How many do you know? How many does the average web developer know? Or the median web developer? And what does that mean for their HTML if they don’t even know all the elements?

Want another example? When people talk about HTML elements like, for example, `<html>` or `<a>` or `<p>`, then [most of the time they do mean _elements_](https://www.456bereastreet.com/archive/200508/html_tags_vs_elements_vs_attributes/). But what they then _talk about_ is “tags.” Google, as of September, 2019, finds 25 million occurrences of [“html tags”](https://www.google.com/search?q="html+tags") alone. HTML elements, what people mean, but don’t call by name? [2.4 million hits](https://www.google.com/search?q="html+elements"), a tenth. So this one begs the question how well developers understand HTML if they’re not sure about the difference between elements and tags.

Another one? In a few years, HTML will celebrate its 30th birthday. Very cool! So we will certainly have maxed out all options to [reduce HTML payload](https://meiert.com/en/blog/html-performance/), to improve performance? Well, no. One of the major options at our disposal to reduce HTML payload is not to write HTML that can be left out without a document turning invalid ([please validate](https://meiert.com/en/blog/about-validation/), by the way). But almost no one uses that option. Web developers have concerns, yes, but the point is that the method is so under-utilized, we cannot speak of HTML mastery here, either.

We could go on, adding data and anecdotes to how HTML is both important and yet not well-understood, nor well-used. But the route I want to take now is to take 10 examples, from the wild, to show simple improvements to respective HTML code. That code, then, has been anonymized, for this book is not about pointing fingers, but to simply look at HTML and see what else we can do, how we can improve it, how we can: upgrade it.

Thanks for obtaining your own copy of this little book, and now welcome to this first and light and playful edition of _Upgrade Your HTML_.

—Jens Oliver Meiert (short: Jens).

PS.
And, oh, the book really is about [HTML](https://html.spec.whatwg.org/multipage/). Not SGML, not XHTML, not XML, just HTML.

PPS.
And, of course, it’s opinionated.