# Probability
- Its the likelihood of certain event

## Types of EVent
1. Independent: One event does not affect the other
2. Dependent: One event affects the prob of the other
3. Mutually Exclusive: Events that cannot happen at the same time

---

### 🎯 Basic Probability

**Probability of an Event A:**

\[
P(A) = \frac{\text{Number of favorable outcomes}}{\text{Total number of outcomes}}
\]

---

### ➕ Addition Rule

**For mutually exclusive events A and B:**

\[
P(A \cup B) = P(A) + P(B)
\]

**For general events A and B:**

\[
P(A \cup B) = P(A) + P(B) - P(A \cap B)
\]

---

### ✖️ Multiplication Rule

**For independent events A and B:**

\[
P(A \cap B) = P(A) \times P(B)
\]

**For dependent events:**

\[
P(A \cap B) = P(A) \times P(B|A)
\]

---

### 📌 Conditional Probability

**Probability of A given B:**

\[
P(A|B) = \frac{P(A \cap B)}{P(B)}
\]

---

### 🔁 Bayes’ Theorem

\[
P(A|B) = \frac{P(B|A) \times P(A)}{P(B)}
\]

Where:
- \( P(A|B) \): Posterior probability of A given B  
- \( P(B|A) \): Likelihood of B given A  
- \( P(A) \): Prior probability of A  
- \( P(B) \): Total probability of B

---

### 🧠 Example (Bayes):

If a test for a disease is 99% accurate, and the disease affects 1 in 1000 people, what is the probability that a person who tested positive actually has the disease?

Use Bayes’ Theorem to find out!

---


## Monte carlo estimation
Repeatedly simulating an experiment independently gives better result. 
using two steps
1. Generate a large number of tosses and 
2. count the number of heads or tails. 
you will notice that the probability is close to 0.5
A good result of $P(A)$ is:
$$P(A) \approx \frac{N_A}{N}$$
i.e the more you perform the simulation the accurate the result

