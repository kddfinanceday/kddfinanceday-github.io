---
title: Speakers
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: single
classes: wide
author_profile: false

# speakers:
#   - image_path: assets/images/jason_lee.jpeg
#     alt: "Jason Lee"
#     title: "Jason Lee"
#     excerpt: |
#         Princeton
#         ### Provable Representation Learning
#         Deep representation learning seeks to learn a data representation that transfers to downstream tasks. In this talk, we study two forms of representation learning: supervised pre-training and self-supervised learning.
        
#         Supervised pre-training uses a large labeled source dataset to learn a representation, then trains a classifier on top of the representation. We prove that supervised pre-training can pool the data from all source tasks to learn a good representation which transfers to downstream tasks with few labeled examples.
        
#         Self-supervised learning creates auxiliary pretext tasks that do not require labeled data to learn representations. These pretext tasks are created solely using input features, such as predicting a missing image patch, recovering the color channels of an image, or predicting missing words. Surprisingly, predicting this known information helps in learning a representation effective for downstream tasks. We prove that under a conditional independence assumption, self-supervised learning provably learns representations.

#   - image_path: assets/images/yasaman_bahri.png
#     alt: "Yasaman Bahri"
#     title: "Yasaman Bahri"
#     excerpt: |
#         Google Brain
#         ### Understanding Neural Scaling Laws
#         The test loss of neural networks has empirically been found to follow power laws as a function of basic variables such as model size and training set size. I will discuss our work connecting and explaining some of these scaling laws. We introduce “variance-limited” and “resolution-limited” scaling regimes to distinguish the origin of the behavior. The variance-limited scaling regime follows simply from the existence of a well-behaved infinite data or infinite width limit, while the resolution-limited regime can be explained by positing that models are effectively resolving a smooth data manifold. In the setting of kernel models, I'll discuss how this can be equivalently obtained from the kernel spectrum. Finally, I’ll close with a few interesting empirical observations about task properties and scaling exponents.
#   - image_path: assets/images/dawn_song.png
#     alt: "Dawn Song"
#     title: "Dawn Song"
#     excerpt: |
#         UC Berkley
#         ### Building towards a Responsible Data Economy
#         Data is a key driver of modern economy and AI/machine learning, however, a lot of this data is sensitive and handling the sensitive data has caused unprecedented challenges for both individuals and businesses. These challenges will only get more severe as we move forward in the digital era. In this talk, I will talk about technologies needed for responsible data use including secure computing, differential privacy, federated learning, as well as blockchain technologies for data rights, and how to combine privacy computing technologies and blockchain to building a platform for a responsible data economy, to enable more responsible use of data that maximizes social welfare & economic efficiency while protecting users’ data rights and enable fair distribution of value created from data.
#   - image_path: assets/images/eric_xing.png
#     alt: "Eric Xing"
#     title: "Eric Xing"
#     excerpt: |
#         Zayed University of Artificial Intelligence (MBZUAI)/Petuum/CMU
#         ### It is time for deep learning to understand its expense bills
#         In the past several years, deep learning has dominated both academic and industrial R&D over a wide range of applications, with two remarkable trends: 1) developing and training ever larger “all-purpose” monster models over all data possibly available, with a whopping 10,000x parameter number increase in recent 3 years; 2) developing and assembling end-to-end “white-boxes” deployments with ever larger number of component sub-models that need to be highly customized and interoperative. Progresses made to the leaderboards or featured in news headlines are highlighting metrics such as saliency of content production, accuracy on labeling, or speed of convergence, but a number of key challenges impacting the cost effectiveness of such results, and eventually the sustainability of current R&D efforts in DL, are not receiving enough attention: 1) For large models, how many lines of code outside of the DL model are need to parallelize the computing over a computer cluster? (2) Which/How many hardware resources to use to train and deploy the model? (3) How to tune the model, the code, and the system to achieve optimum performance? (4) Can we automate composition, parallelization, tuning, and resource sharing between many users and jobs? In this talk, I will discuss these issues as a core focus in SysML research, and I will present some preliminary results on how to build standardizable, adaptive, and automatable system support for DL based on first principles (when available) underlying DL design and implementation.
#   - image_path: assets/images/deepak_agarwal.png
#     alt: "Deepak Agarwal"
#     title: "Deepak Agarwal"
#     excerpt: |
#         Pinterest
#         ### Deep learning to power user engagement on Pinterest
#         Pinterest is a leading social media platform that provides users with inspirational ideas to improve their lifestyle. The ecosystem on the platform is powered by large scale content recommendations, search, product recommendations and online advertising. With nearly half a billion monthly active users and 10s of billions of content, it presents a unique technical challenge to industrialize modern deep learning methods at scale. In this talk, I will talk about the deep learning methods that have worked well for Pinterest and how we operate them at scale while providing enough flexibility for ML practitioners to continuously innovate and improve the system.

#         Bio: Deepak Agarwal is currently a senior engineering leader at Pinterest where he leads the engineering teams responsible for developing all organic user experiences on the platform including recommendations, search and shopping.

#         Prior to Pinterest, Deepak was VP engineering and Head of Artificial Intelligence at LinkedIn from 2012-2020. He began his industrial research career with AT&T Labs from 2001-2006 and subsequently was a senior researcher at Yahoo! Research from 2006-2012.
#         He has published extensively in top-tier conferences/journals in CS, ML and Statistics and has written a textbook on Recommender Systems. He is Fellow of the American Statistical Association, serves as member of Executive Committee for SIGKDD and regularly serves on program committees of major CS and ML conferences.
#   - image_path: assets/images/martin_watternberg.png
#     alt: "Martin Wattenberg"
#     title: "Martin Wattenberg"
#     excerpt: |
#         Google PAIR/Harvard CS
#         ### Visualization for Human and Machine Learning
#         One of the strengths of data visualization is its ability to challenge our own assumptions and add nuance to our thinking. I will present examples of data visualization that do exactly this, and then talk about applications of these ideas to machine learning interpretability. A key focus will be ways that geometric thinking can shed light on how neural networks process natural language.
#   - image_path: assets/images/james_zou.png
#     alt: "James Zou"
#     title: "James Zou"
#     excerpt: |
#         Stanford
#         ### A data-centric view of trustworthy AI
#         What's the data used to train and evaluate deployed AI systems? Is the data sufficient to achieve reliable performance, or do they introduce biases? We survey the data behind important AI algorithms, including FDA-approved medical AI devices, and quantify several key limitations. Motivated by these challenges, I will discuss recent advances in improving trustworthy AI by leveraging unlabeled data and data valuation, which quantifies how specific data contribute to the performance or bias of the AI model.
#   - image_path: assets/images/besmira_nushi.jpeg
#     alt: "Besmira Nushi"
#     title: "Besmira Nushi"
#     excerpt: |
#         Microsoft Research
#         ### On Debugging Machine Learning Models and Systems: Challenges, Myths, Tools
#         As Artificial Intelligence is becoming part of user-facing applications and directly impacting society, deploying AI reliably and responsibly has become a priority for academia and industry leaders. Rigorous model evaluation and debugging are at the heart of responsible machine learning development. However, evaluation and debugging still remain challenging due to lack of tooling, complexities of dealing with a large amount of data and parameters, distributional shifts, and the long tail of potential failures that may happen in deployed systems. At the same time, there exist several challenges in adopting recommended evaluation and debugging practices and tools at a large scale.
 
#         This talk will summarize learnings on challenges, myths, and tools that we have distilled over the last past years while assisting Machine Learning teams in the process of model\system debugging and improvement. We will talk about examples of tools that we have deployed as part of the Machine Learning infrastructure, show how they can accelerate the process and identify current gaps that would be interesting research avenues for the future. At the same time, the talk will also include a discussion about how current practices in industry and academia could be rethought to adjust for more rigorous evaluation and informed improvement.
#   - image_path: assets/images/aleksander_madry.png
#     alt: "Aleksander Madry"
#     title: "Aleksander Madry"
#     excerpt: |
#         MIT
#         ### Why Do ML Models Fail?
#         Our current machine learning models achieve impressive performance on many benchmark tasks. Yet, these models remain remarkably brittle and susceptible to manipulation.
        
#         Why is this the case?

#         In this talk, we take a closer look at this question, and pinpoint some of the roots of this observed brittleness. Specifically, we discuss how the way current ML models “learn” and are evaluated gives rise to widespread vulnerabilities, and then outline possible approaches to alleviate these deficiencies.


# contributed:
#   - image_path: assets/images/andrew_stolman.jpg
#     alt: "Andrew Stolman"
#     title: "Andrew Stolman"
#     excerpt: |
#         KatanaGraph
#         ### Studying the (in)-effectiveness of graph embeddings
#         The introduction of graph embedding techniques such as Node2Vec has led to a number of new architectures for various graph-based machine learning tasks. Although this has generated many exciting new results, there has been little principled investigation into the fundamental limits of these methods. We investigate some potential limitations of popular embedding methods as they pertain to real world graphs. Real graphs are often sparse, and yet they exhibit a high density of triangles and community structure. We show that a class of embedding methods cannot satisfyingly represent such sparse, triangle-dense graphs. We complement this theoretical result with an analysis of how this effects performance on the downstream tasks of community detection and link prediction by comparing the performance of unsupervised state-of-the-art embedding techniques against simpler non-embedding based models.
#   - image_path: assets/images/Daniel.jpg
#     alt: "Daniel Kang"
#     title: "Daniel Kang"
#     excerpt: |
#         Stanford
#         ### Monitoring and Quality Assurance of Complex ML Deployments via Assertions
#         ML is increasingly being deployed in complex situations by teams. While much research effort has focused the training and validation stages, other parts have been neglected by the research community. In this talk, I'll describe two abstractions (model assertions and learned observation assertions) that allow users to input domain knowledge to find errors at deployment time and in labeling pipelines. I'll show real-world errors in labels and ML models deployed in autonomous vehicles, visual analytics, and ECG classification that these abstractions can find. I'll further describe how they can be used to improve model quality by up to 2x at a fixed labeling budget. Work is joint with researchers from Stanford University and Toyota Research Institute.
 
#         Bio: Daniel Kang is a fifth year PhD student in the Stanford DAWN lab, co-advised by Professors Peter Bailis and Matei Zaharia. His research focuses on systems approaches for deploying unreliable and expensive machine learning methods efficiently and reliably. In particular, he focuses on using cheap approximations to accelerate query processing algorithms and new programming models for ML data management. Daniel is collaborating with autonomous vehicle companies and ecologists to deploy his research. His work is supported in part by the NSF GRFP and the Google PhD fellowship.
#   - image_path: assets/images/tianlong.jpg
#     alt: "Tianlong Chen"
#     title: "Tianlong Chen"
#     excerpt: |
#         UT Austin
#         ### The lottery ticket hypothesis for gigantic pre-trained models
#         In NLP and computer vision, enormous pre-trained models have become the standard starting point for training on a range of downstream tasks. In parallel, work on the lottery ticket hypothesis has shown that models contain smaller matching subnetworks capable of training in isolation to full accuracy and transferring to other tasks. We have combined these observations to assess whether such trainable, transferrable subnetworks exist in various pre-trained models. Taking BERT as one example, for a range of downstream tasks, we indeed find matching subnetworks at 40% to 90% sparsity. We find these subnetworks at (pre-trained) initialization, a deviation from prior NLP research where they emerge only after some amount of training. As another example found in computer vision, from all pre-trained weights obtained by ImageNet classification, simCLR and MoCo, we are also consistently able to locate matching subnetworks at 59.04% to 96.48% sparsity that transfer to multiple downstream tasks, whose performance also see no degradation compared to using full pre-trained weights. As large-scale pre-training becomes an increasingly central paradigm in deep learning, our results demonstrate that the main lottery ticket observations remain relevant in this context.
 
#         Bio: Tianlong Chen is a third-year PhD student at University of Texas at Austin. He is under the supervision of Prof. Zhangyang (Atlas) Wang. His research mainly lies in building accurate, robust, reliable, efficient, automatic machine learning systems, and recent focus is extreme sparse neural networks with undamaged trainability, expressivity, and transferability. He is a recipient of IBM PhD Fellowship. His 30+ research papers are published in various top conferences such as NeurIPS, ICML, ICLR, CVPR, ICCV, ECCV, etc.
#   - image_path: assets/images/Harman.jpg
#     alt: "Harmanpreet Kaur"
#     title: "Harmanpreet Kaur"
#     excerpt: |
#         UMichigan
#         ### Interpreting Interpretability: Understanding Data Scientists’ Use of Interpretability Tools for Machine Learning
#         Machine learning (ML) models are now routinely deployed in domains ranging from criminal justice to healthcare. With this newfound ubiquity, ML has moved beyond academia and grown into an engineering discipline. To that end, interpretability tools have been designed to help data scientists and machine learning practitioners better understand how ML models work. However, there has been little evaluation of the extent to which these tools achieve this goal. In this talk, I will present results from our study of data scientists’ use of two existing interpretability tools, the InterpretML implementation of GAMs and the SHAP Python package. We conducted a contextual inquiry and a survey with data scientists to observe how they use interpretability tools to uncover common issues that arise when building and evaluating ML models. Our results indicate that data scientists over-trust and misuse interpretability tools. Furthermore, few of our participants were able to accurately describe the visualizations output by these tools. Looking ahead, I will discuss the importance of helping data scientists’ form accurate mental models of interpretability tools, and present implications for researchers and tool designers.
 
#         Bio: Harman Kaur is a PhD candidate in both the department of Computer Science and the School of Information at the University of Michigan, where she is advised by Eric Gilbert and Cliff Lampe. Her research interests lie in human-AI collaboration and interpretable ML. Specifically, she studies interpretability tools from a human-centered perspective and designs solutions to support the bounded nature of human rationality in the context of ML-based decision-support systems. She has published several papers at top-tier human-computer interaction venues, such as CHI, CSCW, and IUI. Her work has won Best Paper Honorable Mention awards at CHI and IUI. She has also completed several internships at Microsoft Research and the Allen Institute for AI.
#   - image_path: assets/images/Arun.JPG
#     alt: "Arun Kumar"
#     title: "Arun Kumar"
#     excerpt: |
#         UC San Diego
#         ### Some Damaging Delusions of Deep Learning Practice (and How to Avoid Them)
#         This is not a talk by "DL researchers." In fact, we are "outsiders" to the DL/ML world, having never published a full paper at NeurIPS, ICLR, ICML, or KDD! So, what do we have to say and why speak here? We are data systems researchers interested in helping "democratize" DL, specifically from the usability and scalability standpoints. This talk will critically expound and reflect on a set of damaging delusions we see in the DL world on these fronts, from both the ML modeling and systems standpoints. Specifically, I will call out delusional propaganda that discounts the importance of rigorous model selection, as well as magical thinking over automated ML and transfer learning. I will then critique some banal and oversimplified approaches in the ML systems world for allegedly scaling DL that discounts holistic resource efficiency, playing into the hands of greedy cloud whales. As a case study of combating all these delusions, I will share our experiences with building and using Cerebro, a first-of-its-kind model selection-first platform for scalable DL that is inspired by design principles and techniques from the world of database systems.
 
#         Bio: Arun Kumar is an Assistant Professor in the Department of Computer Science and Engineering and the Halicioglu Data Science Institute and an HDSI Faculty Fellow at the University of California, San Diego. He is a member of the Database Lab and Center for Networked Systems and an affiliate member of the AI Group. His primary research interests are in data management and systems for machine learning/artificial intelligence-based data analytics. Systems and ideas based on his research have been released as part of the Apache MADlib open-source library, shipped as part of products from Cloudera, IBM, Oracle, and Pivotal, and used internally by Facebook, Google, LogicBlox, Microsoft, and other companies. He is a recipient of two SIGMOD research paper awards, a SIGMOD Research Highlight Award, three distinguished reviewer awards from SIGMOD/VLDB, the PhD dissertation award from UW-Madison CS, the IEEE TCDE Rising Star Award, an NSF CAREER Award, a Hellman Fellowship, a UCSD oSTEM Faculty of the Year Award, and research award gifts from Amazon, Google, Oracle, and VMware.
#   - image_path: assets/images/david.jpg
#     alt: "David Madras"
#     title: "David Madras"
#     excerpt: |
#         UToronto
#         ### Why Learn Fair Representations?
#         Recently, rising levels of concern around the harmful impacts of automated systems combined with rapid progress in tools for machine learning has led to increased interest in the topic of "fair representation learning". In this talk, I will unpack the motivations behind this subfield, how some recent approaches address them, and their relationships to other subfields of machine learning. I will additionally discuss the central challenges of fair representation learning, as well as detail promising directions by which future work might approach these challenges.
 
#         Bio: David Madras is a PhD student in the Machine Learning group at the University of Toronto and the Vector Institute. His research focuses on the learning and evaluation of automated decision-making systems, including their fairness and robustness, as well as the role of humans in those systems. He is currently a graduate fellow at the Schwartz Reisman Institute for Technology and Society, and was co-organizer of the Participatory Approaches to Machine Learning 2020 workshop, and organizer and program chair of the Pan-Canadian Self-Organizing Conference on Machine Learning (SOCMLx) 2019.
#   - image_path: assets/images/saket_gurukar.jpg
#     alt: "Saket Gurukar"
#     title: "Saket Gurukar"
#     excerpt: |
#         OSU
#         ###  Unsupervised Network Representation Learning and the Illusion of Progress
#         Abstract:  A number of methods have been developed for network representation learning -- ranging from classical methods based on the graph spectra to recent random walk based methods and from deep learning based methods to matrix factorization based methods. Each new study inevitably seeks to establish the relative superiority of the proposed method over others. The lack of a standard assessment protocol and benchmark suite often leave practitioners wondering if a new idea represents a significant scientific advance.
 
#         In this work, we articulate a clear and pressing need to systematically and rigorously benchmark such methods. Our overall assessment -- a result of a careful benchmarking of 13 methods for unsupervised network representation learning on 16 datasets (several with different characteristics) - is that many recently proposed improvements are somewhat of an illusion. Specifically, we find that several recent improvements are marginal at best and that aspects of many of these datasets often render such small differences insignificant, especially when viewed from a rigorous statistical lens.
 
#         Bio: Saket Gurukar is a Ph.D. candidate in CSE Department at The Ohio State University. His research interests include Network Representation Learning and Recommendation Systems. He has published papers in top conferences and has filed three US Patents. He has worked at IBM Research Labs, India as a Research Software Engineer and has completed his master's in computer science from Indian Institute of Technology, Madras.
# ---
# <br/>

## Invited Speakers

<!-- <section class="invited-speakers">
{% include feature_row id="speakers" type="left" %}
</section> -->

<br/>

# Contributed Speakers

<!-- <section class="invited-speakers">
{% include feature_row id="contributed" type="left" %}
</section> -->



