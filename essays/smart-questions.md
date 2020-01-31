---
layout: essay
type: essay
title: Asking Smart Questions (For Dummies!)
# All dates must be YYYY-MM-DD format!
date: 2020-01-23
labels:
---
## Why Ask Questions the Smart Way?
Although in many spheres of academia you might hear the maxim, "There are no stupid questions here!", that certainly doesn't apply in  Programming Forums online. And it's quite clear why: although you may get away with posing a "not smart" question to your professor, who is paid to answer questions (including the not-so-smart ones), you surely won't get away with posting a "not smart" question online and expecting an answer from people who are donating their time to help others.

## How Can I Ask Smart Questions?
### Ground Rules
According to Eric Raymond's "How to ask questions the smart way," some of the qualifications of a smart question include: 
* Aim your question to the right audience. Don't, for example, post a programming question on a vacuum repair forum.
* Don't insult and waste people's time by not doing your research. To avoid the notorious RTFM (Read the Manual) and STFW (Search the Web) answers, make sure you go through those preliminary measures -- and maybe you'll be able to solve the issue yourself along the way.
* Be precise about the problem. You should provide all the details necessary, including but not limited to symptoms, the environment in which it occurs, the research you did to understand what went wrong, and the diagnostics you did to try to solve the problem.
If you've successfully completed all these steps, you can go ahead and ask your question. You should be explicit in asking questions, and make sure it's not just your question that is clear and smart, but if you're posting a question on a forum, your heading should be equally clear and informative to attract the most attention you can. If you've done enough leg work, people will be more likely to answer your question.


## Learn By (Anti) Example
Let's start off the journey through honing our smart question meter by looking at a not-so-smart question. I've found this anti example on Stack Overflow:
<b>Title:</b> How To Add Transition Duration To A Dropdown Css Menu?
<blockquote>
  I just wanted to know if it is possible to add a transition duration to a dropdown menu. I have been looking for an answer online for a while but all I could find is some bootstrap and javascript codes in order to execute this feature.
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
Let's analyze this question using the Ground Rules as specified by Raymond in the prior section. We will address the person who posted this question as Mr. X, for simplicity's sake. 
Firstly, the question is aimed to the right audience. We're on Stack Overflow, so at least Mr. X got that right. 
However, the rest goes downhill from there. It seems that Mr. X didn't do a lot of research, because within one minute of searching Google for "transition duration css dropdown," I found numerous tutorials detailing the specifics of creating a css dropdown with a certain transition duration. What takes the cake, though, is the fact that I found a very similar question on Stack Overflow (which you'll see in the next section) that asks Mr. X's question in a much smarter way, providing much greater detail, and which has multiple answers.
To add insult to injury, this question is not specific or explicit. Mr. X does not provide his CSS, although he's asking a question about CSS. This is insulting to anyone who might stumble upon this question -- it makes one wonder if he even tried to write any of the CSS himself or is expecting it to be handed to him. 
It is clear that Mr. X should anticipate either a nasty answer (STFW, anyone?) or none at all. Perhaps he'd benefit from reading Raymond's article, or maybe just copying and pasting his own header of his post into Google (which would give him his answer in much quicker time than it probably took him to compose that post).
### Repercussions
Mr. X's question is still new, so we can't accurately say that the lack of responses lack the "not smart" nature of his question, but we might try to infer it.

What does Mr. X stand to lose here? Well, firstly, he is losing an opportunity to exercise his problem-solving skills. He could utilize the tools available to him to answer his seemingly simple question, or he could elaborate and take advantage of the many talented programmers that Stack Overflow has to offer. But these talented programmers don't want to waste their free time on an ill-conceived question which Google could easily answer. 

## Learn By Example
This time, let's look at an elevated version of Mr. X's question. Here's another question that I found by searching for Mr. X's own question on Google.

<b>Title:</b> CSS dropdown menu transition
<blockquote>
  I am trying to add dropdown transition for the menu I am working on, but it seems that I have no idea what I am doing wrong. The menu itself appears instantly, ignorning the transition effect.

CSS code I use for transition:
</blockquote>
```
-webkit-transition: height 0.3s ease-in;
-moz-transition: height 0.3s ease-in;
-o-transition: height 0.3s ease-in;
-ms-transition: height 0.3s ease-in;
transition: height 0.3s ease-in;
opacity:0;
```
<blockquote>
  As far as I know I should add it to the nav ul ul CSS block, and adding opacity:1 to nav ul li:hover > ul but it does not work.

And here's whole code of the menu.

HTML
</blockquote>
```
<nav>
    <ul>
        <li><a href="http://www.www.com/">Menu 1</a></li>
        <li><a href="http://www.www.com/">Menu 2</a></li>
        <li><a>Dropdown Here</a>
            <ul>
                <li><a href="http://www.www.com/">Dropdown1</a></li>
                <li><a href="http://www.www.com/">Dropdown2</a></li>
                <li><a href="http://www.www.com/">Dropdown3</a></li>
            </ul>
        </li>
        <li><a href="http://www.www.com/">Menu 4</a></li>
        <li><a href="http://www.www.com/">Menu 5</a></li>
    </ul>
</nav>
```
<blockquote>
  And the CSS I am using
</blockquote>
```
nav ul {
    background: #efefef; 
    background: linear-gradient(top, #efefef 0%, #bbbbbb 100%);  
    background: -moz-linear-gradient(top, #efefef 0%, #bbbbbb 100%); 
    background: -webkit-linear-gradient(top, #efefef 0%,#bbbbbb 100%); 
    box-shadow: 0px 0px 9px rgba(0,0,0,0.15);
    padding: 0 25px;
    border-radius: 10px;  
    list-style: none;
    position: relative;
    display: inline-table;
    float:right;
    z-index:9999;

}
```
(Abbreviated for length.)

We see that the title can use some work, but the rest of this post will demonstrate why this person, who we will designate Mr. Y, has asked a superior question. Let's look at what he does right:
* Mr. Y clearly states his problem with sufficient detail for a response.
* Mr. Y's problem a specific, precise one, unlike Mr. X's problem, which was open ended and provided none of his own code for troubleshooting.
* Mr. Y provides all of his code. Anyone who wants to answer the question has enough peripheral information to get the full picture of what he is trying to accomplish.
* Mr. Y documents what he did to try to resolve the issue. He says, "As far as I know I should...". This is key to showing that he has tried his best to troubleshoot the problem. Unlike Mr. X's problem, which seems like a slap in the face for a qualified person to answer because it requires next to no work to find the solution, Mr. Y has clearly worked on his problem and presented it clearly and explicitly.

### Benefits
The responses to Mr. Y's question show that it is indeed a smart question. He receives a detailed response including a workaround. In fact, he receives multiple responses, each which provide him with a possible solution.

Additionally, his question has been viewed 17,000 times. It's smart not just in that it attracted smart answers, but also that it will be help for future people with the same question. If only Mr. X were one of them.
