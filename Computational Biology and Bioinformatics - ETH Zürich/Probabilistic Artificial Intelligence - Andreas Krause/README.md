# Probabilistic Artificial Intelligence (2023)

## Course Overview
This advanced course explores the development of intelligent systems capable of operating in uncertain environments without explicit rules. It focuses on building systems that can learn and improve from experience, combining concepts from statistics, optimization, planning, and control.

## Useful Resources

### Student Resources & Cheat Sheets
- [Comprehensive PAI Cheat Sheet][pai-cheat] - Detailed summary of course concepts
- [ETH Probabilistic AI Solutions][pai-solutions] - Project implementations and notes
- [Serena Bono's PAI Cheat Sheet][bono-cheat] - Concise summary with key formulas
- [Visual PAI Cheat Sheet][visual-cheat] - Visual approach to course concepts

### Additional Learning Materials
- [Niklas Stoehr's Resources][stoehr] - Supplementary learning materials
- [Distill.pub][distill] - Visual explanations of machine learning concepts

### Topic-Specific Tutorials

#### Bayesian Methods
- [Bayesian Linear Regression & Gaussian Processes][blr-gp] - Detailed tutorial with examples

#### Variational Inference
- [Machine Learning: Variational Inference][vi-guide] - Comprehensive guide
- [Understanding Variational Inference][vi-practical] - Practical approach
- [MCMC and Variational Inference][mcmc-vi] - Comparison and implementation

#### Information Theory
- [Visual Information Theory][visual-info] - Visual explanations of key concepts
- [Guide to Mutual Information][mutual-info] - Detailed conceptual explanation

## Target Audience
- Upper-level undergraduate students
- Graduate students
- Prerequisites: Strong background in mathematics and programming recommended

## Course Structure

### 1. Foundations of Probabilistic AI
The course begins with fundamental concepts that serve as building blocks for more advanced topics. The introduction provides essential context about uncertainty in AI systems and how probabilistic approaches can address real-world challenges. This module builds intuition about why probabilistic methods are crucial in modern AI systems.

### 2. Mathematical Frameworks

#### Bayesian Methods
Bayesian Linear Regression forms the cornerstone of probabilistic modeling in the course. This section introduces powerful Bayesian inference concepts that help understand uncertainty in predictions. The mathematical rigor here is significant, but the practical implementations help solidify the concepts. The assignments involve implementing these methods from scratch, providing valuable hands-on experience.

#### Gaussian Processes
One of the most challenging but rewarding sections of the course. Gaussian Processes (GPs) are explored in depth across two weeks, covering both basic and advanced concepts. The first week focuses on GP fundamentals and kernel methods, while the second week delves into more sophisticated applications. The programming exercises with GPs are particularly enlightening, showing how they can model complex functions with uncertainty estimates.

#### Advanced Statistical Methods
The course takes a deep dive into Variational Inference and MCMC methods. These topics are mathematically intensive but are presented with clear practical applications. The programming assignments help understand how these methods work in practice, particularly for cases where exact inference is intractable.

### 3. Modern Machine Learning

#### Bayesian Deep Learning
This section bridges classical Bayesian methods with modern deep learning. It addresses how to quantify uncertainty in neural networks, a crucial aspect for real-world applications. The assignments involve implementing Bayesian neural networks, which provides valuable insights into modern probabilistic machine learning.

#### Active Learning
Active learning introduces strategies for efficient data collection and model improvement. This section is particularly relevant for real-world applications where data labeling is expensive. The concepts are reinforced through practical exercises involving query strategy implementation.

### 4. Reinforcement Learning
The final third of the course covers reinforcement learning, progressing from foundational concepts to state-of-the-art methods. The material becomes increasingly complex but builds logically from basic MDPs to advanced model-based methods. This section ties together many previous concepts and shows how probability theory underlies modern RL.

## Examination

### Project Experience
The projects were the most time-consuming part of the course. Each project took approximately 20-25 hours to complete, even when working in groups. The project templates were well-structured, though the requirements could sometimes be unclear. 

### Exam Reflection
The final exam was quite challenging, focusing heavily on theoretical understanding. The paper-based format was comprehensive but time-pressured. Having a strong grasp of the mathematical foundations was crucial. The questions were creative and required deep understanding rather than memorization. Practice with past exam questions was essential for preparation. While difficult, the exam fairly represented the course material, though the reinforcement learning questions were particularly challenging.

<!-- Reference Links -->
[pai-cheat]: https://github.com/andbloch/eth-pai-cheat-sheet
[pai-solutions]: https://github.com/alextimans/eth-probabilistic-ai
[bono-cheat]: https://github.com/serenabono/Cheat-Sheets-ETH/blob/main/PAI-CheatSheet.pdf
[visual-cheat]: https://github.com/walkerchi/ETHz-Probabilistic-Artificial-Intelligence-CheatSheet
[stoehr]: https://niklas-stoehr.com/resources/
[distill]: https://distill.pub/
[blr-gp]: https://jonathan-hui.medium.com/bayesian-linear-regression-gaussian-process-with-normal-distribution-e686f7846ad1
[vi-guide]: https://jonathan-hui.medium.com/machine-learning-variational-inference-273d8e6480bb
[vi-practical]: https://fabiandablander.com/r/Variational-Inference.html
[mcmc-vi]: https://towardsdatascience.com/bayesian-inference-problem-mcmc-and-variational-inference-25a8aa9bce29
[visual-info]: https://colah.github.io/posts/2015-09-Visual-Information/#fn4
[mutual-info]: https://medium.com/swlh/a-deep-conceptual-guide-to-mutual-information-a5021031fad0
