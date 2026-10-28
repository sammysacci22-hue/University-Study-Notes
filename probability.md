# Probability

## 1. Definition of Probability

Probability is a measure of how likely an event is to occur.

The probability of an event lies between 0 and 1.

* A probability of 0 means the event is impossible.
* A probability of 1 means the event is certain.
* A probability between 0 and 1 represents varying degrees of likelihood.

## 2. Basic Probability Formula

When all outcomes are equally likely:

$$
P(A) = \frac{\text{Number of favourable outcomes}}{\text{Total number of possible outcomes}}
$$

Where:

* \(P(A)\) is the probability that event A occurs.
* Favourable outcomes are the outcomes that satisfy the event.
* Total possible outcomes are all outcomes in the sample space.

## 3. Important Terms

### Experiment

A process that produces an outcome.

Example: Tossing a coin.

### Sample Space

The set of all possible outcomes of an experiment.

Example: When tossing a coin:

$$
S = \{H,T\}
$$

### Event

A set of outcomes of interest.

Example: Getting a head when tossing a coin.

$$
A = \{H\}
$$

### Complement of an Event

The complement of A consists of all outcomes in the sample space that are not in A.

The probability of the complement is:

$$
P(A^c) = 1-P(A)
$$

## 4. Worked Example

**Question:** A fair die is rolled once. Find the probability of obtaining an even number.

### Step 1: Identify the sample space

$$
S = \{1,2,3,4,5,6\}
$$

There are 6 possible outcomes.

### Step 2: Identify the favourable outcomes

The even numbers are:

$$
A = \{2,4,6\}
$$

There are 3 favourable outcomes.

### Step 3: Apply the formula

$$
P(A) = \frac{3}{6}
$$

Therefore:

$$
\boxed{P(A)=\frac{1}{2}=0.5}
$$

The probability of obtaining an even number is 0.5, or 50%.

## 5. Important Probability Rules

### Rule 1: Probability of the Entire Sample Space

$$
P(S)=1
$$

One of the outcomes in the sample space must occur.

### Rule 2: Probability of an Impossible Event

$$
P(\varnothing)=0
$$

An impossible event has probability zero.

### Rule 3: Complement Rule

$$
P(A^c)=1-P(A)
$$

Use this rule when it is easier to calculate the probability that an event does not occur.

### Rule 4: Addition Rule

For any two events A and B:

$$
P(A\cup B)=P(A)+P(B)-P(A\cap B)
$$

Here:

* \(P(A\cup B)\) is the probability that A or B occurs, or both.
* \(P(A\cap B)\) is the probability that both A and B occur.

If A and B are mutually exclusive, they cannot occur together. Therefore:

$$
P(A\cup B)=P(A)+P(B)
$$

## 6. Common Mistakes

* Forgetting to count all possible outcomes.
* Counting outcomes that do not satisfy the event as favourable outcomes.
* Assuming outcomes are equally likely when they are not.
* Confusing mutually exclusive events with independent events.
* Forgetting to subtract the intersection when applying the general addition rule.

## 7. Quick Revision Questions

**Question 1:** A fair coin is tossed once. What is the probability of obtaining a tail?

**Question 2:** A fair die is rolled once. What is the probability of obtaining a number greater than 4?

**Question 3:** If \(P(A)=0.35\), calculate \(P(A^c)\).

**Question 4:** Explain the difference between mutually exclusive events and independent events.

## 8. Progress

* [x] Create the probability notes.
* [ ] Complete the revision questions.
* [ ] Add more worked examples.
* [ ] Study conditional probability.
* [ ] Study Bayes' theorem.
