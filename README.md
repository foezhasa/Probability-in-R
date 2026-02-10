Quantitative Methods in Political Science – Homework 2

Author: Fatih Özhasar
Course: Quantitative Methods in Political Science
Deadline: September 22, 2022

This repository contains the full solution to Homework 2, which introduces core concepts in probability theory and statistical reasoning using R. The assignment combines theoretical definitions with hands-on implementation and visualization of probability distributions.

📦 Project Structure and Setup

The analysis is implemented in an R Markdown (.Rmd) file that can be rendered to HTML or PDF.

Dependencies

Only one external package is used:

viridis (for color-blind friendly plots)

The setup chunk automatically:

checks whether required packages are installed,

installs missing packages if necessary,

and loads them into the session.

This ensures the code runs reproducibly on any machine without manual setup.

📘 Part 1: Definitions

This part provides concise theoretical answers to foundational concepts in probability:

Random variables (with discrete and continuous examples from political science)

Interpretation of probability as long-run relative frequency

No code is used in this section; it focuses on conceptual understanding.

📊 Part 2: Probability in R

This section introduces basic probability distributions and their behavior through visualization.

Topics covered:

Normal distribution (PDF and CDF)

Standard normal distribution

Binomial distribution (PMF and CDF)

Comparison of fair vs. biased coins

Key skills demonstrated:

Use of dnorm(), pnorm(), dbinom(), and pbinom()

Choosing appropriate plotting ranges and labels

Distinguishing between density functions and cumulative distribution functions

All plots are generated using base R, with viridis used for consistent coloring.

🗳️ Part 3: Answering Probabilistic Questions

This part applies probability theory to a substantive political science example:
forecasting the vote share of the Green Party.

Main tasks:

Simulating a sample from a normal distribution (mean = 18, sd = 3)

Estimating probabilities and percentages based on the simulated sample

Comparing individual outcomes to sample means

Interpreting percentiles and confidence ranges

The section highlights the difference between:

theoretical probabilities (using pnorm() / qnorm()), and

sample-based quantities (using simulated data).

⚖️ Part 4: Applied Probability

This section applies the binomial distribution to a real-world example:
the selection of jurors in the O.J. Simpson trial.

Concepts illustrated:

Probability of at least one success

Probability of at least two successes

Importance of random and independent sampling assumptions

Correct use of the binomial distribution (pbinom) is emphasized, along with a short conceptual explanation.

✅ Learning Outcomes

By completing this homework, the project demonstrates:

Understanding of probability distributions and their interpretation

Ability to visualize and simulate stochastic processes in R

Correct distinction between densities, probabilities, and cumulative probabilities

Application of probabilistic reasoning to political science questions

Reproducible and well-documented statistical analysis
