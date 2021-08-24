---
title: Footnotes in web content
subtitle: "Will we ever be able to do it right?"
date: 2021-08-24
---

## Introduction

I've always found myself running off on tangents whenever I'm reading or even recalling things.
It happens to me multiple times within even a single sentence.^[Could [Racing thoughts][Racing Thoughts - Wikipedia] be tangentially related?]
Of course, I'd love for a person reading this to be able to know what's running through my mind,
whether it be an amusing anecdote or a bit of context that makes the paragraph easier to understand.

Books are nice in this regard.
Whenever the author has something tangential they want to include, they can just add a note at the bottom of the page.
Since books are nice and compact and contain a reasonable number of words per page, the typesetting allows for ancillary comments not too far away from the text.
Of course, being a more serious medium compared to the web, inline comments of a jocular nature are naturally far less frequent than, say, a long rant about footnotes.
An example from The New Annotated Sherlock Holmes Vol. 1 should suffice to demonstrate the idea:

Web content, however, presents unique challenges.
For one, the web is primarily displayed using markup and styling instead of precise typesetting like in LaTeX.^[As much as we may want to use \LaTeX for our fancy typesetting needs.]
This already presents the unique design challenge of using two different tools for a single output.^[However, they do make sense in terms of their function. Perhaps we shall explore this some other time.<!--- #website\htmlcss -->]
We also have a variety of screen formats to contend with, not to mention the variations in font rendering and browser support.
Certainly a complex mess to deal with as a writer.^[I'm not there yet, I know.]
One would think that 30 years^[Or more depending on where you start counting from.] from the birth of hypertext that there would be standards in place for footnotes but we are found wanting.
We must thus rely on our own ingenuity.

This is by no means a novel problem.
Several have paved the way before me — I take inspiration from Dave Liepmann's [_Tufte CSS_][Tufte CSS] as well as Bradley Taunt's [_ET-Jekyll_][ET-Jekyll].
Jake Zimmerman's [_Tufte Pandoc CSS_][Tufte Pandoc CSS] does quite a bit of heavy lifting as well.
Of course, Liepmann's implementation is inspired by Edward Tufte's handout styling; he acknowledges it early on in the post.^[Tufte seems to be rather influential. I should take a deeper look.]<!--- #website/tufte -->
Tufte CSS is also mentioned very early on in Gwern's [analysis of sidenote designs on the web][Gwern - Sidenotes In Web Design].^[It inspired me to write this!] 

Gwern takes a very thorough look at several implementations he dug up and very rightly concludes that Tufte CSS would suffice for most writers on the web.
He does mention of a pure HTML+CSS solution by Said but I failed to come across it.^[If you know, [tell me](Contact Me.md)!]
