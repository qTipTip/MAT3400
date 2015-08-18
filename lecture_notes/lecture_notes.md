---
title: Lecture notes in MAT3400 - Linear Analysis
author: Ivar Stangeby
---

# Lecture summaries

## August 18th

We started with an outline of the course. It is divided into two "sections", namely
*measure and integration theory* and *linear analysis*.

Starting off we discussed the *Riemann integral* and some of its pros and cons. 
This was ment as a motivator for the integration theory developed in the course.

The Riemann integral works well for continuous functions, in other words, it is
computable in a lot of cases. It is *additive* meaning that we can split the
interval into finitely many subintervals and preserve the integral. It is
*monotone* in the sense that if a function $g$ dominates $f$ on an interval,
then the integral of $g$ dominates the integral of $f$ on the same interval.

The drawbacks of the Riemann integral is that it requires functions to be
bounded, and still, not all bounded functions can be integrated. An example is
the characteristic function on the set of rational numbers $\mathbb{Q}$.  In
addition to this, the integral need not preserve limits. If we have a sequence
of functions $f_n$ converging to a limit function $f$, then the sequence of
integrals of $f_n$ does not neccessarily converge to the integral of the limit
function $f$.

If we look at a metric involving the Riemann integral on the space of
continuous functions from $a$ to $b$, the metric space we achieve is _not_
complete!

The theory of integration we are to develop, namely the *Lebesgue integration*,
aims to fix all of these problems.

Some motivation regarding the second part of the course was also presented.
Linear maps between various vector spaces constitues the base line for pretty
much all the theory. What happens when the vector spaces we are considering are
infinite dimensional?

Some basic set theory was covered, some notational convention as well as a lot
of material from the course on real analysis.

We want to generalize the notion of length of an interval, and the crucial step
is to assign a *measure/size* to larger collections of subsets of $\mathbb{R}$.
We defined what an *algebra* is and listed some consequences and properties of
these. We considered the *largest* and *smallest* algebras of subsets of sets
$\Omega$ containing a specific collection of subsets.

We also defined what a *$\sigma$-algebra* is and listed some of its properties.
It looks a lot like any other algebra. An example was given of a sigma algebra,
one that is very important - namely the *Borel $\sigma$-algebra* on
$\mathbb{R}$. Its essentially just a collection of open sets in $\mathbb{R}$.

We gave a plan on how to introduce this new notion of the *size* of a set.
Starting with the *Lebesgue outer measure*, we restrict it to the class
$\mathcal{M}$ of measurable sets and obtain a proper measure.
