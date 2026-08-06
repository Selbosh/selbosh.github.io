---
title: How not to write like an LLM
date: '2026-08-03T12:00:00+02:00'
draft: true
---

I reckon I have a fairly good command of the English language.
As an academic, my job involves reviewing writing of others, both native and non-native English speakers.
This means I am quite sensitive to bad writing---which is not to say that I claim to be a good writer, but I think I know bad writing when I see it.

The last couple of years has seen AI-generated text enroaching into online life: on social media, in emails, in reviews and even in academia.
This has a deleterious effect on our day-to-day experience, because sooner or later one of us has to read this stuff, whether we realise it or not.

## The problem with AI writing

Stilted writing is not a new phenomenon.
Bad literature, business jargon, clichés and PR-speak litter the Web.
And because large language models (LLMs) are trained what is available---not what is _good_---they reflect our worst habits.
Engaging and effective writing is not generic.
But generic writing is all LLMs can offer, because they are built to reproduce statistically likely patterns.
(This is why [AI images all look the same](https://www.science.org/content/article/when-creating-images-ai-keeps-remixing-same-12-stock-photo-cliches).)

The goal of this guide is to help your recognize signs of AI writing.
This isn't about shaming people who use ChatGPT, or about learning to pass off machine-generated text as human.
Rather, as generative AI pollutes the Internet with bland writing, we don't want to pick up any bad habits.

'Bad' writing is, of course, subjective, so this guide is opinionated.
This post was inspired by the Wikipedia guide on [Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing).

## How to sound like a language model

I am not talking about spelling or grammar errors.
LLMs are less likely to make these; presence of such mistakes can be a sign that the AI was _not_ used.[^1]
Bad writing can be grammatically correct, but unpleasant to read.

LLMs are trained on text stolen from the Internet, which means they exhibit particular patterns based on common (mis)use of phrases and online formats.
Instead of typos, we get [loquacity](https://dictionary.cambridge.org/dictionary/english/loquacious), [grandiloquence](https://dictionary.cambridge.org/dictionary/english/grandiloquence) and [sesquipedalian](https://dictionary.cambridge.org/dictionary/english/sesquipedalian) language---using impressive-sounding words in an attempt to sound clever.

[^1]: Except really common mistakes like 'invite' as a noun, or 'barbeque' as a misspelling of 'barbecue'.

According to an LLM, everything is a 'fundamental paradigm shift'.
This is a symptom of learning from marketing copy, hagiography, press releases and newspaper column inches.
Everything is important---even when it isn't, it must surely be a harbinger of some key moment or else a part of a significant trend.

In academic text, this manifests in grandiloquent language like 'critical', 'essential', 'crucial', 'vital' and 'paradigm shift', even though on a normal day nobody knows what a 'paradigm' is or why it can only 'shift'.

![Aren't these just buzzwords that dumb people use to sound important?](https://media1.tenor.com/m/7F-mvUGCuTcAAAAd/arent-these-just-buzz-words-that-dumb-people-use-to-sound-important-proactive.gif)

Samuel Johnson put it best:

> Read over your compositions, and wherever you meet with a passage which you think is particularly fine, strike it out.

One of the more famous AI tropes is: **'It's not _X_, it's _Y_!'**
Years ago we used to mock Kickstarter campaigns for phrasing like this: 'It's not just a toothbrush, it's your friend!'
But this contrastive framing is back with a vengeance and is one of the more famous tells of AI-generated copy.
It might sound like a clever rhetorical device, a balanced presentation of competing viewpoints or an interesting paradox, but more likely it's just an unnecessarily longwinded way of writing 'and' to describe two non-conflicting characteristics of a subject. 'It's not just a blog post, it's online!'

A variation on this is **'While _X_, also _Y_'**; ostensibly for weighing up pros and cons, but in practice one of the points is just ballast. 
Some examples from the last peer review cycle:
> While grounded in cognitive science, our novelty lies in adapting...

This is like going to a job interview and saying your weaknesses are: 'While a perfectionist, I am modest' instead of something memorable like: 'While an inveterate liar, I am also a compulsive thief'.

> While informative, this strategy [citation] has clear limitations...

Writing that a cited work is 'informative' is akin to writing 'I enjoyed the experiment' to pad out the evaluation section in your school science report.
But today's machine learning models have even more advanced ways of filling the page.
If you want to add some redundant and superficial analysis to an existing sentence, add a comma and a **present participle ('-ing')** and you can have a vague discussion about anything... _underscoring the utility of LLMs in padding your word count_. For example:

> [citation], slowly contributing to a growing body of deep learning methods...

> Overall, success depended on [x], [y], and [z], highlighting the need for cross-domain evaluation.

Pursuit of comprehensive answers yields sentences that are trying to do too many things at once. This makes it harder to separate out the introduction, background, methodology, results and conclusion sections of a technical report, except with (over)-use of headers.

Why state something when you can say it _explicitly_? Why use an API when you can access it _directly_? Why say 2 is less than 3 when you can say it _strictly_?
If you can remove a ~~word or~~ phrase from your sentence and it means ~~exactly~~ the same thing, then it was ~~just~~ filler.
A special case is when the sentence sits on the fence to avoid an absolute statement about something that is uncontroversial: 'often', 'largely', 'generally'; or 'notoriously' (never cited, of course).

My favourites are the phrases that cannot make sense in any context, of which here are a few examples from real submissions:

- the study primarily focused...
- explicitly align
- distinct boundary
- robust proof-of-concept
- crucial robustness function
- deliberately restricted
- consistently lacks
- critical bottlenecks
- clear consensus
- often scarce
- often inherently miscalibrated
- often yield inconsistent results
- often measure performance primarily
- ...strategies prove largely ineffective, ... often reducing performance

Mark Twain said:

> As to the adjective: when in doubt, strike it out.

#### Inelegant variation

Before LLMs, a pet peeve of mine was how every new Web development framework was promoted with language like 'feature-rich' or 'rich user experience', without ever explaining what this means in normal language.
At least this usage seemed to be standard among people within the field, who presumably knew what it meant even if I did not.

Elegant variation is the use of synonyms to avoid repeating the same word twice. [Inelegant variation](https://www.secondmentions.com/) is when journalists arrive at unusual phrases after they take this a bit too far.
Generative language models, automatically generate [tortured phrases](https://arxiv.org/abs/2107.06751) to evade detection of plagiarism and repetition.

Do not blindly draw from your thesaurus. Also, technical writing is not journalism; it is OK to repeat a key word now and then to be precise.

Rumours of LLM reasoning are greatly exaggerated.
Nothing is ever implied. A structured report can only mean lots of subheadings and no enumeration of points is complete without at least one bulleted list.

### Mistakes people and LLMs make (but you shouldn't)

#### Definitions and abbreviations

In technical writing, you should define an unfamiliar term when it is introduced, so the reader knows what you are talking about.
This is especially important for abbreviations and initialisms that you plan to use later in the text without writing out in full every time.

If the writer (human or otherwise) does not really understand the purpose of doing this, or does not have access to the rest of the text, then we find abbreviations and definitions being introduced but never actually used in the text, or being reintroduced repeatedly.

> The advent of Foundation Models has revolutionized the landscape of artificial intelligence. These models demonstrate remarkable capabilities in generalization and transfer learning across Computer Vision (CV) and Natural Language Processing (NLP).

Another common problem is a misunderstanding of how initialisms work.
Yes, we write 'LLM' with capital letters when abbreviated, but it is not a proper noun, so we write 'large language model', not 'Large Language Model'.
It is not a trademark! It is not a country!


### Things that annoy me personally

I have a few pet peeves that possibly do not bother anybody else but I'd like to mention them here so that they can annoy you, too.

#### Punctuation

I am probably the only person I know who cares about the difference between a hyphen (-), an en-dash (--), an em-dash (---) and a minus (&minus;).

_Normal_ people have not memorised the sequence Alt-0151, nor the HTML code `&mdash;` nor the Markdown syntax `---`.
As a reader of [Butterwick's _Practical Typography_](https://practicaltypography.com/hyphens-and-dashes.html) and owner of books about typography---despite not working in design or publishing---I am not a normal person.

Therefore, a sudden (over)usage of correctly-typeset em-dashes is inherently suspicious.
It's only OK when I do it.

#### Oxford commas

The Oxford (or Harvard) comma is a redundant comma added before the 'and' in a list of three or more items, for example 'apples, oranges, and bananas'.
This unnecessary punctuation is sometimes defended by writers who use it as a crutch for a poorly structured sentence, instead of rewriting it.
US English style guides recommend its use more often than British English ones.
LLMs' over-use of the rhetorical [rule of three](https://en.wikipedia.org/wiki/Rule_of_three_(writing)) means the Oxford comma crops up fairly often, as a result.

More redundant commas appear after the Latin abbreviations 'i.e.' and 'e.g.' as if the meaning would be lost without having a comma there. Real people do this and I don't like it.

#### Definition lists

Hardly any web developer appears to be aware of HTML description lists, `<dl>`, or the $\LaTeX\$ equivalent, `\begin{description}` lists, because they do not translate well between formats or plain text in the way that simple bullet points or numbered lists do, and are not supported by common blog templates or discussion boards. This means that LLMs have no idea either.

But for one reason or another they feel compelled to add redundant structure.
The manifestation of this is in bullet point lists with titles in front of each item, separated by a comma.

- Number One: more text
- Number Two: more text
- Number Three: more text

If anybody really wanted to write like this, they would use a definition list, also known as a description list, via the lesser-known HTML tag `<dl></dl>`, $\LaTeX\$ `description` environment or the Markdown syntax
```markdown
Term
: Description or Definition
```

But they don't, because most people haven't heard of these, and they do not translate unambiguously to Markdown syntax.

This blog supports description lists because I wrote the CSS for them specifically. Many other sites will not.

Number One
: more text

Number Two
: more text

Number Three
: more text

#### Mathematical operators

Many users of $\LaTeX\$ never learn how to typeset `\text{}` or names of mathematical operators properly.
Thus they do not recognize the difference between $sin(x)$ and $\sin(x)$ or between $F_{before}$ and $F_\text{before}$ and this badly rendered syntax appears in many published papers.
As a result LLMs now make this mistake by default.

## Recommendations

