# 📖 Glossary

## Glossary of Logical Terms

### Proposition
A **proposition** is a declarative statement that is either *true* or *false*, but not both. It represents the content of a statement regardless of its linguistic form.

**Examples:**
- "The Earth orbits the Sun" is a proposition because it can be evaluated as true.
- "The Moon is made of cheese." (False)
- "2 + 2 = 4" (True)

---

### Predicate
A **predicate** is a function or property that returns a truth value when applied to one or more subjects. In logic, it expresses something about an object or variable, often written as \( P(x) \).

**Examples:**
- In "Socrates is mortal", "is mortal" is the predicate and "Socrates" is the subject. In predicate logic: Mortal(x) 
- IsTall(x): "x is tall"
- Loves(x, y): "x loves y"
- Prime(n): "n is a prime number"

---

### Premise
A **premise** is a proposition that provides support or reasons for a conclusion in an argument. Premises are the starting points of reasoning.

**Examples:**
- "All mammals are warm-blooded."
- "If it rains, the ground gets wet."
- "Jane is taller than Tom."

---

### Argument
An **argument** is a group of propositions in which some (premises) are intended to support another (conclusion). It's the fundamental structure of reasoning.

**Example 1:**
   - Premise: All birds have feathers.  
   - Premise: A sparrow is a bird.  
   - Conclusion: Therefore, a sparrow has feathers.

**Example 1:**
   - Premise: If you study, you will pass.  
   - Premise: You studied.  
   - Conclusion: Therefore, you will pass.

---

### Conclusion
A **conclusion** is the proposition that is supported or proven by the premises in an argument.

**Examples:**
- "Therefore, the Earth is round." (based on previous evidence/premises)
- "Hence, she must be at home."
- "It follows that all bachelors are unmarried."

---

### Inference (Reasoning)
**Inference**, or **reasoning**, is the process of deriving logical conclusions from premises or known facts.

**Examples:**
- From "All dogs bark" and "Rex is a dog," we infer "Rex barks."
- From "If the light is red, stop" and "The light is red," infer "Stop."
- From "All metals conduct electricity" and "Copper is a metal," infer "Copper conducts electricity."

---

### Validity (Valid)
An argument is **valid** if the conclusion necessarily follows from the premises. Validity is about form, not the actual truth of the statements.

**Examples:**
1.  
   - Premise: All cats are animals.  
   - Premise: Felix is a cat.  
   - Conclusion: Felix is an animal. ✅ Valid

2.  
   - Premise: All unicorns are reptiles.  
   - Premise: Bob is a unicorn.  
   - Conclusion: Bob is a reptile. ✅ Valid (though premises are false)

3.  
   - Premise: Some dogs are brown.  
   - Premise: Rex is brown.  
   - Conclusion: Rex is a dog. ❌ Invalid (conclusion doesn't logically follow)

---


## Glossary of Proof-Related Terms

### Theorem
A **theorem** is a mathematical or logical statement that has been proven to be true based on previously established statements such as axioms, definitions, and earlier theorems.

**Examples:**
- Pythagorean Theorem: \( a^2 + b^2 = c^2 \)
- Fundamental Theorem of Calculus
- Gödel’s Incompleteness Theorems

---

### Proposition (in proof context)
A **proposition** in the context of proofs is a statement that is proved true using logic and previously proven statements. It is often considered less central or less important than a theorem.

**Examples:**
- In some texts, a small result that is still worth proving may be called a proposition.
- "Every finite group of prime order is cyclic."

---

### Proof
A **proof** is a logical argument demonstrating the truth of a theorem or proposition, using deductive reasoning from accepted premises, axioms, and previously established results.

**Examples:**
- A direct proof using definitions and logical steps.
- A proof by contradiction assuming the opposite and deriving a contradiction.
- An inductive proof involving base cases and inductive steps.

---

### Axiom
An **axiom** (or **postulate**) is a self-evident or universally accepted principle that does not require proof. It serves as a starting point for logical or mathematical reasoning.

**Examples:**
- In geometry: "Through any two points, there exists exactly one line."
- In arithmetic: "For any number \( a \), \( a + 0 = a \)."
- In set theory: "Two sets are equal if they contain the same elements."

---

### Lemma
A **lemma** is a proven statement used as a stepping stone to prove a larger result (typically a theorem). While it may be useful in its own right, its main role is as a helper theorem.

**Examples:**
- Euclid’s Lemma: If a prime divides a product, it divides at least one factor.
- Schwarz’s Lemma in complex analysis.

---

### Corollary
A **corollary** is a statement that follows readily and with little or no additional proof from a previously proven theorem or proposition.

**Examples:**
- Corollary to the Pythagorean Theorem: If two sides of a triangle are perpendicular, the square of the hypotenuse equals the sum of the squares of the other two sides.
- Corollary: Every finite subgroup of the multiplicative group of a field is cyclic.

---

### Conjecture
A **conjecture** is a statement that is believed to be true based on observations or evidence but has not yet been proven or disproven.

**Examples:**
- Goldbach’s Conjecture: Every even integer greater than 2 is the sum of two primes.
- Collatz Conjecture
- Twin Prime Conjecture

---