# 100 Days Of Code - Log

We are all beginners at something.

## Day 000: THU APR 5 2018

### Todays Progress

- Observed #100DaysOfCode on Twitter
- Browsed around 100daysofcode.com and blog posts
- Forked repository to give it a go
- Started this log, recorded plan for some learning goals / projects
- Browsed around forks at some others that went through this effort

### Thoughts

The curse of knowledge makes it easy to forget how difficult it was when
starting the journey to learn a new skill, technology, etc.  I'm perhaps
co-opting this idea to commit 1hr/day to learning something new but document
the process as well.  It might be a handy reference / usability study as I
stumble upon non-optimal resources in my search to learn a new technology.

This process is not that dissimilar from personal notes I've taken on projects
but those I typically keep private.  Curious to see what benefits may come by
publishing in public what my first ~24 hours are with various technologies.  My
expectation of a benefit is that others may chime in with suggestions of what
may be a better path for learning.

Assorted thoughts:
- 100 sounds epic but I'm ok with just 24 days as an outcome
- 1 hr sounds accessible but I'm guessing self-report bias will be +/- 1hr
- May be contrary to habit-formation theory, but I code more than an hour a day
  already, this is about coding for a side project with technologies I
  don't already know
- Anticipate spend of 2x time studying / researching before coding anything
- Live coding has interesting potential for community feedback on process,
  possibility of teaching others when working with something already familiar
- Consideration over how much code to make public if some projects have
  potential to be a future endeavor

### Links

- https://medium.freecodecamp.org/join-the-100daysofcode-556ddb4579e4
- http://100daysofcode.com/

## Day 001: SUN APR 8 2018

### Todays Progress

- Decided to use golang for first project
- Search for golang learning resources
- Installed golang
- Wrote hello world and explored go tools

### Thoughts

Chose first learning project to be golang.  Why?  Honestly, others seem to like
it and I haven't tried it out yet.  I'm not sure it's well suited for the
problem I want to solve but let's not dwell.

Googled "golang" - browsed first page of results
- [x] golang.org
- [x] wikipedia
- [x] blog post: Keval Patel
- [x] blog post: Sagi Nadir
- [x] github org
- [x] intro video from sentdex
- [x] twitter handle
- [x] blog post: hacker noon
- [x] free code camp

**golang.org**

First thing I see -- I like the "Try Go" area.  While Hello, World is fun,
appreciate that there are a variety of short programs to see some quick code
samples of what the language looks like in practice.  Spent 5 minutes playing
with it.  Interesting that even the Hello World has complexity assuming a
knowledge of reader about character encoding and i18n issues.

There is a video, but it's 34min.  It's on front page though so must be a good
place to start. Very quickly talk gives tour of 3 essential pices: Interfaces,
Reflection, Concurrency.  This tells me the content is not really geared toward
somebody who is just learning to program for the first time.  That's fine for
me as I want to see what's different and why I should use it, but a novice may
be quickly lost.

Made it about 5m into video and stopped as I don't think it's what I'm looking
for yet.

Looking at what else is on page -- "Download Go" is important since I don't
have it installed yet.  Featured articles looks like blog of more recent
issues, developments for experienced gophers.

Looking at headers -- Documents, Packages, The Project, Help, Blog.  Went into
Documents (aka Documentation) where I can see some of what I probably need to
get going: Getting Started / Installing and Learning Go / Tour.

That was my first 20 minutes, but curious about some more historical context so
heading over to wikipedia.

**Wikipedia**

Again see that concurrent programming is an emphasized feature that
differentiates Go.  The whole article is generally pretty useful as it focuses
on what differentiates and motivated the development of the language.

Any general purpose programming language will solve most of the day-to-day
needs, so was curious to learn more on the applicability of "Use Go for
this..." rather than theoretical / computer science perspectives.

I think the list of projects using go demonstrates this to a certain extent:
Docker, Kubernetes, Terraform, Cloud Foundry.

**Why should you learn go?**

It is tempting to play the grammar police, but if you can get past that the
16+k claps and high google page rank is because of the justification presented
to make a case for trends toward concurrent development and why Golang is
positioned to handle those problems.

**Why I Love Golang**

Self described "I write this on a tangent".  Not sure I got much from this
post, though made a few interesting counter-arguments:

- "The bottom line is, it leads to code which is easier to reason with because
  it's less abstract" because of omitted features like classes, operator
  overloading, function overloading, optional parameters, exceptions.
- "I have left the concurrency talk by intention to be last.  Why?  because I
  don't think it's so important."

**Github / Twitter**

Nothing too unexpected from github repositories and twitter account.

I guess Go versions 1.10.1 / 1.9.5 were recently released.

**Introduction - Go Lang Practical Programming Tutorial p.1**

It's only 7:24 so pretty short, but since this seemed like a random video to
choose I wanted to do a quick background check so to speak on the source.
What I learned by looking at sentdex channel is that the creator is a python
developer responsible for pythonprogramming.net so this feels like it could be
a good introduction to Go for myself.

These videos may be an effective approach for somebody familiar with Python and
trying to transition into Go since he followed a similar path.  There are a
another 23 videos each about 4-10 minutes long and done relatively recently
(Oct 2017) so likely to still be relevant.

**A Space Themed Intro to Golang**

It's a nice idea, take some code and then explain it line by line, but this
approach doesn't seem to be working for me.

**freeCodeCamp**

This is actually the freeCodeCamp stories on Medium tagged with golang.
Nothing particular jumping out at me here that I want to read just yet.

I hadn't tried out freeCodeCamp or signed up before so I did now but now
realize it is javascript / web centric so not helpful for me in this project
just yet.

**Installation**

I went back to golang.org to download and install on osx, which was pretty
straightforward.

https://golang.org/doc/install?download=go1.10.1.darwin-amd64.pkg

Testing the installation is a bit surprising.  The docs hint at importance of
GOPATH though everything works fine as is up until `go install`.

The error message tells me to run `go help gopath` which gives me more context
of the importance of the variable for package / dependency management.

Next time, I'll start with docs for "How to Write Go Code"

### Links

- https://golang.org/doc/
- https://en.wikipedia.org/wiki/Go_(programming_language)#cite_note-107
- https://medium.com/@kevalpatel2106/why-should-you-learn-go-f607681fad65
- https://medium.com/@saginadir/why-i-love-golang-90085898b4f7
- https://github.com/golang
- https://www.youtube.com/watch?v=G3PvTWRIhZA
- https://hackernoon.com/golang-the-highest-paying-technology-to-know-9c6089d7081d
- https://golang.org/doc/code.html

## Day 002: MON APR 9 2018

### Todays Progress

- Started going through some online learning / books / tutorials

### Thoughts

Will be approaching this initiative in two ways primarily:

1. Top-Down deep dive into learning language from tutorials / guides / books /
   videos / etc.
2. Working on projects and just-in-time google, stack, etc. what I need to know
   to make forward progress on a project.

On the top-down front, did some initial searches across paid and free
resources.

**O'Reilly Safari**

Usually this is my go-to resource for deep dive materials.  There are some
learning paths ranging from 1-13 hours.

- Learning Path: Go - Building Cloud Native Go Applications (4h)
- Learning Path: Go - Advancing into Web Development with Go (12h 49m)
- Learning Path: Go - Dynamic Web Development with Go (56m)
- Introduction to Go Programming / John Graham-Cumming (5h 18m)
- ...

There are quite a few books (161) as well.  Here are a few of the more general
sounding in no particular order.

- Sam's Teach Yourself Go in 24 Hours by George Ornbo (Sams)
- Go in Practice by Matt Farina and Matt Butcher (Manning)
- Learning Go Programming by Vladimir Vivien (Packt)
- The Go Programming Language by Alan Donovan and Brian Kernighan (Addison-Wesley)
- Introducing Go by Caleb Doxsey (O'Reilly)
- Go in Action by William Kennedy, Brian Ketelsen, Erik St. Martin (Manning)
- Head First Go by Jay McGavren (O'Reilly)
- ...

**Pluralsight**

Was curious what Pluralsight has available since I have access to it.  There
does not appear to be a learning path, but there are 18 courses.

- Code School: On Track wiht Golang (1h 15m)
- Creating Web Applications with Go (4h 47m)
- The Go Programming Language (4h 35m)
- Go: Getting Started (1h 51m)
- Go Fundamentals (3h 36m)
- Building Distributed Applications with Go (3h 17m)
- Concurrent Programming with Go (2h 36m)
- ...

**Official Resources**

- The Go Tour
- Effective Go

**MOOCs**

Looked for Coursera, edX, Udacity, and Udemy resources as well -- though some
in the community seem to suggest just sticking with The Go Tour.

**Curated Lists**

Before commiting time to any of those, also wanted to look around at some other
learning materials around the web others would recommend.

I figured there would be an awesome-go list, and since these lists remind me of
Yahoo circa 1996 I decided to take a look at these options.

The github.com/golang/go/wiki also has a list of resources for getting started
and learning specific topics.

There are also some ranked tutorials from hackr.io/tutorials/learn-golang
that could be worth reviewing since they are voted on by community..

Also stumbled upon reactdom.com go-books listing which included a few
additional online tutorials.

I think I've reached the point of diminishing returns in seeking the best
companion resource at this point.  Mark McGranaghan's gobyexample.com seems
highly rated and is a good cookbook like approach to complement official tour.

**Google it**

Ultimately, for today's task all I needed was a sample of how to fetch data
from an API endpoint by making a REST request.  Thankfully, Nic Raboy had
posted a blog post with some sample code for doing that very thing.

Task accomplished.

### Links

- https://awesome-go.com/
- https://github.com/golang/go/wiki
- https://hackr.io/tutorials/learn-golang
- https://reactdom.com/blog/go-books
- https://golang.org/doc/code.html
- https://gobyexample.com/
- https://www.thepolyglotdeveloper.com/2017/07/consume-restful-api-endpoints-golang-application/

## Day 003: TUE APR 10 2018

### Todays Progress

- Chose to review Sam's Teach Yourself Go in 24 Hours by George Ornbo (Sams)

### Thoughts

Mostly study and experimentation today, no major insights.

### Links







---

## Day 000: DAY APR d 2018

- https://github.com/j12y/check-last-commit

### Todays Progress

### Thoughts

### Links

