# Phase 3 guide

## Welcome to Phase 3

Welcome from your teachers.  Phase 3 is the most exciting phase here at DBC.
In this phase we no longer view you as students or developers-in-training,
rather we look at you to be valuable, albeit junior, collaborators in the craft
of software development.  This will define how we interact and how we assign
and tackle challenges.  Similarly, and you should no longer think of yourselves
as "classmates" but rather "teammates" or "coworkers."

## TL;DR

You should read it all, but...

* We're going to treat you like developers.  This means:
  * Github based code review
  * Pointed criticism
  * Teachers won't ask "do you need help."  You're going to have to ask for it
  * Don't be late
  * Remember IKE
  * Don't be lazy
* We want to give you real-world, project-based challenges
* Use Rails, but don't become a "Rails developer:" become a great developer and
  the tech won't matter
* Think critically
  * Don't trust all you read or hear about fads and fashions in tech
  * When asking for help form a Good Question
  * When asked for help ensure you're being asked a Good Question.  Be Kind,
    but guard your time
* Be polite
  * Realize if you start talking at someone you might break their train of
  * thought
  * Observe the headphone rule - this applies to staff and peers alike
* Read the rest of this but uses these points as a cultural guide. You may need
  to revisit this document multiple times

## Daily Schedule

- Lectures
  - We will lecture around 10:00 and 2:00 daily
  - ...but we will ocassionally have surprise break-outs
  - ...and we may occasionally drop lectures if we think we'll be interrupting
    your flow

## Challenges

Challenges will be bigger and more vague. A lot of the problem will be
strategizing how to approach the problem: like debugging or researching a
problem.  The emphasis of challenges is on the process of problem solving, not
the solution.  _We expect that you can complete any challenge at this point.
HOW you complete it is at stake_.  Code quality is #1.

## Rails

Rails is a powerful tool.  While you've had to write and re-write the same
boilerplate code dozens of times in Sinatra skeleton, Rails will make it
**much** easier to get up and running and take the boilerplate away.

That said, Rails can become _too_ "zealous" in its code generation.  While we
bless your *exploration* of the powers of `rails generate` **do not use it** in
these challenges.  The ability to write Rails code (models, controllers, and
views) from a blank editor screen is a skill you **must** develop.  An
interviewer will be none-too-impressed if your ability to write a controller is
hamstrung by access to the Rails generators.

**EXCEPTIONS**:  You may feel free to `rails generate migration`.  Why?  Because
figuring out time-stamps is irritating.  Also if you install a gem (for
instance `rspec-rails` which finalized its install by running a `rails
generate` command, feel free).

## Feedback

Don't be attached to your code, our job is to be critical and opinionated :)
Occasionally a criticism will be reducible to a question of style.  Both of us
are professional Rails developers.  We may occasionally give you guidance that
is justified by "that's not idiomatic Rails."  That's "taste" and while we hope
you have aquired some sense of it in the previous phases, we will try to help
you further refine it during our time together.


### On Taste

![quote by Ira Glass on beginners](ira-glass-quote.jpg)

-- Ira Glass

### On Feedback Style

In Phase 3, part of our goal is to debug your thought process.  If you say you
are weak, we will give you exercises.  If you give us a bad process, we will ask
you to find your own weakness.  If you criticise the challenges we give you, we
will make you fix them.  If you complain that something "doesn't work" we will
ask you to explain what you've done to understand the problem.

In short, we're going to ask you to be completely **responsible**.  Lamentably
this expectation seems to have gone out of fashion these days, but that is not
the case here.

## De Sententiis (On Opinions)

When someone gives you an observation, it is your obligation to hold them
accountable to that opinion.  When a coach comes along and says "ERB sucks,
HAML is the bomb" it is your **job** to ask that individiual:  "Wombat Salar,
why do you say this?  What problem does this solve?  What companies are using
this?  Who are the main contributors on this?  What's their philosophy?  What's
the point of view behind this thing?"

While it's important to leave your mind open for input, it's also important to
know when you need *not* heed some advice.  As Kipling says in "If:"

    If you can trust yourself when all men doubt you,
        But make allowance for their doubting too;...
    Yours is the Earth and everything that’s in it

## Review

We will do our best to pair with all of you several times throughout the phase.
We will be conducting code reviews for specific challenges. Some of these will
happen on github's pull requests and others will happen live, face to face.

## Questions

We are here to help.  Everyone who teaches at DBC has made a decision to use
their development talents and passion to help fuel that selfsame passion in
others.  We want you to ask _yourself_ first, _your pair_ second, _your peer_
third and a teacher _last_.

When engaging with any of these parties, most especially the first party, it is
absolutely paramount that you ask the question properly.  80% of the time a
question that would be asked of another or of a forum could be avoided entirely
if the asker had taken the time to formulate the question clearly with
expectations and proof.  Your teacher demands that you ask me focused,
targeted questions that indicate the strength and character of your mental
model.

An invaluable guide on asking questions can be found here:
[Asking Smart Questions by Eric Raymond](http://www.catb.org/esr/faqs/smart-questions.html)

To be clear "asking a question" is not the same as "telling a story."  Telling
a story tells us what the user story or feature was that you're implementing.
Saying that the story's goal doesn't work is not a question.  It says you're
_en route_ to asking a question but you've not isolated the essential tripping
point that's preventing your story from having a happy ending.  Story-telling
is a great first step, but it is not the step where you should reach out for
help.

When you ask a question look for seams between "what I have here it what I
expect" and "what I get back is not what I expect".  That tunnel that takes the
"what you expect" and turns it into "what you didn't expect" is where your bug
is.  If your that tunnel, i.e. your code, is small and focused, your bug should
pop out.  If it is a snarl of spaghetti, it will be difficult to figure out.
We call this process "debugging."

Have log files, unit tests, etc. handy when you engage these peers and we will
be able to focus, solve, and move on.  If anyone asks for help but doesn't show
you the respect of formulating a question, you should feel proud in asking them
to formulate a clearer question for you.  All our time is precious and we
must all show each other due respect.

## Conclusion

- Don't be attached to your code, my job is to be critical and opinionated :)
- Teachers will do their best to pair with all of you several times throughout the phase.
- Teachers will be conducting code reviews for specific challenges. Some of these will happen on GitHub's pull requests and others will happen live, face to face.
- This is a no-shame ask-anything environment.
- All our challenge solutions/repos should be under phase organization.
- Make sure you check out [Phase 3 Git Workflow](../../../phase-3-guide/blob/master/git-workflow.md#phase-3-github-workflow)
- Don't burn out, take care of each other.

### Student Handbook

The [student handbook](../../..student-handbook) has information about DBC's agreements, policies, and rules. Please review it.
