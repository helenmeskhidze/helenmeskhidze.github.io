<br>

# Week 1 Practice Problems
[Back to the landing page](https://carnap.io/shared/emeskhid@uci.edu/0landingPage.md) <br>
[Back to the Week 1 materials](https://carnap.io/shared/emeskhid@uci.edu/1Week.md)

*Please complete the problems below by 5pm Friday April 2. This assignment will be graded for completion and 20% of the assignment grade is the reflection you will submit on Canvas (due Saturday, April 3 at 5pm).
<br>
Please make sure you click submit or your answer will not be recorded! Note also that Carnap will not show you which questions you've submitted if you reload the page, so either complete them all in one sitting or keep your own record of what you've submitted.*
***

This set of practice problems consists of 16 problems falling into 4 categories:
  - general content questions
  - questions about wffs
  - practice with translations
  - practice with truth tables

### General content questions

~~~{.QualitativeProblem .MultipleChoice points=".25" options="check"}
1.1 In ((A\/B)->C) what do we call the ->?
| * The main connective.
| The minor connective.
| The truth functional connective.

1.2 What do we call A in A->B?
| * Antecedent.
| Consequent.
| Implicative.

1.3 What do we call A and B in A\/B?
| Antecedents.
| * Disjuncts.
| Consequents.
| Either...or.

1.4 Which of the following is impossible?
| a valid unsound argument
| a valid sound argument
| *an invalid sound argument
| an invalid unsound argument

1.5 Why do we have strict rules for what counts as a wff?
| to make translations easier
| *to eliminate ambiguities
| to eliminate redundancies
~~~

### Questions about wffs

~~~{.QualitativeProblem .MultipleChoice points=".25" options="check"}
2.1 Is P a well-formed formula (wff)?
| *yes
| no

2.2 Is (~~~R) a wff?
| yes
| *no

2.3 Is (~~~R/\A) a wff?
| *yes
| no

2.4 Is (P->(Q->R(->S))) a wff?
| yes
| *no

2.5 Is (P->(Q->(R->S))) a wff?
| *yes
| no
~~~

### Practice with translations


<p style="margin-left: 40px"> $p=$ it appears that the $p$rosecution has failed to prove an essential element of the offense  </p>
<p style="margin-left: 40px"> $e=$ its $e$vidence has been discredited in cross-examination </p>
<p style="margin-left: 40px"> $n=$ there is $n$o case to answer </p>
<p style="margin-left: 40px"> $d=$ the $d$efense responds </p>

~~~{.Translate .Prop system="gamutPND" options="check" points=".25"}
3.1 (p\/e)->(n/\~d) : If it appears that the prosecution has failed to prove an essential element of the offense, or if its evidence has been discredited in cross-examination, there is no case to answer and the defense does not respond.

3.2 (d->(~e/\~p)) : If the defense responds, then it was neither the case that the evidence was discredited in cross-examination nor that the prosecution failed to prove an essential element of the offense.
~~~

<p style="margin-left: 40px"> $p=$ a $p$atient was considered to have a previous diagnosis of asthma </p>
<p style="margin-left: 40px"> $e=$ they were $e$nrolled in the pulmonary clinic with the diagnosis of asthma </p>
<p style="margin-left: 40px"> $r=$ they were $r$eceiving therapy </p>

~~~{.Translate .Prop system="gamutPND" options="check" points=".25"}

3.3 (e/\r)->p : A patient was considered to have a previous diagnosis of asthma if they were enrolled in the pulmonary clinic with the diagnosis of asthma and they were receiving chronic bronchodilator therapy.

3.4 (e/\(r/\f))->p : A patient is considered to have a previous is both receiving therapy and enrolled in a pulmonary clinic

~~~


### Practice with truth tables

The following homework problems are intended to help you *internalize* truth-tables for the propositional connectives. Only one of the rows are given, and this is designed to help you *internalize* the truth-tables row-by-row, and to make sure that your recall of this is not tied to the particular order we happened to enumerate the rows in.

~~~{.TruthTable .Partial system="gamutPND" options="check nodash nocounterexample autoAtoms"  points=".25"}
4.1 p/\q
| F - F
~~~

~~~{.TruthTable .Partial system="gamutPND" options="nodash nocounterexample autoAtoms"  points=".25"}
4.2 p\/q
| F - F
~~~

~~~{.TruthTable .Partial system="gamutPND" options="nodash nocounterexample autoAtoms"  points=".25"}
4.3 p->q
| F - F
~~~

~~~{.TruthTable .Partial system="gamutPND" options="nodash nocounterexample autoAtoms"  points=".25"}
4.4 p/\q
| T - F
~~~

~~~{.TruthTable .Partial system="gamutPND" options="nodash nocounterexample autoAtoms" points=".25"}
4.5 p\/q
| T - F
~~~
