<br>

# How do I translate into (sentential) logic? 
## Part 1

<br>



## A recipe for translation

Here is an easy three-step recipe for translating:

1. Identify the smallest sub-sentences of the example which can be true or false.

2. Assign arbitrary propositional letters to these, and rewrite using them in place of originals.

3. Look for propositional letters that are connected by "and", "or", as well as "if . . . then. . ." and "if and only if." Then translate via the symbols $\wedge$, $\vee$, $\rightarrow$, $\leftrightarrow$. Do the same for negation.

<br>

## Two quick notes about the translation-checker

1. It assumes that you remember how to type the logical symbols. If you need a refreshed on this, consider reviewing [how to type the connectives on the keyboard](https://carnap.io/shared/walsh@g.ucla.edu/book-prop-main-connectives.pandoc#typing-the-connectives-on-the-keyboard).

2. Press **return** to check your answer.

<br>

## Further examples

In the following examples, we use the abbreviations:


<p style="margin-left: 40px"> $a$ = Anthony attends the meeting</p>
<p style="margin-left: 40px"> $b$ = Briana stays at the office</p>



~~~{.Translate .Prop system="gamutPND" submission="none"}
  a /\ b : Anthony attends the meeting and Briana stays at the office.
~~~


~~~{.Translate .Prop system="gamutPND" submission="none"}
  a /\ b : Either Anthony attends the meeting or Briana does not stay at the office.
~~~


~~~{.Translate .Prop system="gamutPND" submission="none"}
 a->b : If Anthony attends the meeting, then Briana stays at the office
~~~

~~~{.Translate .Prop system="gamutPND" submission="none"}
 ~b->~a : If Briana does not stay at the office, then Anthony does not attend the meeting.
~~~
