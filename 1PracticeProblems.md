<br>

# Week 1 Practice Problems 
[Back to the landing page](https://carnap.io/shared/emeskhid@uci.edu/0landingPage.md)

*Please complete the problems below. This assignment will be graded for completion and the solutions will be posted a day after the assignment is due. I will ask you to reflect on these problems as part of your assignment next week.* 
*** 





## Assessing soundness

To assess soundness we need to agree on what is true and what is false. While this is a hard thing to do in general, in the following five problems we simplify this by assuming that the following eight facts about collges and their location and acceptance rates are all true (these were obtained by searching "US colleges" on google, which strangely leads to a google page that does not have an obvious link):

1. Harvard, Massachusetts, acceptance rate 5%
2. Princeton, New Jersey, acceptance rate 7%
3. MIT, Massachusetts, acceptance rate 8%
4. Columbia, New York, acceptance rate 7%
5. Yale, Connecticut,  acceptance rate 6%
6. Cal Tech, California, acceptance rate 8%
7. UC Berkeley, California, acceptance rate 17%
8. Cornell, New York, acceptance rate 14%


The following are four valid arguments which would be translated by substitution instances of modus ponens. But only one of the arguments is sound. Which one is it?

```{.QualitativeProblem .MultipleChoice options="check" submission="none"}
 Which one is sound?
| If Harvard is in Connecticut then Harvard is in the same state as MIT. Harvard is in Connecticut. Therefore Harvard is in the same state as MIT.
| If Yale is in Massachusetts then Yale is in the same state as MIT. Yale is in Massachusetts. Therefore Yale is in the same state as MIT.
| If Yale is in Connecticut then Yale is in the same state as MIT. Yale is in Connecticut. Therefore Yale is in the same state as MIT.
| * If Harvard is in Massachusetts then Harvard is in the same state as MIT. Harvard is in Massachusetts. Therefore Harvard is in the same state as MIT.
```


The following are four valid arguments which would be translated by substitution instances of modus tollens (perhaps together with some replacement using double-negation). But only one of the arguments is sound. Which one is it?

```{.QualitativeProblem .MultipleChoice options="check" submission="none"}
  Which one is sound?
| If Columbia is in New York then Columbia is not in the same state as Princeton. Columbia is in the same state as Princeton. Therefore Columbia is not in New York.
| *If Columbia is in New Jersey then Columbia is in the same state as Princeton. Columbia is not in the same state as Princeton. Therefore Columbia is not in New Jersey.
| If Cal Tech is not in New Jersey then Cal Tech is in the same state as Princeton. Cal Tech is not in the same state as Princeton. Therefore Cal Tech is in New Jersey.
| If Cal Tech is in California then Cal Tech is in the same state as Cornell. Cal Tech is not in the same state as Cornell. Therefore Cal Tech is not in California.
```


The following are four valid arguments which would be translated by substitution instances of disjunctive syllogism (perhaps together with some DeMorgan and double-negation). But only one of the arguments is sound. Which one is it? (In this problem, take "lowest acceptance rate in the state" to be shorthand for "lowest acceptance rate in the state of the colleges displayed in the list above." Also, in this problem, you'll probably have to actually look at the list of acceptance rates up above.)

```{.QualitativeProblem .MultipleChoice options="check" submission="none"}
  Which one is sound?
| Not both Harvard and MIT have the lowest acceptance rate in Massachusetts. MIT has the lowest acceptance rate in Massachusetts. Therefore, Harvard does not have the lowest acceptance rate in Massachusetts.
| Harvard or MIT has the lowest acceptance rate in Massachusetts. Harvard does not have the lowest acceptance rate in Massachusetts. Therefore, MIT has the lowest acceptance rate in Massachusetts.
| MIT has the lowest acceptance rate in Massachusetts. Not both Harvard and MIT have the lowest acceptance rate in Massachusetts.  Therefore, Harvard does not have the lowest acceptance rate in Massachusetts.
| *Not both Harvard and MIT have the lowest acceptance rate in Massachusetts. Harvard has the lowest acceptance rate in Massachusetts. Therefore, MIT does not have the lowest acceptance rate in Massachusetts.
```


Consider the argument: "If Cal Tech has a lower acceptance rate than Cornell, then Cal Tech has a lower acceptance rate than UC Berkeley. Cal Tech has a lower acceptance rate than UC Berkeley. Therefore, Cal Tech has a lower acceptance rate than Cornell."

Which of the following describes this argument:

```{.QualitativeProblem .MultipleChoice options="check" submission="none"}
  Which best describes the argument?
| The argument is sound
| The argument is unsound but valid.
| *The argument is invalid but has all true premises and a true conclusion.
| The argument is invalid and has a false premise or a false conclusion.
```


Consider the argument: "If Cornell does not have a lower acceptance rate than Columbia, then Cornell has a lower acceptance rate than Princeton. Cornell does not have a lower acceptance rate than Columbia. Therefore, Cornell has a lower acceptance rate than Princeton."

Which of the following describes this argument:

```{.QualitativeProblem .MultipleChoice options="check" submission="none"}
  Which best describes the argument?
| The argument is sound
| *The argument is unsound but valid.
| The argument is invalid but has all true premises and a true conclusion.
| The argument is invalid and has a false premise or a false conclusion.
```
