{sample: true}
# Intro

HTML is the backbone of the Web. We can build a website without JavaScript, even without CSS, but without HTML—_any_ HTML—, no, we can’t.

HTML is so important, yet so easy. Everyone writes HTML, and everyone says they can write HTML. They don’t just mean they’re able to write HTML, but that they write _good_ HTML, where “good” means “high quality.”

That would be great news, because writing good HTML is [more important](https://meiert.com/blog/rules-for-html/) than writing good CSS or good JavaScript. This is at least the view of [the first paradigm of web development](https://meiert.com/blog/two-paradigms/). This paradigm sees a benefit in separating concerns, and assumes, as the end goal, a large code base of many HTML templates and files with few style sheets and scripts.

The problem is not that there’s also a new paradigm, in which components may include HTML and CSS and JavaScript (or ECMAScript, if we want to adjust terminology). It’s that _not_ everyone writes good HTML. There are many reasons for that.

The most important one is that HTML isn’t actually that easy, because it really is complex. Want an example?

HTML 5.2, which is the last HTML recommendation by the W3C (HTML is maintained [by the WHATWG](https://spec.whatwg.org/)), contains [111 elements](https://meiert.com/indices/html-elements/) alone. _111._ How many do you know? How many does the average web developer know? What does it mean for their markup if they don’t know all the elements?

Want another example? When people talk about HTML elements like `html` or `a` or `p`, then [most of the time they do mean _elements_](https://www.456bereastreet.com/archive/200508/html_tags_vs_elements_vs_attributes/). But what they then _talk about_ is “tags.” Google, as of September, 2019, finds 25 million occurrences of [“html tags”](https://www.google.com/search?q="html+tags") alone. HTML elements, what people mean, but don’t call by name? [2.4 million hits](https://www.google.com/search?q="html+elements"), a tenth. This begs the question how well developers understand HTML if they can’t tell the difference between elements and tags.

Another one? In a few years, HTML will celebrate its 30th birthday. Very cool! We will certainly have maxed out all options to [reduce HTML payload](https://meiert.com/blog/html-performance/) to improve performance, wouldn’t we? Well, no. One of the major options at our disposal to reduce HTML payload is not to write HTML that can be left out without a document turning invalid ([please validate](https://meiert.com/blog/about-validation/), by the way). Unfortunately, almost no one uses that option. Web developers have their concerns and habits, yes. The point is that the method is so under-utilized, we cannot speak of HTML mastery here, either.

We could go on, adding data and anecdotes to how HTML is both important and yet not well-understood, nor well-used. The route I want to take is to select 10 examples, from the wild, to make improvements to the respective HTML code. That code has been anonymized, for this booklet is not about pointing fingers. It’s to look at HTML and note what else we can do, how we can improve it, how we can: upgrade it.

Welcome to this first and light and playful edition of _Upgrade Your HTML_.

—Jens Oliver Meiert (short: Jens)

PS.
The booklet really is about [HTML](https://html.spec.whatwg.org/multipage/). Not SGML, not XHTML, not XML, just HTML.