# Lesson 2 - Introduction to AI and Machine Learning

Get an overview of AI and machine learning and where they are used in industry. This lesson covers terminology and applications of supervised learning, unsupervised learning, and neural networks.

## What is AI?

### Quiz Question

Which of these applications use AI, which we'll define as a technology that can automatically learn to detect patterns in data? (Check ALL that apply.)

- [x] Siri
- Calculators
- [x] Netflix's recommendation system
- Refrigerators

> Great job! These two technologies use patterns in existing data to do things like recognize speech (Siri) and generate recommended movies (Netflix).

## 3: What Can AI Do?

- Speech recognition
    - challenged: noisy environments, accented speech, speaking styles and languages with limited training data, understanding speech
- Audio recognition
- NLP
    - filtering out hate speech, sentiment analysis

## 4: The AI Universe

Here is a graphic for reference when you are considering the different types of AI. Much like a square is a rectangle but a rectangle is not a square; many of these categories are refinements of the others.

![The AI Universe](../img/screen-shot-2019-05-28-at-4.33.23-pm.png)

> The term Ai is aspirational, a moving target based on those capabilities that humans possess but which machines do not. - Zachary Lipton, Assistant Professor at Carnegie Mellon

### Reflect

What characteristics does **deep learning** have, that traditional machine learning does not?

> Deep learning specifically refers to algorithms that use neural networks, which you'll learn more about, later in this lesson! This approach relies on vast amounts of data to work.

## 5: Why Deep Learning?

- can learn from much more data than previous ML approaches (siri, alexa)
- why is AI so relevant now? compute power, data availability, cost is low

## 6: Industry Applications

>  I think that AI technology, especially deep learning...has now advanced to the point where we see a surprisignly clear path for it to **transform every major indudstry** -- Andrew Ng

- Sectors with great potentials
    - retail:
    - consumer goods: supply-chain management, demand forecasting
    - finance:  marketing and sales, assessign and managing risk

## 7: Affecting Industry

- sense and decide: Blue river's AI indentifies subtle differences between crops and weeds

## 8: Machine Learning Concepts

What is Machine Learning?

> Computer algorithms that improve automatically through experience. - Tom Mitchel, CMU

- Supervised learning: classification, regression
- Unsupervised learning: clustering, association
- Reinforcement learning: Real-time, offline

## 9: Supervised Learning

## 10: Unsupervised Learning

## 11: Unsupervised vs Supervised

Supervised vs. Unsupervised Learning
------------------------------------

When you are thinking about using machine learning to solve a task, the type of algorithm you’ll use will generally depend on the data you are given. Before approaching a task, you should ask two questions: Does the data contain labels, such as true classes? Is the data continuous?

For example, if you are given images with true class labels, these labels indicate that you’ll likely use a supervised learning method that learns to associate patterns in the data with the given labels. This data is also discrete since there are a limited number of image classes. These two qualities: supervised learning and discrete data mean that you should use a classification algorithm to solve this task.

It may be helpful to consult the matrix below that addresses all kinds of data analysis cases.

*   **Discrete** data is data that you can count and it has a finite amount, say the number of image classes or clothing item types.
*   **Continuous** data is often numerical data that takes a large range of values.

![](https://video.udacity-data.com/topher/2019/May/5cedca5d_screen-shot-2019-05-28-at-4.54.58-pm/screen-shot-2019-05-28-at-4.54.58-pm.png)

### Quiz Question

What kind of algorithm should you use to estimate clothing prices? You can assume that you are given some training data about clothing prices; a single piece of data includes the price of a piece of clothing in dollars and cents, the material and color of the piece, and the clothing brand.

- [ ] Classification
- [x] Clustering
- [ ] Regression
- [ ] Dimensionality Reduction

> Great! Since the price data is continuous (in dollars and cents), and you have a known value that you want to estimate this is a supervised, regression task.

## 12: Reinforcement Learning

## 13: Neural Networkds

## 14: Current State of AI

- What can AI do well right now?
    - specific, narrow tasks
    - learning from large volumes of unstructured data
