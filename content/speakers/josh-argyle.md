---
draft: true
language: en
categories:
- speakers
title: "Josh Argyle"
job_title: "Lead Data Scientist"
company: "Freyda"
track: "data"
slot_length: 45
slot_Type: "talk"
slot_level: 1
slot_title: "Enhancing Retrieval-Augmented Generation for Financial Document Processing"
summary: "Enhancing Retrieval-Augmented Generation for Financial Document Processing"
contact:
-  text: LinkedIn
   url: https://www.linkedin.com/in/joshua-argyle/
bio:
- TBC
takeaways:
- An understanding Graph-based RAG for Financial Data
- An insight into how a startup has integrated LLMs into a live product
- A look forward onto the next stages of applied AI
---
Retrieval-Augmented Generation (RAG) systems excel in diverse natural language processing tasks, yet integrating graph-based models has been shown to significantly improve performance, especially in complex domains like finance.

We've developed a dynamic knowledge graph, specifically tailored for the financial domain, continuously evolving to capture the ever-changing landscape of financial concepts and relationships. This structured representation is then used to enhance the understanding of domain-specific terminology and semantics.

We employ a two-stage alignment process to go from query to answer. The initial alignment links broad concepts from the query to a document graph, using a blend of heuristic methods and graph neural networks. The refinement stage, inspired by semantic matching techniques, ensures detailed matching between query specifics and document elements, enhancing the accuracy of information retrieval. We then incorporate LLMs with the aim to extract and structure financial data accurately, adhering to user-defined output specifications.

The process involves multiple steps, each requiring specific data retrieval to build a coherent response—from query initiation to the final answer. User feedback is integral, continually refining our system's performance, enhancing the knowledge graph, and aligning the extracted information with user expectations.

By integrating graph-based models, knowledge representations, and language models, our approach significantly enhances the capabilities of traditional RAG systems. This technical overview will highlight how these innovations contribute to more accurate and efficient information retrieval and processing for financial data analysis.