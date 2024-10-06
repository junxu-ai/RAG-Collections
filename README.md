# [WIP] RAG-Collections
This is a summarized collection of RAG papers, tutorials, tools, applications and databases from multiple repositories with latest update. 

# Existing Repositories

|Repository|Papers|Workshops/Tutorials|Tools|Applications|Database|
|---------------------|------------------|-------------------|----------------------|--------------|-----|
|[Awesome-LLM-RAG](https://github.com/jxzhangjhu/Awesome-LLM-RAG)|Yes|Yes| | |  |
|[*Awesome-RAG](https://github.com/frutik/Awesome-RAG)|Yes|  |Partial|partial| |
|[awesome-rag](https://github.com/coree/awesome-rag)|Yes| Yes |Partial|| |
|[Awesome-LLM-with-RAG](https://github.com/WangRongsheng/Awesome-LLM-with-RAG)|Yes| Partial ||| |
|[*RAG-Survey](https://github.com/Tongji-KGLLM/RAG-Survey)|Yes| Yes |Partial|| |
|[*OpenRAG Base](https://openrag.notion.site/Open-RAG-c41b2a4dcdea4527a7c1cd998e763595)|Yes| Yes |Yes|Yes| |
|[Awesome-RAG](https://github.com/Danielskry/Awesome-RAG)|Yes| Yes |Yes| | Yes|
|[awesome-llm-reader](https://github.com/HITsz-TMG/awesome-llm-reader)|Yes|  ||| |
|[Awesome RAG](https://github.com/run-llama/awesome-rag)|Yes|  ||| |
|[Awesome-RAG](https://github.com/lucifertrj/Awesome-RAG)|| Yes |Yes|| |



# Tools
## General LLM
- [LangChain](https://python.langchain.com/): It is a framework for developing applications powered by LLMs.It contains a versatile Python library that simplifies the development of applications involving LLMS and RAG implementations. It features a modular architecture, allowing developers to integrate various components such as retrieval systems and knowledge bases easily. One of its standout features is memory management, enabling models to maintain conversational context across interactions. LangChain supports a wide range of pre-trained models and offers seamless integration with structured databases and unstructured text data. 

- [Llamaindex](https://github.com/run-llama/llama_index): it is a data framework for your LLM application. Building with LlamaIndex typically involves working with LlamaIndex core and a chosen set of integrations (or plugins). Its Python library is namespaced such that import statements which include core imply that the core package is being used. In contrast, those statements without core imply that an integration package is being used.
- [Haystack](https://haystack.deepset.ai/): It  is an open-source framework developed by Deepset for building end-to-end question-answering systems that utilize RAG techniques. It includes components for document stores, retrievers, and generators, allowing developers to create sophisticated applications that combine retrieval and generation capabilities efficiently. Haystack is particularly useful for creating applications that require in-depth natural language processing with substantial knowledge integration.
- [Hugging Face Transformers](https://huggingface.co/docs/transformers/index): This library provides a wide array of pre-trained models for various natural language processing tasks, including RAG implementations. Hugging Face Transformers supports both retrieval and generation tasks, allowing developers to leverage state-of-the-art language models easily. The library is highly extensible and integrates well with other tools and frameworks, making it a popular choice for building AI applications.
- [Semantic Kernel by Microsoft](https://github.com/microsoft/semantic-kernel): It is an open-source project developed by Microsoft, designed to facilitate the integration of LLMs with existing software applica-tions. The core idea behind Semantic Kernel is to provide a framework that allows de-velopers to easily create, orchestrate, and customize workflows around LLMs by utiliz-ing a variety of skills like prompt chaining, memory, and learning capabilities. The tool enables developers to embed LLM capabilities directly into their applications while maintaining flexibility and control. It is highly customizable and supports a modular approach, allowing users to combine different AI services and integrate seamlessly with other Microsoft tools like Azure AI and OpenAI. In essence, Semantic Kernel helps streamline LLM-based operations in enterprise or software development con-texts.

## Specific RAG

- [RAGFlow](https://github.com/infiniflow/ragflow) : It is an open-source framework built to streamline the development and deployment of RAG systems. It focuses on modularity and easy integration with a variety of data sources, including documents, images, and structured datasets. With RAGFlow, users can efficiently implement RAG pipelines, leveraging LLMs to provide grounded, context-aware responses by integrating external data sources. RAGFlow supports both cloud and on-premises deployments, making it flexible for various use cases.

- [GraphRAG By Microsoft](https://github.com/microsoft/graphrag)  : GraphRAG organizes information into interconnected graphs to enhance retrieval and context understanding in RAG systems. This graph-based approach helps capture the relationships between different pieces of infor-mation, leading to more accurate and relevant LLM responses. It is particularly useful for applications that require in-depth, structured retrieval, such as legal document analysis, scientific research, and knowledge management.

- [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm)  : It is a flexible framework that allows developers to create cus-tomized RAG systems by integrating various retrieval and generation components. This framework supports integration with multiple APIs and data sources, making it ideal for a wide range of applications, from small-scale projects to large enterprise-level systems. Its modular design enables developers to build dynamic pipelines tai-lored to specific use cases.

- [Cognita by TrueFoundry](https://www.truefoundry.com/cognita): It is an open-source framework from designed to sim-plify the development and deployment of RAG systems. It provides a modular, API-driven architecture that supports customization and scalability, allowing users to handle large datasets efficiently. Key features include incremental indexing, multiple query handling, autoscaling, and support for various vector databases like Qdrant and embedding models from OpenAI and Cohere. Cognita also offers a user-friendly UI, making it suitable for both technical and non-technical users to experiment and deploy RAG systems. In addition, it uses Langchain/Llamaindex under the hood, which means we can always integrate the latest modules/functions from these two popular tools.  

- [Weaviate Verba](https://github.com/weaviate/Verba): An open-source RAG application designed to make RAG ac-cessible to users without extensive technical expertise. It features a user-friendly inter-face for customizing RAG pipelines and interacting with generated outputs. It can connect either locally with Ollama and Huggingface or through LLM providers such as Anthrophic, Cohere, and OpenAI.

- [AutoRAG](https://github.com/Marker-Inc-Korea/AutoRAG): This tool automatically identifies the best RAG pipeline for your specif-ic data and use case. With many RAG pipelines and modules available, manually test-ing them all is time-consuming and difficult. It simplifies this by automating the eval-uation of different module combinations, helping you quickly find the optimal solution based on your own evaluation data. Try it now to streamline your search for the best RAG pipeline.

- [NeumAI by NeumTry](https://github.com/NeumTry/NeumAI): NeumAI is an open-source AI framework designed to of-fer a user-friendly platform for building and deploying ML/ AI models. The focus of NeumAI is to simplify AI model development by providing intuitive tools that mini-mize the complexity of setting up training environments, managing data, and scaling machine learning operations. The framework is built to be accessible for both beginners and experienced developers, emphasizing easy-to-understand APIs and modular com-ponents. NeumAI supports deep learning models and offers features that help with model optimization, experiment tracking, and collaborative AI development. It is de-signed to be highly flexible and adaptable for various AI applications, from research to production environments.





