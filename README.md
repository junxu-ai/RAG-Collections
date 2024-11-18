# [WIP] RAG-Collections
This is a summarized collection of RAG papers, tutorials, tools, applications and databases from multiple repositories with latest update. 

# Existing Repositories

|Repository|Papers|Workshops/Tutorials|Tools|Applications|Database|
|---------------------|------------------|-------------------|----------------------|--------------|-----|
|[Awesome-LLM-RAG](https://github.com/jxzhangjhu/Awesome-LLM-RAG)  ![GitHub Repo stars](https://img.shields.io/github/stars/jxzhangjhu/Awesome-LLM-RAG?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/jxzhangjhu/Awesome-LLM-RAG)](https://github.com/jxzhangjhu/Awesome-LLM-RAG)|Yes*|Yes*| | |  |
|[*Awesome-RAG](https://github.com/frutik/Awesome-RAG) ![GitHub Repo stars](https://img.shields.io/github/stars/frutik/Awesome-RAG?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/frutik/Awesome-RAG)](https://github.com/frutik/Awesome-RAG)|Yes| Yes* |Partial|partial| |
|[awesome-rag](https://github.com/coree/awesome-rag) ![GitHub Repo stars](https://img.shields.io/github/stars/coree/awesome-rag?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/coree/awesome-rag)](https://github.com/coree/awesome-rag) |Yes| Yes |Partial|| |
|[Awesome-LLM-with-RAG](https://github.com/WangRongsheng/Awesome-LLM-with-RAG) ![GitHub Repo stars](https://img.shields.io/github/stars/WangRongsheng/Awesome-LLM-with-RAG?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/WangRongsheng/Awesome-LLM-with-RAG)](https://github.com/WangRongsheng/Awesome-LLM-with-RAG)|Yes| Partial ||| |
|[*RAG-Survey](https://github.com/Tongji-KGLLM/RAG-Survey)![GitHub Repo stars](https://img.shields.io/github/stars/Tongji-KGLLM/RAG-Survey?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/Tongji-KGLLM/RAG-Survey)](https://github.com/Tongji-KGLLM/RAG-Survey)|Yes*| Yes* |Partial|| |
|[*OpenRAG Base](https://openrag.notion.site/Open-RAG-c41b2a4dcdea4527a7c1cd998e763595) |Yes*| Yes* |Yes|Yes*| |
|[Awesome-RAG](https://github.com/Danielskry/Awesome-RAG) ![GitHub Repo stars](https://img.shields.io/github/stars/Danielskry/Awesome-RAG?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/Danielskry/Awesome-RAG)](https://github.com/Danielskry/Awesome-RAG)|Yes*| Yes* |Yes| | Yes|
|[awesome-llm-reader](https://github.com/HITsz-TMG/awesome-llm-reader) ![GitHub Repo stars](https://img.shields.io/github/stars/HITsz-TMG/awesome-llm-reader?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/HITsz-TMG/awesome-llm-reader)](https://github.com/HITsz-TMG/awesome-llm-reader)|Yes|  ||| |
|[Awesome RAG](https://github.com/run-llama/awesome-rag) ![GitHub Repo stars](https://img.shields.io/github/stars/run-llama/awesome-rag?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/run-llama/awesome-rag)](https://github.com/run-llama/awesome-rag)|Yes|  ||| |
|[Awesome-RAG](https://github.com/lucifertrj/Awesome-RAG)![GitHub Repo stars](https://img.shields.io/github/stars/lucifertrj/Awesome-RAG?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/lucifertrj/Awesome-RAG)](https://github.com/lucifertrj/Awesome-RAG)|| Yes |Yes*|| |
|[awesome-papers-for-rag](https://github.com/gomate-community/awesome-papers-for-rag)![GitHub Repo stars](https://img.shields.io/github/stars/gomate-community/awesome-papers-for-rag?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/gomate-community/awesome-papers-for-rag)](https://github.com/gomate-community/awesome-papers-for-rag)|| Yes* ||| |
|[RAG-Survey](https://github.com/hymie122/RAG-Survey)![GitHub Repo stars](https://img.shields.io/github/stars/hymie122/RAG-Survey?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/hymie122/RAG-Survey)](https://github.com/hymie122/RAG-Survey)|| Yes* ||| |
|- [Awesome-RAG-Evaluation](https://github.com/YHPeter/Awesome-RAG-Evaluation)  ![GitHub Repo stars](https://img.shields.io/github/stars/YHPeter/Awesome-RAG-Evaluation?style=social) [![GitHub last commit](https://img.shields.io/github/YHPeter/Awesome-RAG-Evaluation)](https://github.com/YHPeter/Awesome-RAG-Evaluation) |Yes*|||Yes||

# Tools
## General LLM
- [LangChain](https://github.com/langchain-ai/langchain) ![GitHub Repo stars](https://img.shields.io/github/stars/langchain-ai/langchain?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/langchain-ai/langchain)](https://github.com/langchain-ai/langchain): It is a framework for developing applications powered by LLMs.It contains a versatile Python library that simplifies the development of applications involving LLMS and RAG implementations. It features a modular architecture, allowing developers to integrate various components such as retrieval systems and knowledge bases easily. One of its standout features is memory management, enabling models to maintain conversational context across interactions. LangChain supports a wide range of pre-trained models and offers seamless integration with structured databases and unstructured text data. 

- [Llamaindex](https://github.com/run-llama/llama_index) ![GitHub Repo stars](https://img.shields.io/github/stars/run-llama/llama_index?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/run-llama/llama_index)](https://github.com/run-llama/llama_index): it is a data framework for your LLM application. Building with LlamaIndex typically involves working with LlamaIndex core and a chosen set of integrations (or plugins). Its Python library is namespaced such that import statements which include core imply that the core package is being used. In contrast, those statements without core imply that an integration package is being used.
- [Haystack](https://haystack.deepset.ai/) ![GitHub Repo stars](https://img.shields.io/github/stars/deepset-ai/haystack?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/deepset-ai/haystack)](https://github.com/deepset-ai/haystack): It  is an open-source framework developed by Deepset for building end-to-end question-answering systems that utilize RAG techniques. It includes components for document stores, retrievers, and generators, allowing developers to create sophisticated applications that combine retrieval and generation capabilities efficiently. Haystack is particularly useful for creating applications that require in-depth natural language processing with substantial knowledge integration.
- [Hugging Face Transformers](https://huggingface.co/docs/transformers/index) ![GitHub Repo stars](https://img.shields.io/github/stars/huggingface/transformers?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/huggingface/transformers)](https://github.com/huggingface/transformers): This library provides a wide array of pre-trained models for various natural language processing tasks, including RAG implementations. Hugging Face Transformers supports both retrieval and generation tasks, allowing developers to leverage state-of-the-art language models easily. The library is highly extensible and integrates well with other tools and frameworks, making it a popular choice for building AI applications.
- [Semantic Kernel by Microsoft](https://github.com/microsoft/semantic-kernel) ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/semantic-kernel?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/microsoft/semantic-kernel)](https://github.com/microsoft/semantic-kernel): It is an open-source project developed by Microsoft, designed to facilitate the integration of LLMs with existing software applica-tions. The core idea behind Semantic Kernel is to provide a framework that allows de-velopers to easily create, orchestrate, and customize workflows around LLMs by utiliz-ing a variety of skills like prompt chaining, memory, and learning capabilities. The tool enables developers to embed LLM capabilities directly into their applications while maintaining flexibility and control. It is highly customizable and supports a modular approach, allowing users to combine different AI services and integrate seamlessly with other Microsoft tools like Azure AI and OpenAI. In essence, Semantic Kernel helps streamline LLM-based operations in enterprise or software development con-texts.

- [embedchain / mem0](https://github.com/mem0ai/mem0) ![GitHub Repo stars](https://img.shields.io/github/stars/mem0ai/mem0?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/mem0ai/mem0)](https://github.com/mem0ai/mem0): It enhances AI assistants and agents with an intelligent memory layer, enabling personalized AI interactions. Mem0 remembers user preferences, adapts to individual needs, and continuously improves over time, making it ideal for customer support chatbots, AI assistants, and autonomous systems. Mem0 leverages a hybrid database approach to manage and retrieve long-term memories for AI agents and assistants. Each memory is associated with a unique identifier, such as a user ID or agent ID, allowing Mem0 to organize and access memories specific to an individual or context.
- [GenAI Stack](https://github.com/docker/genai-stack) ![GitHub Repo stars](https://img.shields.io/github/stars/docker/genai-stack?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/docker/genai-stack)](https://github.com/docker/genai-stack)The GenAI Stack will get you started building your own GenAI application in no time: Langchain + Docker + Neo4j + Ollama.
- [AIConfig ](https://github.com/lastmile-ai/aiconfig) ![GitHub Repo stars](https://img.shields.io/github/stars/lastmile-ai/aiconfig?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/lastmile-ai/aiconfig)](https://github.com/lastmile-ai/aiconfig)  a framework that makes it easy to build generative AI applications for production. It manages generative AI prompts, models and model parameters as JSON-serializable configs that can be version controlled, evaluated, monitored and opened in a local editor for rapid prototyping. It allows you to store and iterate on generative AI behavior separately from your application code, offering a streamlined AI development workflow
<!-- - [Big Hummingbird](https://www.bighummingbird.com/) -->


## Specific RAG

- [RAGFlow](https://github.com/infiniflow/ragflow) ![GitHub Repo stars](https://img.shields.io/github/stars/infiniflow/ragflow?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/infiniflow/ragflow)](https://github.com/infiniflow/ragflow): It is an open-source framework built to streamline the development and deployment of RAG systems. It focuses on modularity and easy integration with a variety of data sources, including documents, images, and structured datasets. With RAGFlow, users can efficiently implement RAG pipelines, leveraging LLMs to provide grounded, context-aware responses by integrating external data sources. RAGFlow supports both cloud and on-premises deployments, making it flexible for various use cases.

- [GraphRAG By Microsoft](https://github.com/microsoft/graphrag)  ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/graphrag?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/microsoft/graphrag)](https://github.com/microsoft/graphrag): GraphRAG organizes information into interconnected graphs to enhance retrieval and context understanding in RAG systems. This graph-based approach helps capture the relationships between different pieces of infor-mation, leading to more accurate and relevant LLM responses. It is particularly useful for applications that require in-depth, structured retrieval, such as legal document analysis, scientific research, and knowledge management.

- [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm) ![GitHub Repo stars](https://img.shields.io/github/stars/Mintplex-Labs/anything-llm?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/Mintplex-Labs/anything-llm)](https://github.com/Mintplex-Labs/anything-llm) : It is a flexible framework that allows developers to create cus-tomized RAG systems by integrating various retrieval and generation components. This framework supports integration with multiple APIs and data sources, making it ideal for a wide range of applications, from small-scale projects to large enterprise-level systems. Its modular design enables developers to build dynamic pipelines tai-lored to specific use cases.

- [Cognita by TrueFoundry](https://www.truefoundry.com/cognita) ![GitHub Repo stars](https://img.shields.io/github/stars/truefoundry/cognita?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/truefoundry/cognita)](https://github.com/truefoundry/cognita): It is an open-source framework from designed to sim-plify the development and deployment of RAG systems. It provides a modular, API-driven architecture that supports customization and scalability, allowing users to handle large datasets efficiently. Key features include incremental indexing, multiple query handling, autoscaling, and support for various vector databases like Qdrant and embedding models from OpenAI and Cohere. Cognita also offers a user-friendly UI, making it suitable for both technical and non-technical users to experiment and deploy RAG systems. In addition, it uses Langchain/Llamaindex under the hood, which means we can always integrate the latest modules/functions from these two popular tools.  

- [Weaviate Verba](https://github.com/weaviate/Verba) ![GitHub Repo stars](https://img.shields.io/github/stars/weaviate/Verba?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/weaviate/Verba)](https://github.com/weaviate/Verba): An open-source RAG application designed to make RAG ac-cessible to users without extensive technical expertise. It features a user-friendly inter-face for customizing RAG pipelines and interacting with generated outputs. It can connect either locally with Ollama and Huggingface or through LLM providers such as Anthrophic, Cohere, and OpenAI.
- [FlashRAG](https://github.com/RUC-NLPIR/FlashRAG) ![GitHub Repo stars](https://img.shields.io/github/stars/RUC-NLPIR/FlashRAG?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/RUC-NLPIR/FlashRAG)](https://github.com/RUC-NLPIR/FlashRAG) a Python toolkit for the reproduction and development of Retrieval Augmented Generation (RAG) research. the toolkit includes 32 pre-processed benchmark RAG datasets and 15 state-of-the-art RAG algorithms.

- [AutoRAG](https://github.com/Marker-Inc-Korea/AutoRAG) ![GitHub Repo stars](https://img.shields.io/github/stars/Marker-Inc-Korea/AutoRAG?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/Marker-Inc-Korea/AutoRAG)](https://github.com/Marker-Inc-Korea/AutoRAG): This tool automatically identifies the best RAG pipeline for your specif-ic data and use case. With many RAG pipelines and modules available, manually test-ing them all is time-consuming and difficult. It simplifies this by automating the eval-uation of different module combinations, helping you quickly find the optimal solution based on your own evaluation data. Try it now to streamline your search for the best RAG pipeline.
- [llmware](https://github.com/llmware-ai/llmware) ![GitHub Repo stars](https://img.shields.io/github/stars/llmware-ai/llmware?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/llmware-ai/llmware)](https://github.com/llmware-ai/llmware): it provides a unified framework for building LLM-based applications (e.g, RAG, Agents), using small, specialized models that can be deployed privately, integrated with enterprise knowledge sources safely and securely, and cost-effectively tuned and adapted for any business process.
- [NeumAI by NeumTry](https://github.com/NeumTry/NeumAI) ![GitHub Repo stars](https://img.shields.io/github/stars/NeumTry/NeumAI?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/NeumTry/NeumAI)](https://github.com/NeumTry/NeumAI): NeumAI is an open-source AI framework designed to of-fer a user-friendly platform for building and deploying ML/ AI models. The focus of NeumAI is to simplify AI model development by providing intuitive tools that mini-mize the complexity of setting up training environments, managing data, and scaling machine learning operations. The framework is built to be accessible for both beginners and experienced developers, emphasizing easy-to-understand APIs and modular com-ponents. NeumAI supports deep learning models and offers features that help with model optimization, experiment tracking, and collaborative AI development. It is de-signed to be highly flexible and adaptable for various AI applications, from research to production environments.

- [beyondllm](https://github.com/aiplanethub/beyondllm) ![GitHub Repo stars](https://img.shields.io/github/stars/aiplanethub/beyondllm?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/aiplanethub/beyondllm)](https://github.com/aiplanethub/beyondllm): It offers an all-in-one toolkit for experimentation, evaluation, and deployment of RAG systems, simplifying the process with automated integration, customizable evaluation metrics, and support for various Large Language Models (LLMs) tailored to specific needs, ultimately aiming to reduce LLM hallucination risks and enhance reliability.
- [MindSQL](https://github.com/Mindinventory/MindSQL) ![GitHub Repo stars](https://img.shields.io/github/stars/Mindinventory/MindSQL?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/Mindinventory/MindSQL)](https://github.com/Mindinventory/MindSQL): It is a Python RAG Library designed to streamline the interaction between users and their databases using just a few lines of code. With seamless integration for renowned databases such as PostgreSQL, MySQL, and SQLite, MindSQL also extends its capabilities to major databases like Snowflake and BigQuery by extending the IDatabase Interface. This library utilizes LLM like GPT-4, Llama 2, Google Gemini, and supports knowledge bases like ChromaDB and Faiss.

## Evaluation
We can use the general frameworks, such as [Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/what-is-bedrock.html),  [Azure AI Studio](https://ai.azure.com/)  [Google's Vertex AI Studio](https://cloud.google.com/vertex-ai), [LangSmith](https://www.langchain.com/langsmith) and [TruLens](https://github.com/truera/trulens) and [DeepEval](https://github.com/confident-ai/deepeval), for the evaluations. Or we can customize our datasets, e.g., [SuperAnnotate](https://www.superannotate.com/blog/llm-evaluation-guide). Below are some dedicated tools for RAG.
- [Phoenix](https://github.com/Arize-ai/phoenix) ![GitHub Repo stars](https://img.shields.io/github/stars/Arize-ai/phoenix?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/Arize-ai/phoenix)](https://github.com/Arize-ai/phoenix) It is an open-source AI observability platform designed for experimentation, evaluation, and troubleshooting. It is vendor and language agnostic with out-of-the-box support for popular frameworks (🦙LlamaIndex, 🦜⛓LangChain, Haystack, 🧩DSPy) and LLM providers (OpenAI, Bedrock, and more).

- [TruLens](https://github.com/truera/trulens) ![GitHub Repo stars](https://img.shields.io/github/stars/truera/trulens?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/truera/trulens)](https://github.com/truera/trulens) A tool can systematically evaluate and track your LLM experiments. the core concepts behind TruLens include Feedback Functions, The RAG Triad, and Honest, Harmless and Helpful Evals.
- [ragas](https://github.com/explodinggradients/ragas)![GitHub Repo stars](https://img.shields.io/github/stars/explodinggradients/ragas?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/explodinggradients/ragas)](https://github.com/explodinggradients/ragas) Ragas is a framework that helps you evaluate your RAG pipelines.Dedicated solutions to evaluate, monitor and improve performance of LLM & RAG application in production including custom models for production quality monitoring
- [CRUD_RAG](https://github.com/IAAR-Shanghai/CRUD_RAG) ![GitHub Repo stars](https://img.shields.io/github/stars/IAAR-Shanghai/CRUD_RAG?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/IAAR-Shanghai/CRUD_RAG)](https://github.com/IAAR-Shanghai/CRUD_RAG)  This project fully supports the Chinese RAG system evaluation, which includes native Chinese datasets, evaluation tasks, and baseline models; It covers CRUD (Create, Read, Update, Delete) operations, which are used to evaluate the RAG system's ability to add, reduce, correct information, as well as to answer questions based on the retrieve information;
- [RGB](https://github.com/chen700564/RGB)  ![GitHub Repo stars](https://img.shields.io/github/stars/chen700564/RGB?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/chen700564/RGB)](https://github.com/chen700564/RGB) An implementation for Benchmarking Large Language Models in Retrieval-Augmented Generation [arxiv](https://arxiv.org/abs/2309.01431)
- [ARES](https://github.com/stanford-futuredata/ARES)  ![GitHub Repo stars](https://img.shields.io/github/stars/stanford-futuredata/ARES?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/stanford-futuredata/ARES)](https://github.com/stanford-futuredata/ARES) ARES is a groundbreaking framework for evaluating Retrieval-Augmented Generation (RAG) models. The automated process combines synthetic data generation with fine-tuned classifiers to efficiently assess context relevance, answer faithfulness, and answer relevance, minimizing the need for extensive human annotations. ARES employs synthetic query generation and Prediction-Powered Inference (PPI), providing accurate evaluations with statistical confidence.
- [ALCE](https://github.com/princeton-nlp/ALCE) ![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/ALCE?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/princeton-nlp/ALCE)](https://github.com/princeton-nlp/ALCE) This repository contains the code and data for paper Enabling Large Language Models to Generate Text with Citations (https://arxiv.org/abs/2305.14627). In this paper, ALCE, a benchmark for Automatic LLMs' Citation Evaluation, is proposed. ALCE contains three datasets: ASQA, QAMPARI, and ELI5. it provides automatic evaluation code of LLM generations around three dimensions: fluency, correctness, and citation quality. This repository also includes code to reproduce the baselines in the paper.

- [RAG Evaluator](https://github.com/AIAnytime/rag-evaluator) ![GitHub Repo stars](https://img.shields.io/github/stars/AIAnytime/rag-evaluator?style=social) [![GitHub last commit](https://img.shields.io/github/last-commit/AIAnytime/rag-evaluator)](https://github.com/AIAnytime/rag-evaluator): It is a Python library for evaluating Retrieval-Augmented Generation (RAG) systems. It provides various metrics to evaluate the quality of generated text against reference text.




