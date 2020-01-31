---
layout: essay
type: essay
title: Asking Smart Questions (For Dummies!)
# All dates must be YYYY-MM-DD format!
date: 2020-01-30
labels:
  - questions
  - life
  - etiquette
---
## Why Ask Questions the Smart Way?
<img class="ui small right floated image" src="../images/question.jpeg">
In many spheres of academia you might hear the maxim, "There are no stupid questions here!" However, that's certainly not true for programming forums like Stack Overflow. It's quite clear why: although you might (sometimes) get away with posing a "not-so-smart" question to a professor who is accustomed to answering those kind of questions, you surely won't get away with posing a "not-so-smart" question to an online forum consisting of people who donate their time to helping others.

---

## How Can I Ask Smart Questions?
### Ground Rules
According to Eric Raymond's "How to ask questions the smart way," some of the qualifications of a smart question include: 
* Aim your question to the right audience. Don't, for example, post a programming question on a vacuum repair forum.
* Don't waste people's time. Do your research. To avoid the notorious RTFM (Read the Manual) and STFW (Search the Web) answers, make sure you go ahead and read the manual, or search the web, whichever applies to you. You might even find that you'll solve the problem on your own in the process.
* Be precise about your problem. You should provide all the details necessary, including but not limited to symptoms, the environment in which the problem occurs, the research you did to understand what went wrong, and the steps you took to try and solve the problem.

If you've successfully completed all these steps, you can go ahead and ask your smart question. When dealing with online forums, the heading for your question should be equally smart and informative. You want to grab the attention of those code-wizards who might be lurking. If you've done enough leg work, people will be more likely to answer your question.

---

## Learn By Anti-Example
Let's start off by honing our smart question radar by first looking at a "not-so-smart" question. I've found this anti example on Stack Overflow:

#### <b>Title:</b> How To Add Transition Duration To A Dropdown Css Menu?
<blockquote>
  "I just wanted to know if it is possible to add a transition duration to a dropdown menu. I have been looking for an answer online for a while but all I could find is some bootstrap and javascript codes in order to execute this feature."
</blockquote>

```
 <li class="dropdown"><a href="#" class="dropbtn">Dropdown</a>
                    <div class="dropdown-content">
                       <a href="#">Houses</a>
                       <a href="#">Catles</a>
                       <a href="#">Studios</a>
                    </div>
            </li>
 ```
You may be wondering, "What's the issue?" A question is a question, right? Well, the utility of a question to the person who asks it (and anyone who may have the same question) depends on its likeliness to get answered. And the smarter the question, the more likely it will receive an answer.

Let's analyze this question using the Ground Rules as specified by Raymond in the prior section. We will address the person who posted this question as Mr. X, for simplicity's sake. 
* The question is aimed to the right audience. We're on Stack Overflow, so at least Mr. X got that right. Unfortunately, the rest goes downhill from here.
* It seems that Mr. X didn't do a lot of research, because within one minute of searching Google for "transition duration css dropdown," I found numerous tutorials detailing the specifics of creating a css dropdown with a certain transition duration. What takes the cake, though, is the fact that I found a very similar question on Stack Overflow (which you'll see in the next section) that asks Mr. X's question in a much smarter way, providing much greater detail, and which has multiple answers.
* To add insult to injury, this question is neither specific nor explicit. Mr. X provides his HTML but not his CSS, although he's asking a question about CSS. This is insulting to anyone who might stumble upon this question -- it makes one wonder if he even tried to write any of the CSS himself or is expecting it to be handed to him. 

Unfortunately, Mr. X might be in for a snarky answer or none at all. Perhaps he'd benefit from reading Raymond's article, or maybe just copying and pasting the header of his post into Google (which would probably give him his answer much faster than it took him to compose the post).

### Repercussions
Mr. X's question is still new, so we can't accurately say that the lack of responses reflect the "not-so-smart" nature of his question, but we might try to infer it.

What does Mr. X stand to lose here? Firstly, he losing an opportunity to exercise his problem-solving skills. He could utilize the tools available to him (namely, Google and the Stack Overflow search bar) to answer his question, or he could elaborate on his sparse question and take advantage of the many talented programmers that Stack Overflow has to offer.

---

## Learn By Example
This time, let's look at an elevated version of Mr. X's question. Below is another question posted on Stack Overflow. Ironically, I found this smart question by pasting the heading of Mr. X's "not-so-smart" one into Google.

#### <b>Title:</b> CSS dropdown menu transition
<blockquote>
  "I am trying to add dropdown transition for the menu I am working on, but it seems that I have no idea what I am doing wrong. The menu itself appears instantly, ignorning the transition effect.

CSS code I use for transition:"
</blockquote>
```
-webkit-transition: height 0.3s ease-in;
-moz-transition: height 0.3s ease-in;
...
```
<blockquote>
  "As far as I know I should add it to the nav ul ul CSS block, and adding opacity:1 to nav ul li:hover > ul but it does not work.

And here's whole code of the menu."

HTML
</blockquote>
```
<nav>
    <ul>
        <li><a href="http://www.www.com/">Menu 1</a></li>
        <li><a href="http://www.www.com/">Menu 2</a></li>
        <li><a>Dropdown Here</a>
        ...
</nav>
```
<blockquote>
  "And the CSS I am using"
</blockquote>
```
nav ul {
    background: #efefef; 
    background: linear-gradient(top, #efefef 0%, #bbbbbb 100%); 
    ...
}
```
(All code above was abbreviated for length.)

Clearly, the title could use some work to draw people in, but the rest of this post will demonstrate why this person, who we will designate Mr. Y, has asked a superior question to Mr. X. Let's look at what he does right:
* Mr. Y clearly states his problem with sufficient detail for a response.
* Mr. Y's problem is a specific, precise one, unlike Mr. X's problem, which is open ended. Unlike Mr. Y, Mr. X provided none of his own code for troubleshooting, making it difficult and/or tedious to answer.
* Mr. Y provides ALL of his code (HTML and CSS) Anyone who wants to answer the question has enough peripheral information to get the full picture of what he is trying to accomplish. While Raymond says that posting large chunks of code is not always the best method, if it can provide others more insight to help you, post the necessary information.
* Mr. Y documents what he did to try to resolve the issue, "as far as (he) knows." This is key to showing that he has done his part in troubleshooting the problem. It shows in a respectful way that he is not asking more of others than he did of himself.

### Benefits
<img class="ui medium right floated image" src="../images/congratulations-you-figured.jpg">
The responses to Mr. Y's question show that it is indeed a smart question. He receives a detailed response including a workaround. In fact, he receives multiple responses, each which provide him with a possible solution.

Perhaps the most important observation about Mr. Y's post is that his question has been viewed 17,000 times. The "smartness" of his question is self-evident: not only did it attract smart answers, but it provides a lasting source of information for anyone who might encounter the same issue at some point in time. This question will be accessible to people in need who have the wherewithal to do a Google search. If only Mr. X were one of them.
