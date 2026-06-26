---
title: Journal paper - 'Towards a Semantics-Based Recommendation System for Cultural Heritage Collections'
date: 2026-06-26 17:55:00 +0100
categories: [Publications]
tags: [Graph Database, Recommendation System, Cultural Heritage, Linked Data, Digital Humanities]
---

The paper [**"Towards a Semantics-Based Recommendation System for Cultural Heritage Collections"**](https://www.mdpi.com/2076-3417/13/15/8907) was published in August, 2023. It introduces an architecture of recommentation system for cultural heritage resources.

The system (the architecture) was developend on *Neo4j*, a (probably the most popular) graph database platform, with the algorithms provided by Neo4j via *Graph Data Science Library*. All codes (in cypher, the query langugage for Neo4j) and the example dataset (open linked dataset) are provided in the paper.

The system is designed for users who have specific interests in items but struggle to conduct highly accurate searches—often due to the vocabulary difference between search keywords and semantic labels.

It operates on semantics-based resources with well-annotated topic labels. In this paper, for example, we use a dataset consisting of paintings annotated with topics like flora or bird.

How the recommendation loop works:

- Capture: The system assumes users will view at least one painting. It captures the semantic topics related to that viewed painting, treating them as the user's implicit browsing interest.

- Recommend: The system automatically recommends more paintings related to the captured topics, assisting in reducing the labour of manual searching. As users view more paintings, their interests (represented by the topics related to the viewed paintings) are updated with corresponding algorithm, which contributes to new recommentations for them.

The paper was adapted from my dissertation at MSc Digital Humanities, UCL. I'd say it is an immature work in terms of my understanding of fields such as semantic technologies, information searching and recommendation system. 

From a humanities background, my journey of (very basic) programming and engineering began with that master programme. I conducted this research with an enthusiasm to "build something by my hands" for the first time, For all technical work I did for this study, you can find official tutorials from Neo4j. 

Importantly, this work would not be possible without the guidance and support of my supervisor (the second author of the paper)!

The paper is open access at [here](https://www.mdpi.com/2076-3417/13/15/8907). (I may come later to add a PDF viewer here!)
