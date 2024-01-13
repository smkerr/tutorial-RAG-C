# Retrieval Augmented Generation with Citation (RAG+C) Tutorial

This tutorial offers a step-by-step guide on how to implement Retrieval Augmented Generation with Citation (RAG+C) to address the challenge of knowledge management in government. In essence, RAG+C provides LLMs with additional contextual information through an external data base, which significantly improves response accuracy and avoids hallucinations, particularly on highly domain-specific topics. After showcasing the enhanced performance of RAG+C on a toy example related to coffee prices in Berlin Mitte, this tutorial's focus is the development of a chatbot to answer questions on the U.S. Federal Acquisition Regulation (FAR), the rule book for public procurement issuance in the United States. You will learn how to load and process FAR documents, store them in a data base and build your very own RAG-pipeline. To validate model performance, we leverage a FAR-quiz commonly used for training government employees, which allows us to compare responses from a standard LLM to the RAG+C enhanced LLM. Lastly, this tutorial will show you how to deploy your model as a Conversation User Interface (CUI) on a web server.

An important aspect of this tutorial is its commitment to open-source accessibility, ensuring that all models and frameworks employed are available to everyone. Moreover, the tutorial is designed with computational efficiency in mind. Unlike the resource-heavy process of fine-tuning LLMs, the methods and applications showcased can be comfortably executed on standard laptops. Overall, the tutorial is designed to provide users with clear understanding and a hands-on policy application of how LLM can be augmented to improve their reliability, relevance and privacy conformity, without the need to fall back to paid LLM solutions. 

Additionally, you can access our "FAR-Chat" on HuggingFace Spaces [here](https://huggingface.co/spaces/smkerr/rag-chat). Explore the repository and its files, especially the adapted Python application [here](https://huggingface.co/spaces/smkerr/rag-chat/tree/main).

**Authors:**

*   Kai Foerster, [k.foerster@students.hertie-school.org](mailto:k.foerster@students.hertie-school.org)
*   Steve Kerr, [s.kerr@students.hertie-school.org](mailto:s.kerr@students.hertie-school.org)
*   Amin Oueslati, [a.oueslati@students.hertie-school.org](mailto:a.oueslati@students.hertie-school.org)

<a href="https://colab.research.google.com/github/smkerr/tutorial-rag-c/blob/main/Tutorial_RAG_C.ipynb" target="_parent">
<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" width="200px"/></a>
