# Azure_NLPSolutions
In this repo, we briefly review NLP and its various techniques. We then comprehensively provide the links of Microsoft Azure solutions for each type of technique.

# Understanding NLP
Natural Language Processing (NLP) (also known as Neuro Linguistic Programming) is a field of artificial intelligence, machine learning, and the computational linguistics. Its sub-domains includes: **natural language understanding**, **machine translation**, **semantics** , **the syntactic passing**, **natural language emulation**, **dialectal systems** such as speech recognition, question & answering and a broad range of **text analytics techniques** such as classification, summarization, ranking and generation tasks. 

## Knowledge Extraction 
Knowledge extraction also known as (Information Extraction (IE)) is one of the main techniques of NLP which is the task of automatically extracting knowledge from structured/semi-structured (XML, RDF, HTML) documnets or unstructured (text, images, speech) resources. This task can be done at different lingustice levels.  


Microosft Azure  Cloud solutions for knowledge exraction tasks offer two types of solutions: 

### 1. Pre_built solution for extracting knowledge:
Azure Cognitive Services are APIs, SDKs, and services available to help developers build intelligent applications without having direct AI or data science skills or knowledge. Azure Cognitive Services enable developers to easily add cognitive features into their applications. The goal of Azure Cognitive Services is to help developers create applications that can see, hear, speak, understand, and even begin to reason.The catalog of services within Azure Cognitive Services can be categorized into five main pillars - Vision, Speech, Language, Web Search, and Decision.

- [Microstf docs resource API access](https://docs.microsoft.com/en-us/azure/cognitive-services/Welcome#feedback)  

Below is the official repositories for some of the services published by Microsoft: 

- [Project page for Cognitive Services offerings and demos](https://azure.microsoft.com/en-us/services/cognitive-services/)
- [Free trial access key link](https://azure.microsoft.com/en-us/try/cognitive-services/)
- [Cognitive Services Java SDK samples](https://github.com/Azure-Samples/cognitive-services-java-sdk-samples)
- [Cognitive Services Node.js SDK samples](https://github.com/Azure-Samples/cognitive-services-node-sdk-samples)
- [Cognitive Services Python SDK samples](https://github.com/Azure-Samples/cognitive-services-python-sdk-samples)

- [Cognitive Services Speech SDK](https://github.com/Azure-Samples/cognitive-services-speech-sdk)
- [Cognitive-services-REST-api-samples](https://github.com/Azure-Samples/cognitive-services-REST-api-samples)
- [Azure Cognitive TTS Samples](https://github.com/Azure-Samples/Cognitive-Speech-TTS)

- [Computer Vision Recipes](https://github.com/microsoft/computervision-recipes)

- [Language Understanding (LUIS)](https://github.com/Azure-Samples/cognitive-services-language-understanding)

	
### 2. Advanced Knowledge Mining solutions:
These solutions are designed for advanced knowlege mining tasks, such as Name Entity Recognition, Phrase Extraction, Custom labeling and Custom skills, where can enrich the IE porcess. 
- [Azure Cognitive Search Accelerator](https://github.com/microsoft/azure-search-knowledge-mining)
- [Form Recognizer Recipes](https://github.com/microsoft/knowledge-extraction-recipes-forms)

## Language Models
Building a language models are the most advanced NLP tasks, such as **word embedding**, **classification**, **summarization**, **document similarities** are implemented by deep learning techniques. Azure cloud currently does not have the full-support for such techniques,

### 1. Deep Learning jupyter notebooks solutions: 
Microsoft research has published a repository contains examples and best practices for building NLP systems, provided as Jupyter notebooks and utility functions. The focus of the repository is on state-of-the-art methods and common scenarios that are popular among researchers and practitioners working on problems involving text and language.  
 - [Microsoft NLP Recipes](https://github.com/microsoft/nlp-recipes)
