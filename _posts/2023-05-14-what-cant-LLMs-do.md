---
title: "All jobs require exactly 2 functions; LLMs can perform only 1 of them"
date: 2023-05-14
---

![robot thinking](/assets/images/robot-philosophy.jpg)
<p>Math and Philosophy. That’s it. That’s what every productive skill boils down to at the end: some mixture of math and philosophy.</p>
<p>LLMs are extremely impressive at what they do, and what they do is to mimic a lot of the math part of these things. It’s so good in fact that when it takes the math aspect of a certain task and knocks it out the park, people start to think it can handle the philosophy as well. But that’s just not the case.</p>
<p>LLMs will automate a lot of our work, that is for sure. I will not talk about to what precise extent that will happen, or what effect it will have on your livelihood, because that’s an economics question and I'm not an economist. Don’t worry though, you can go online and find a lot of non-economists commenting on subjects they aren’t qualified to advise people on.</p>
<p>What I am certain LLMs will not automate are the philosophical aspects of these tasks. That, I think, is a hard limit.</p>
<h1>Just math and philosophy? That sounds too simple</h1>
<p>Give me a minute while I raise the defense that’s standard issue to every AI researcher when they start the job. </p>
<p>“All models are wrong; but some are useful” - George E. P. Box</p>
<p>Bless that man, his quote’s gotten me out of sticky situations at work. </p>
<p>Obviously, that is a model of how human knowledge can be organized. I don’t think it’s perfectly correct, but we don’t need models to be perfectly correct, we need them to make us just a bit better at understanding what we can see, and predicting what we can’t. By that yardstick, splitting things into these two fields of thought makes organizing the functions we perform for “work” a bit easier</p>
<p>Consider how people manage their personal finances. They may not have studied how interest exactly works and how to calculate it, but they know that it sucks to not have money; and so if someone takes money from them and gives it back later, it wasn’t good that they didn't have their money to spend in the meantime. So if they are going to loan out a large amount of money to someone in the future, it’ll make sense to them that they get a bit more money back. Because it’ll suck while they dont have their money, and they need to be compensated. That’s Math.</p>
<p>But then consider if they would demand interest payments if a friend borrowed some cash for lunch because they forgot their wallet. Of course not, that’s kinda messed up. People need to be able to trust each other, especially those they share a relationship or bond with. It’s the right thing to do. That’s Philosophy.</p>
<p>Everything we do that’s productive can be seen through this lens and it makes sense. These fields or tasks can be described as some mixture of subjects that fall under the umbrellas of math or philosophy; subjects that can be boiled down to either math or philosophy.</p>
<p>I came to this idea years ago in college when I was <s>studying for midterms</s> <s>procrastinating</s> enriching my mind and saw this <a href="https://xkcd.com/435/"><u>XKCD comic</u></a>:</p>
![xkcd comic showing how the natural sciences boil down to math](/assets/images/xkcd-knowledge-purity.png)
<h1>Are you sure? chatGPT seems to handle philosophy pretty well</h1>
<p>That’s where the mixture part comes in. </p>
<p>When generating natural language, LLMs only handle the math part, but they do it very very well. They absolutely do not perform any philosophical aspect of any task, because LLMs are just very sophisticated calculators.</p>
<p>If you don’t know how causal language models are trained, then a layman’s explanation is this: </p>
<p>LLMs work by putting all the words it reads on a grid like the x,y grid used in algebra. Then, when it needs to figure out what the next word in a sentence or paragraph should be, it just chooses the word that’s closest to the other words it just read. The exact position of the words on the grid is decided beforehand by trial and error, where it “trains” in a situation where it takes a word, and tries to put it on the grid in a position where it would be the closest to as many as possible of the words that it would be the next word for.</p>
<p>That’s it. That’s the core of what LLMs do. Everything else we see is built on top of it and can’t exceed its capabilities. It can do a lot of math from this foundation but it certainly can’t reason about philosophical questions the way people do.</p>
<p>Now, it may look like it “knows” a lot about the world and can “think” but that’s because memorizing which words generally appear close to each other mimics thought processes pretty well; because natural language is nothing but a vehicle for expressing thought and knowledge.</p>
<p>What gets confusing is when it solves the mathematical problem of predicting the next word so well that we assume it must be answering so well because it must know things the way we do. But that's just because this is the first thing that can even pretend to talk like us. We have no experience in discriminating between actual philosophical reasoning and mimicry</p>
<p>Let me be clear, I am not denying how powerful and impactful LLMs obviously will be. It is very impressive that ML researchers were able to design a way to perfectly model natural language and that will be a major milestone in the ongoing information revolution, like the steam engine was in the industrial revolution. But steam engines can’t think, and LLMs can’t do philosophy.</p>
<h1>Any proof?</h1>
<p>I’m not a philosopher so I don’t know how I could prove it exhaustively, but I can offer some empirical proof. Both of the following were done on the GPT-4 variant of chatGPT</p>
<p>The first is presenting a simple situation that is impossible. And asking chatGPT to explain how it could occur.</p>
![asking chatPGT4 how my birth mother missed my birth and it going along](/assets/images/chatGPT4-birth-mother-mistake.png)
<p>chatGPT4 can’t reason about the actual act of birth and so doesn't understand that it’s impossible for a birth mother to miss a child’s birth. Its suggestion of a surrogate doesn't make sense because then the surrogate would be the birth mother as opposed to the biological mother who provided the egg that was implanted in the surrogate. The timezone stuff also sounds like it’s leading to something but doesn't because the question accounted for that.</p>
<p>A second example is tricking its training by taking something that is very familiar and putting a twist on it that fundamentally changes the logic.</p>
![asking chatGPT4 the cabbage, goat, lion question but the goat eats lions and the lion eats cabbages. It fails](/assets/images/chatGPT4-vegetarian-lion-mistake.png)
<p>Here chatGPT4 is able to correctly derive the updated rules that the constraints regarding the lion and goat are swapped, because only because those are the series of words most likely to occur after my question. But it shows that it doesn't understand those rules because the actual solution it gives leaves the lion and cabbage alone. It gave that solution because those are the series of words most likely to occur after the original version of the riddle, which is something almost identical to what I asked. So the model thinks it’s good enough. Because the distance metric between the points on the graph are minimized. The model is not capable of understanding that the changed rules are a hypothetical universe where it must now operate, because that is a fundamentally philosophical task.</p>
<p>(Do note that while these specific examples worked as of the writing of this post, tests like these always get “patched out” as soon as they become popular. This is done using Reinforcement Learning from Human Feedback or RLHF which is an effective technique to put a filter of sorts on the output of the actual model. But it only patches instances of the trend that use similar wording, it fails when the same philosophical problems are presented with different wording. This is the same thing those <a href="https://time.com/6275995/chatgpt-facebook-african-workers-union/"><u>kenyan workers were striking about</u></a>)</p>
<h1>TL;DR</h1>
<ul><li>Every productive thing humans do needs a mixture of math and philosophy</li>
<li>LLMs and other AI are sophisticated calculators, they are limited to math</li>
<li>They can mimic philosophy with math, but not at its core</li>
<li>They are very good at math though, and that will fundamentally change the world</li></ul>

