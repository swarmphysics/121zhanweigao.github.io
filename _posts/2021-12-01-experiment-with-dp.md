---
layout: post
title:  "About the project: Experiment with Differential Privacy using IBM's Diffprivlib"
date:   2021-12-01 23:10:00
blurb: "About"
---
Under IBM India's Global Remote Mentoring Program, I participated in an open-source project on 'Experimenting with Differential Privacy using IBM's Diffprivlib' between September 2020 - August 2021.

### Table of Contents

1. [About](#about)
    * [Background](#about)
    * [Our Contributions](#our-contributions)
2. [Important Links](#important-links)

### About

**Guides**
- Ms. Seetha Subramaniam, IBM
- Ms. Deepshikha Sinha, IBM
- Prof. Ashutosh Muchrikar, CCEW

**Teammates**
- Atmaja Jape, CCEW
- Tanya Sikarwar, CCEW
<br />

#### Background

Differential privacy addresses the paradox of learning nothing about an individual while learning useful information about a population. Essentially, it is a definition that formalizes the idea that a query should not reveal whether any one person is present in a dataset, much less what their data are.

Some important terms used in Differential Privacy -
1. Sensitivity
2. Privacy Loss
3. Privacy Budget
4. Mechanism

Refer [this section](#important-links) for more information on Differential Privacy.

#### Our Contributions

During the course of this project, we worked on the following -

* Extending the functionality of Diffprivlib

  Implemented the following differentially private statistical utilities and data visualization tools:
  * Percentiles
  * Median
  * Interquartile Range
  * Frequency Polygon
  * Bivariate Histogram

* Demonstrating privacy-preserving data analysis for real-world use cases

  Using the U.S. Census Bureau dataset, we performed a case study for analysing the algorithms.

* Promoting the use of IBM’s Open Source library, Diffprivlib, in an accessible manner

  Built a User Interface to expose our implementations using Python StreamLit.

  <img src="/assets/img/content/diffpriv/diffpriv.png" alt="bay" class="post-pic"/>

* Enabling data analysts to experiment, investigate and develop applications using differential privacy

  We performed an extensive empirical analysis of different percentile calculation methods, including our own extended Optimal Histogram method.
  <br />

We also presented our work to Security Division, IBM Bangalore. We also presented our work to Dr. Naoise Holohan, one of the leading developers of Diffprivlib. The feedback was amazing and it was very fulfilling to show our work to seniors from industry.

#### Important Links

1. [IBM Global Remote Mentoring Program](http://connecttobuild.in/)
2. [IBM's Diffprivlib](https://github.com/IBM/differential-privacy-library)
3. [The Definition of Differential Privacy, Cynthia Dwork](https://www.youtube.com/watch?v=lg-VhHlztqo)
4. [CS 860 - Algorithms for Private Data Analysis](http://www.gautamkamath.com/CS860-fa2020.html)
5. [The Algorithmic Foundations of Differential Privacy](https://www.cis.upenn.edu/~aaroth/Papers/privacybook.pdf)
