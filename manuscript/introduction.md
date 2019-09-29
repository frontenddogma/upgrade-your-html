# Introduction

HTML is the backbone of the Web. Or one of the backbones of the Web. Or the backbone, again, for us as web developers, because we could build a website without JavaScript, even without CSS, but without HTML, _any_ HTML, no, we couldn’t.

As HTML is so important and yet also so easy everyone writes HTML, and everyone says they can write HTML. And with that they don’t just mean they are able to write HTML, but that they write _good_ HTML, where “good” means “high quality.”

That would be great news, because writing good HTML is actually [more important](https://meiert.com/en/blog/rules-for-html/) than writing good CSS or good JavaScript. At least from the view of [the first paradigm of web development](https://meiert.com/en/blog/two-paradigms/), which sees a benefit in separating concerns, and in managing a large code base of many HTML templates and files with very few style sheets and scripts.

Alas, then, the problem is not that there’s also a new paradigm, in which components feature HTML and CSS and JavaScript (or ECMAScript, if we want to adjust terminology), but that _not_ everyone writes good HTML. And that has many reasons, of course.

The most important one, and one of the most constructive reasons at the same time, is that HTML isn’t actually that easy, because it really is a bit complex. Want an example?

HTML&nbsp;5.2, which is the latest HTML recommendation over at the W3C (as opposed to the WHATWG, where HTML really is written—so rather look at [their spec](https://html.spec.whatwg.org/multipage/)!), contains [111 elements](https://meiert.com/en/indices/html-elements/) alone. _111._ How many do you know? How many does the average web developer know? Or the median web developer? And what does that mean for their HTML if they don’t even know all the elements?

Want another example? (Okay, it’s a bit unscientific.) When people talk about HTML elements like, for example, `<html>` or `<a>` or `<p>`, then [they usually mean _elements_](https://www.456bereastreet.com/archive/200508/html_tags_vs_elements_vs_attributes/). But what they then talk about is “tags.” Google, as of September, 2019, finds 25 million occurrences of [“html tags”](https://www.google.com/search?q="html+tags") alone. HTML elements, what people mean, but don’t call by name? [2.4 million hits.](https://www.google.com/search?q="html+elements")

Another one? In a few years, HTML will celebrate its 30th birthday. Very cool! So we will certainly have maxed out all options to reduce HTML payload, to improve performance, no? Well, no. One of the major options at our disposal to reduce HTML payload is not to write that HTML that can be left out without a document turning invalid (please validate, by the way). But almost no one uses that option. Web developers have concerns, yes, but the point here is that the method is so under-utilized, we cannot speak of HTML mastery here, either.

We could go on, adding data and anecdotes to how HTML is both important and yet not well-understand, nor well-used. But the route I want to take now is to take 10 examples, from the wild, to show simple improvements to respective HTML code. That code, then, will often be anonymized—it’s not about pointing fingers, but to simply look at HTML and see what else we can do, how we can improve it, how we can: upgrade it.

Thanks for obtaining your own copy of this little book, and now welcome to this first edition of _Upgrade Your HTML_.

—Jens Oliver Meiert (short: Jens).