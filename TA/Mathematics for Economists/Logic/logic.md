# Logic

**Author:** Abhijeet  
**Institute:** IGIDR  
**Date:** August 12, 2025

---

## Statements

- **Statements** are declarative or an assertion that is either true or false (but not both).
- (a) The integer 3 is odd. (b) The square root of 1 is 0. Both are statements. The former is true, the latter is false.
- For a sentence to be considered as a statement, it is not necessary that we know the truth value of the statement.
- The possible truth value of a **statement** can be listed in a truth table. The following is an example:

| $P$ | T | T | T | T | F | F | F | F |
|-----|---|---|---|---|---|---|---|---|
| $Q$ | T | T | F | F | T | T | F | F |
| $R$ | T | F | T | F | T | F | T | F |

---

## Negations

- The **negation** of a statment **P** is the statement **not P**.
- e.g., $P_{1}:$ The Sun rises in the east. $\neg P_{1}:$ The Sun rises in the west. Statement $P_{1}$ is true while statment $ \neg P_{1}$ is false.
- The negation of a **true** statement is always false and vice versa. 

| $P$ | $\neg P$ |
|-----|----------|
| T   | F        |
| F   | T        |

---

## Disjunctions

- The **disjunction** of the statement **P** and **Q** is the statement **P or Q** and is denoted by **P $\lor$ Q**.
- The disjunction statment is true if either one of P and Q is true, or if both P and Q is true. 
- For example, P: The integer 10 is even, Q: 5 is the cube root of 25. Here P is true and Q is false. The disjunction statement would be P$\lor$Q, which we would read, Either "The integer 10 is even" or "5 is a cube root of 25". And this disjunction statement is true, cause P is true.

| $P$ | T | T | F | F |
|-----|---|---|---|---|
| $Q$ | T | F | T | F |
| $P \lor Q$ | T | T | T | F |

---

## Conjunctions

- The **conjunction** of the statement **P** and **Q** is the statement **P and Q** and is denoted by **P $\land$ Q**.
- The conjunction statment is true when both P and Q are true, otherwise the conjunction statement is false.
- For example, P: The integer 10 is even, Q: 5 is the cube root of 25. Here P is true and Q is false. The disjunction statement would be P$\land$Q, which we would read, "The integer 10 is even" and "5 is a cube root of 25". And this conjunction statement is False, cause Q is False.

| $P$ | T | T | F | F |
|-----|---|---|---|---|
| $Q$ | T | F | T | F |
| $P \lor Q$ | T | F | F | F |

---

## Implications (Conditional)

- For statements $P$ and $Q$, the implication (or conditional) is the statement $$\text{If } P, \text{ then } Q$$. in such a acse the statemnt is called "Vacuously true". and is denoted by $P \Rightarrow Q$. We can also say, "$P$ implies $Q$."
- $P \Rightarrow Q$ is false only when $P$ is true and $Q$ is false ($P \Rightarrow Q$ is true otherwise).
- For $P_1$: The integer 3 is odd. and $P_2$: The integer 57 is prime., the implication $P_1 \Rightarrow P_2 \text{: If 3 is an odd integer, then 57 is prime.}$ is a false statement. The implication,$P_2 \Rightarrow P_1 \text{: If 57 is prime, then 3 is odd.}$ is true.

| $P$ | T | T | F | F |
|-----|---|---|---|---|
| $Q$ | T | F | T | F |
| $P \Rightarrow Q$ | T | F | T | T |

---

## Implications (Conditional)

The statement or open sentence $P$ in the implication $P \Rightarrow Q$ is commonly referred to as the **hypothesis** or **premise** of $P \Rightarrow Q$, while $Q$ is called the **conclusion** of $P \Rightarrow Q$.

The following are equivalent: 
- If $P$, then $Q$.
- $Q$ if $P$.
- $P$ implies $Q$.
- $P$ only if $Q$.
- $P$ is sufficient for $Q$.
- $Q$ is necessary for $P$.

Use, P: You get A+ and Q: I give you a favour.

---

## Bi-Conditional

- For statements (or open sentences) $P$ and $Q$, the conjunction $(P \Rightarrow Q) \land (Q \Rightarrow P)$ of the implication $P \Rightarrow Q$ and its converse is called the biconditional of $P$ and $Q$ and is denoted by $P \Leftrightarrow Q$.

| $P$ | T | T | F | F |
|-----|---|---|---|---|
| $Q$ | T | F | T | F |
| $P \Leftrightarrow Q$ | T | F | F | T |

- The following are equivalent ways to say $P \Leftrightarrow Q$:
  - $P$ is equivalent to $Q$
  - $P$ if and only if $Q$
  - $P$ is necessary and sufficient for $Q$

---

## Examples: 1

State the negations of the following statements: 
1. 2 is a rational number.
2. Two sides of the triangle have the same length.
3. The area of the circle is at least $9\pi$.
4. The point $P$ in the plane lies outside of the circle $C$.

Complete the truth table:

| $P$ | $Q$ | $\neg P$ | $\neg Q$ |
|-----|-----|----------|----------|
| T   | T   |          |          |
| T   | F   |          |          |
| F   | T   |          |          |
| F   | F   |          |          |

---

## Examples: 2

Let $P$: 15 is odd. and $Q$: 21 is prime.  
State each of the following in words and determine whether it is true or false.
1. $P \lor Q$
2. $P \land Q$
3. $(\neg P) \lor Q$
4. $P \land (\neg Q)$

Complete the truth table:

| $P$ | $Q$ | $\neg Q$ | $P \land (\neg Q)$ |
|-----|-----|----------|--------------------|
| T   | T   |          |                    |
| T   | F   |          |                    |
| F   | T   |          |                    |
| F   | F   |          |                    |

---

## Examples: 3

Consider the statements $P$: 2 is rational. and $Q$: $22/7$ is rational.  
Write each of the following statements in words and indicate whether it is true or false.
1. $P \Rightarrow Q$
2. $Q \Rightarrow P$
3. $(\neg P) \Rightarrow (\neg Q)$
4. $(\neg Q) \Rightarrow (\neg P)$

---

## Examples: 4

A college student makes the following statement:
> If I receive an A in both Calculus I and Discrete Mathematics this semester, then I'll take either Calculus II or Computer Programming this summer.

For each of the following, determine whether the statement above is true or false.
1. The student doesn't get an A in Calculus I but decides to take Calculus II this summer anyway.
2. The student gets an A in both Calculus I and Discrete Mathematics but decides not to take any class this summer.
3. The student does not get an A in Calculus I and decides not to take Calculus II but takes Computer Programming this summer.
4. The student gets an A in both Calculus I and Discrete Mathematics and decides to take both Calculus II and Computer Programming this summer.

---

## Examples: 5

Let $P(x)$: $x$ is odd. and $Q(x)$: $x^2$ is odd. be open sentences over the domain $\mathbb{Z}$. State $P(x) \Leftrightarrow Q(x)$ in two ways: (1) using "if and only if" and (2) using "necessary and sufficient."

Consider the open sentences:  
$P(x) : x = -2$. and $Q(x) : x^2 = 4$.  
over the domain $S = \{-2, 0, 2\}$. State each of the following in words and determine all values of $x \in S$ for which the resulting statements are true.
1. $\neg P(x)$
2. $P(x) \lor Q(x)$
3. $P(x) \land Q(x)$
4. $Q(x) \Rightarrow P(x)$
5. $P(x) \Leftrightarrow Q(x)$

---

## Tautologies and Contradictions

1. The symbols $\neg$, $\lor$, $\land$, $\Rightarrow$ and $\Leftrightarrow$ are referred to as logical connectives. A compound statement is a statement composed of one or more given statements and at least one logical connective. For example, for a given component statement $P$, its negation $\neg P$ is a compound statement.
2. A compound statement $S$ is called a **tautology** if it is true for all possible combinations of truth values of the component statements that comprise $S$. Hence, $P \lor (\neg P)$ is a tautology.
3. A compound statement $S$ is called a **contradiction** if it is false for all possible combinations of truth values of the component statements that are used to form $S$. The statement $P \land (\neg P)$ is a contradiction. If a compound statement $S$ is a tautology, then its negation $\neg S$ is a contradiction.

---

## Examples 6

- For statements $P$ and $Q$, show that $P \Rightarrow (P \lor Q)$ is a tautology.
- For statements $P$ and $Q$, show that $(P \land (\neg Q)) \land (P \land Q)$ and $(P \Rightarrow \neg Q) \land (P \land Q)$ are contradictions.
- For statements $P$ and $Q$, show that $(P \land (P \Rightarrow Q)) \Rightarrow Q$ is a tautology. 
- For statements $P$, $Q$ and $R$, show that $((P \Rightarrow Q) \land (Q \Rightarrow R)) \Rightarrow (P \Rightarrow R)$ is a tautology.
- Let $R$ and $S$ be compound statements involving the same component statements. If $R$ is a tautology and $S$ is a contradiction, then what can be said of the following?

---

## Logical equivalence

Let $R$ and $S$ be two compound statements involving the same component statements. Then $R$ and $S$ are called **logically equivalent** if $R$ and $S$ have the same truth values for all combinations of truth values of their component statements.

| $P$ | $Q$ | $\neg P$ | $P \Rightarrow Q$ | $(\neg P) \lor Q$ |
|-----|-----|----------|-------------------|-------------------|
| T   | T   | F        | T                 | T                 |
| T   | F   | F        | F                 | F                 |
| F   | T   | T        | T                 | T                 |
| F   | F   | T        | T                 | T                 |

P: You earn an A on the final exam, Q: you will receive a Chocolate. How would we know that the instructor didn't keep his promise? Only when "P" is true and "Q" is false (In the case of P $\Rightarrow$ Q). But how do we express in a single sentence that the teacher kept the promise? Either "you did not get an A" OR "You received a chocolate". That is, $\neg P \lor Q$.

---

## Examples 7

- Let $P$ and $Q$ be statements.
  1. Is $\neg (P \lor Q)$ logically equivalent to $(\neg P) \lor (\neg Q)$? Explain.
  2. What can you say about the biconditional $\neg (P \lor Q) \Leftrightarrow ((\neg P) \lor (\neg Q))$?
- For statements $P$, $Q$ and $R$, use a truth table to show that each of the following pairs of statements are logically equivalent.
  1. $(P \land Q) \Leftrightarrow P$ and $P \Rightarrow Q$.
  2. $P \Rightarrow (Q \lor R)$ and $(\neg Q) \Rightarrow ((\neg P) \lor R)$.
- For statements $P$ and $Q$, show that $(\neg Q) \Rightarrow (P \land (\neg P))$ and $Q$ are logically equivalent.
- For statements $P$, $Q$ and $R$, show that $(P \lor Q) \Rightarrow R$ and $(P \Rightarrow R) \land (Q \Rightarrow R)$ are logically equivalent.

---

## Some fundamental Properties of Logical Equivalence

For statements $P$, $Q$ and $R$, Thefollowing are logically equivalent.

- **Commutative Laws**
  1. $P \lor Q \equiv Q \lor P$.
  2. $P \land Q \equiv Q \land P$.
- **Associative Laws**
  1. $P \lor (Q \lor R) \equiv (P \lor Q) \lor R$.
  2. $P \land (Q \land R) \equiv (P \land Q) \land R$.
- **Distributive Laws**
  1. $P \lor (Q \land R) \equiv (P \lor Q) \land (P \lor R)$.
  2. $P \land (Q \lor R) \equiv (P \land Q) \lor (P \land R)$.
- **De Morgan's Laws**
  1. $\neg (P \lor Q) \equiv (\neg P) \land (\neg Q)$.
  2. $\neg (P \land Q) \equiv (\neg P) \lor (\neg Q)$.

---

## Examples 8

- Let $P$, $Q$ and $R$ be statements. Then $P \lor (Q \land R)$ and $(P \lor Q) \land (P \lor R)$ are logically equivalent.
- Let $P$ and $Q$ be statements. Then $\neg (P \lor Q)$ and $(\neg P) \land (\neg Q)$ are logically equivalent.
- For a real number $x$, let $P(x): x^2 = 2$. and $Q(x): x = 2$. State the negation of the biconditional $P \Leftrightarrow Q$ in words.
- Let $P$ and $Q$ be statements. Show that $[(P \lor Q) \land \neg (P \land Q)] \equiv \neg (P \Leftrightarrow Q)$.

---

## Quantified Statements- For All

- If $P(x)$ is an open sentence over a domain $S$, then $P(x)$ is a statement for each $x \in S$.
- An open sentence can be converted into a statement, namely by a method called quantification.
- Let $P(x)$ be an open sentence over a domain $S$. Adding the phrase "For every $x \in S$" to $P(x)$ produces a statement called a quantified statement.
- The phrase "for every" is referred to as the universal quantifier and is denoted by the symbol $\forall$. Other ways to express the universal quantifier are "for each" and "for all."

---

## Quantified Statements- There Exists

- Each of the phrases "there exists," "there is," "for some," and "for at least one" is referred to as an **existential quantifier** and is denoted by the symbol $\exists$. The quantified statement $$ \exists x \in S, P(x) $$ can be expressed in words by "There exists $x \in S$ such that $P(x)$."
- An open sentence can be converted into a statement, namely by a method called quantification.
- The existential quantifier is used to claim that at least one statement resulting from a given open sentence is true when the values of a variable are assigned from its domain. We know that for an open sentence $P(x)$ over a domain $S$, the quantified statement $\exists x \in S, P(x)$ is true provided $P(x)$ is a true statement for at least one element $x \in S$.

---

## Quantified statements

- The statement $\exists x \in \mathbb{R}, x^2 > 0$ is true since, for example, $x^2 > 0$ is true for $x = 1$.
- The quantified statement $\exists x \in \mathbb{R}, 3x = 12$ is therefore true since there is some real number $x$ for which $3x = 12$, namely $x = 4$ has this property.

---

## Examples 9

Consider the statement  
> For every two real numbers $x$ and $y$, $x^2 + y^2 \ge 0$.

If we let $P(x, y) : x^2 + y^2 \ge 0$ where the domain of both $x$ and $y$ is $\mathbb{R}$, then this statement can be expressed as  
$$ \forall x \in \mathbb{R}, \forall y \in \mathbb{R}, P(x, y) $$  
or as  
$$ \forall y \in \mathbb{R}, \forall x \in \mathbb{R}, P(x, y), \quad \text{or as} \quad \forall x, y \in \mathbb{R}, P(x, y) \quad \text{or} \quad \forall y, x \in \mathbb{R}, P(x, y) $$  
since quantifiers of the same type commute. Since $x^2 \ge 0$ and $y^2 \ge 0$ for all real numbers $x$ and $y$, it follows that $x^2 + y^2 \ge 0$ and so $P(x, y)$ is true for all real numbers $x$ and $y$. Thus, this quantified statement is true.

---

## Examples 9

The negation of this statement is therefore  
\begin{align*}
    \neg (\forall x \in \mathbb{R}, \forall y \in \mathbb{R}, P(x, y)) &\equiv \exists x \in \mathbb{R}, \exists y \in \mathbb{R}, \neg P(x, y) \\
    &\equiv \exists x, y \in \mathbb{R}, \neg P(x, y)
\end{align*}  
which, in words, is  
> There exist real numbers $x$ and $y$ such that $x^2 + y^2 < 0$.

The resulting statement is therefore false.

For an open sentence containing two variables, the domains of the variables need not be the same.

State the negations of the following quantified statements:
1. For every rational number $r$, the number $1/r$ is rational.
2. There exists a rational number $r$ such that $r^2 = 2$.