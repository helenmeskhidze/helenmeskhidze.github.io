<br>

# How do I translate into (sentential) logic? 
## Part 1
[Back to the landing page](https://carnap.io/shared/emeskhid@uci.edu/0landingPage.md)

<!-- <video controls width="700" src=""/> </video> -->



## A recipe for translation

Here is an easy three-step recipe for translating:

1. Identify the smallest sub-sentences of the example which can be true or false.

2. Assign arbitrary propositional letters to these, and rewrite using them in place of originals.

3. Look for propositional letters that are connected by "and", "or", as well as "if . . . then. . ." and "if and only if." Then translate via the symbols $\wedge$, $\vee$, $\rightarrow$, $\leftrightarrow$. Do the same for negation.

<br>

## A few quick notes about the translation-checker

1. It assumes that you remember how to type the logical symbols. If you need a refreshed on this, consider reviewing [how to type the connectives on the keyboard](https://carnap.io/shared/emeskhid@uci.edu/0CourseInfo.md#typing-the-connectives).

2. You type your translation in the top box. Replace the English sentence(s) there with your logical expression.

3. Press **return** to check your answer.

<br>

## Translations 

In the following examples, we use the abbreviations:


<p style="margin-left: 40px"> $a$ = Anthony attends the meeting</p>
<p style="margin-left: 40px"> $b$ = Briana stays at the office</p>


<video controls width="500" src="https://helenmeskhidze.github.io/Examples%20for%20videos/Translation.mp4" /> </video> 

Example to follow along with the video-- translate the following: 

~~~{.Translate .Prop system="gamutPND" submission="none"}
  a /\ b : Anthony attends the meeting and Briana stays at the office.
~~~

## Translation Excercises

Use the same abbreviations as above to translate: 

~~~{.Translate .Prop system="gamutPND" submission="none"}
  a \/ ~b : Either Anthony attends the meeting or Briana does not stay at the office.
~~~


~~~{.Translate .Prop system="gamutPND" submission="none"}
 a->b : If Anthony attends the meeting, then Briana stays at the office
~~~

~~~{.Translate .Prop system="gamutPND" submission="none"}
 ~b->~a : If Briana does not stay at the office, then Anthony does not attend the meeting.
~~~
