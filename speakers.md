---
title: Speakers
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: single
classes: wide
author_profile: false
---


speakers:
- image_path: assets/images/manuela.jpg
     alt: "Manuela M. Veloso"
     title: "Manuela M. Veloso"
     excerpt: |
         Head of J.P. Morgan AI Research & Herbert A. Simon University Professor in the School of Computer Science at Carnegie Mellon University
         ### Provable Representation Learning
         Deep representation learning seeks to learn a data representation that transfers to downstream tasks. In this talk, we study two forms of representation learning: supervised pre-training and self-supervised learning.
         
<!-- #         Supervised pre-training uses a large labeled source dataset to learn a representation, then trains a classifier on top of the representation. We prove that supervised pre-training can pool the data from all source tasks to learn a good representation which transfers to downstream tasks with few labeled examples. -->


<!-- 
# contributed:
#   - image_path: assets/images/andrew_stolman.jpg
#     alt: "Andrew Stolman"
#     title: "Andrew Stolman"
#     excerpt: |
#         KatanaGraph
#         ### Studying the (in)-effectiveness of graph embeddings
#         The introduction of graph embedding techniques such as Node2Vec has led to a number of new architectures for various graph-based machine learning tasks. Although this has generated many exciting new results, there has been little principled investigation into the fundamental limits of these methods. We investigate some potential limitations of popular embedding methods as they pertain to real world graphs. Real graphs are often sparse, and yet they exhibit a high density of triangles and community structure. We show that a class of embedding methods cannot satisfyingly represent such sparse, triangle-dense graphs. We complement this theoretical result with an analysis of how this effects performance on the downstream tasks of community detection and link prediction by comparing the performance of unsupervised state-of-the-art embedding techniques against simpler non-embedding based models. -->
---
<br/>

## Invited Speakers

<section class="invited-speakers">
{% include feature_row id="speakers" type="left" %}
</section>


<!-- <section class="invited-speakers">
{% include feature_row id="contributed" type="left" %}
</section> -->



