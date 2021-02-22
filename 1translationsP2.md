<br>

# How do I translate into (sentential) logic? 
## Part 2
[Back to the landing page](https://carnap.io/shared/emeskhid@uci.edu/0landingPage.md)


<!-- <video controls width="700" src=""/> </video> -->

### Translation Excercises 
In the following examples, we use the abbreviations:

<p style="margin-left: 40px"> $a$ = Anthony attends </p>
<p style="margin-left: 40px"> $b$ = Briana attends </p>
<p style="margin-left: 40px"> $c$ = Cynthia attends </p>
<p style="margin-left: 40px"> $d$ = Dylan attends </p>

Please review the quick video on [how to complete translation excercises](https://carnap.io/shared/emeskhid@uci.edu/1translationsP1.md#translations) if you've forgotten. 


~~~{.Translate .Prop system="gamutPND" submission="none"}
 (a\/b)->(c/\d) : If Anthony attends or Briana attends then Cynthia attends and Dylan attends.
~~~

~~~{.Translate .Prop system="gamutPND" submission="none"}
 (a/\b)->(c\/d) : If Anthony attends and Briana attends then Cynthia attends or Dylan attends.
~~~

~~~{.Translate .Prop system="gamutPND" submission="none"}
 (a->b)/\(c->d) : If Anthony attends then Briana attends, and if Claire attends then Dylan attends.
~~~

~~~{.Translate .Prop system="gamutPND" submission="none"}
 (~a->b): If Anthony does not attend then Briana attends.
~~~

~~~{.Translate .Prop system="gamutPND" submission="none"}
 ~(a->b) : It is not the case that if Anthony attends then Briana attends.
~~~

~~~{.Translate .Prop system="gamutPND" submission="none"}
 (a<->~b) : Anthony attends if and only if Briana does not attend.
~~~

## Practice finding the main connectives

A good way to learn how to read well-formed formulas is to find the main connectives. In fact, this skill will be essential for constructing truth tables. In the following problems we successively find the main connectives of the formulas, starting with the big formulas and breaking them into smaller parts. Press return after you have entered in the main connective to get to the next level. Here's a quick video demonstrating how to complete these excercises and a sample excercise to get you started: 

<video controls width="500" src="https://helenmeskhidze.github.io/Examples%20for%20videos/FindingMainConnective.mp4" /> </video> 

Example to follow along with the video: find the main connective
```{.SynChecker .Match system="gamutPND" submission="none"}
 ((p/\q)->(~q\/r))
```

### Main Connective Excercises 

Two quick notes. First, you can also just cut and paste the main connective instead of typing it. Second, ignore the "You may now submit your solution" remark after you finish.



```{.SynChecker .Match system="gamutPND" submission="none"}
 ((p/\q)->(~q\/r))
```

```{.SynChecker .Match system="gamutPND" submission="none"}
 (q->((~p\/r)/\s))
```

```{.SynChecker .Match system="gamutPND" submission="none"}
 ((p/\~q) \/ (q<->r))
```

```{.SynChecker .Match system="gamutPND" submission="none"}
 ((p->(q/\~r))->(s\/~t))
```

## Dropping outermost parentheses

As we have seen, parentheses are crucial for the avoidance of ambiguity in our well-formed formulas. However, when we write things out by hand, the last parentheses that we write can be omitted without any loss of confusion. That is, we can write just $p\wedge q$ instead of $(p\wedge q)$. Likewise, we can just write $p\wedge (q\vee r)$ instead of $(p\wedge (q\vee r))$. However, we cannot drop inner parentheses, since e.g $p\wedge q\vee r)$ is ambiguous in exactly the way we are trying to avoid. We maintain the convention of allowing ourselves to drop outermost parentheses throughout this course.

<br>