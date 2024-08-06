# Demystifying the AI Black Box

## An Empirical Evaluation of Explainable AI Techniques in NLP Tasks Using Counterfactual Assessment

### Authors
- Pamela González Muñiz
- Joselo Peña Contreras
- Haoran Zheng

### Advisors
- Instructor: Utku Pamuksuz PhD
- Advisor: Ming-Long Lam PhD

### Institution
A Capstone Project Submitted to the University of Chicago in partial fulfillment of the requirements for the degree of Master of Science in Applied Data Science, Division of Physical Sciences, August 2024.

---

## Abstract
Explainable Artificial Intelligence (XAI) is crucial for enhancing the transparency and accountability of AI models, particularly in natural language processing (NLP) tasks. This paper evaluates the effectiveness of various XAI methods in text classification tasks across different model architectures, including Convolutional Neural Networks (CNNs), Recurrent Neural Networks (RNN), and BERT. We assess gradient-based approaches such as LIME and SHAP and backpropagation-based approaches like Integrated Gradients. Additionally, we propose a novel evaluation framework using counterfactual explanations employing Validitysoft and Csoft formulations. This framework provides insights into the strengths and limitations of XAI techniques without extensive fine-tuning. Our comparative analysis highlights the performance and applicability of XAI methods across diverse neural network architectures.

**Keywords:** Explainable Artificial Intelligence, Natural Language Processing, Text Classification, Perturbation, Counterfactual Explanation, Soft Counterfactual Evaluation Metrics.

---

## Executive Summary
This paper provides a review of explainable artificial intelligence (XAI) techniques specifically tailored for text data, a domain witnessing rapid growth in recent years. The study describes, categorizes, and tests XAI methods, offering a structured overview of the field. Through practical evaluations, this survey assesses the real-world efficacy of these methods. Such evaluations reveal the strengths and limitations of current XAI implementations, particularly in terms of their scalability and the balance they strike between accuracy and transparency. Key challenges in deploying XAI systems are identified, with emphasis on the need for scalable solutions that do not compromise explanatory depth for performance. The paper also addresses the lack of consensus on what constitutes an adequate explanation, which varies among different user groups. Looking forward, the paper introduces a novel approach (SCENE) to measure interpretability with the use of counterfactuals.

This survey serves as a critical resource for both researchers and practitioners interested in the application of XAI techniques to text data, providing them with a comprehensive framework to inform their approach and encouraging continued innovation in this essential area of artificial intelligence.

---




