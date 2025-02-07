# Python Notebook Tutorial Series: Complementing Medium Articles

Welcome to our Python Notebook Tutorial Series, designed to complement and expand upon various programming concepts introduced in Medium tutorials. Our aim is to provide you with hands-on experience and deeper insights into practical applications of advanced programming techniques.

## Tutorial 1: React Agents with dynamic Top_k function

This first notebook in the series focuses on the integration of React agents with a dynamic top _k function, based on "Llama Index Framework". It demonstrates how to enhance selection processes, making them more efficient and adaptable to dynamic conditions. This tutorial serves as a practical extension to the theoretical concepts discussed in the corresponding Medium article.

### What You Will Learn

- **Introduction to React Agents and the Llama Index Framework**: Gain an understanding of React agents, their significance in Python, and how they integrate within the Llama Index Framework for dynamic data handling.
- **Dynamic Top _k Function**: Dive into the top _k function's role in data selection and processing, and why it's crucial for optimizing performance in various applications.
- **Step-by-Step Implementation**: Follow a detailed guide on implementing React agents with a dynamic top _k function within your projects.


Each section is crafted to build upon the concepts introduced in the Medium article, providing you with a comprehensive understanding and the ability to implement these ideas in your own projects. By the end of this tutorial, you'll be equipped with a powerful toolset for data selection and processing tasks.

Stay tuned for more tutorials in this series, where we'll continue to explore and apply advanced programming concepts in practical, real-world scenarios.

### Prerequisites

Before diving into this notebook, make sure you have a basic understanding of Python and React. Familiarity with data processing concepts will also be helpful.

## Tutorial 2: Effortless Press Article Generation with BBC, ChatGPT, and Jinja

In this second tutorial, you'll learn how to effortlessly generate press articles by combining BBC web scraping, ChatGPT for rewriting, and a Jinja template for seamless formatting into a Word document. This practical guide builds upon the concepts introduced in the corresponding Medium article.

### What You Will Learn

- **Introduction to Web Scraping and ChatGPT Integration**: Understand the fundamentals of web scraping with the BBC RSS feed and how to integrate OpenAI's ChatGPT for rewriting articles.
- **Using a Jinja Template**: Learn how to create and customize a Jinja template that matches the JSON structure, enabling you to generate polished Word documents.
- **Step-by-Step Implementation**:
1. Extract Information from BBC: Scrape data using the RSS feed and process it into a structured format with Pandas.
2. Enrich Data with ChatGPT: Use prompts to enrich the scraped data with specific topics and rewrite the content in JSON format.
3. Format with a Jinja Template: Implement a Jinja template that matches the JSON structure for seamless formatting into a Word document.

### Prerequisites

Basic Python Knowledge and basic knowledge of web scraping using BeautifulSoup (BS4) will help you follow along more easily.

## Tutorial 3: Automating Table of Content Extraction and Filtering with LlamaIndex

In this tutorial, you'll learn how to automate the extraction of tables of contents from research papers and apply metadata filters for more accurate document retrieval using LlamaIndex. This tutorial builds on the concepts introduced in the corresponding Medium article.

### What You Will Learn

- **PDF to HTML Conversion**: Convert PDFs to HTML for cleaner data extraction.
- **Automated Table of Content Extraction**: Extract and assign section names from research papers automatically.
- **Metadata Filters**: Apply metadata filters to refine document retrieval, enhancing LLM accuracy.
- **Creating a Vector Store Index**: Build a vector store index and query it using metafilters for better information retrieval.

### Prerequisites

- Basic understanding of Python, web scraping, and data processing.
- Familiarity with large language models and Google Colab.

## Tutorial 4: Automating Table of Content Extraction and Filtering in Papers with LlamaIndex (Part 2)

This tutorial builds on the previous part, focusing on using metadata embeddings to enhance search capabilities within research papers, allowing for more accurate retrieval even with similar but different terms.

#### What You Will Learn:

- **Metafilters with Embeddings:** Improve document retrieval by embedding metadata and applying metafilters using OpenAI's embedding models.
- **Similarity Search Without Weights:** Perform searches based on metadata similarity without additional weighting.
- **Weighted Similarity and Normalization:** Apply custom weights to specific keywords to refine search results (e.g., prioritizing "Conclusion" sections).
- **Advanced Querying with Vector Store Index:** Create and use a vector store index for advanced queries with LlamaIndex.

#### Prerequisites:

- Basic knowledge of Python and machine learning.
- Familiarity with vector-based search techniques and large language models.


## Tutorial 5: Building an AI Real-Time Trading System with Kafka & LlamaIndex

In this tutorial, you'll create a real-time trading bot that uses Kafka for streaming EUR/USD bid-ask data, LlamaIndex workflows for seamless data handling, and GPT-4o for sophisticated decision-making. The bot can capture real-time bid-ask prices, analyze them, and make decisions such as buying, selling, or holding, forming a foundation for a more advanced AI trading system with future rebalancing potential.

### What You Will Learn

- **Real-Time Data Streaming with Kafka**: Set up Kafka to stream real-time bid-ask data from Investing.com for the EUR/USD currency pair.
- **Decision Making with LlamaIndex and GPT**: Build a workflow in LlamaIndex that uses GPT-4o for initial chart analysis and GPT-3.5 for trading decisions.
- **Step-by-Step Implementation**:
  1. **Download Daily EUR/USD Chart**: Use Selenium to capture a daily chart for initial analysis by GPT-4o.
  2. **Configure Kafka Data Stream**: Create a Kafka topic to collect and stream bid-ask data every 5 seconds.
  3. **Implement LlamaIndex Workflow**: Integrate LlamaIndex workflows that use technical indicators and GPT-3.5 to generate trading recommendations.


#### Prerequisites:

- Basic knowledge of Python and scraping techniques.
- Familiarity with real-time data streaming and large language models.


## Tutorial 6: Building an Industrial AI Chatbot with NeMo Guardrails and LlamaIndex 🚧🤖

In this tutorial, we demonstrate how to build a robust AI chatbot tailored for industrial applications, such as crane operations. By combining **NeMo Guardrails**, **LlamaIndex**, and **Docling**, this bot ensures accurate information retrieval, conversational flow management, and contextual relevance. We'll walk through parsing an industrial manual, creating a Retrieval-Augmented Generation (RAG) pipeline, and implementing custom conversation rules.

#### What You Will Learn 📘

- **Parsing Industrial Documents with Docling**: Extract structured text from PDF manuals and split it into manageable nodes.
- **Retrieval-Augmented Generation (RAG) with LlamaIndex**: Build a query engine that retrieves relevant technical information from indexed nodes.
- **Guardrails for Safe Conversations**: Implement NeMo Guardrails to moderate user inputs, validate outputs, and enforce conversational flow constraints.
- **Custom RAG Actions**: Learn to handle out-of-scope queries by escalating them to expert systems.

#### Step-by-Step Implementation ⚙️

1. **Prepare the Document**: Use **Docling** to parse and convert PDF manuals into structured Markdown content.
2. **Index and Retrieve with LlamaIndex**:
    - Split the parsed document into nodes.
    - Create a **vector store** to enable efficient retrieval.
    - Build a query engine and enhance relevance with a **SentenceTransformerRerank** model.
3. **Configure NeMo Guardrails**:
    - Define conversation flows using **Colang** for input moderation, dialogue rules, and output validation.
    - Set up custom Python actions, like escalating industrial queries beyond the chatbot's scope.
4. **Testing and Deployment**: Use test prompts to verify the chatbot's performance and adjust flows for real-world scenarios.


#### Prerequisites:

- Basic knowledge of Python and LlamaIndex.

-------------------------------------------------------------------------------------------------------------------------------------------

### Why Google Colab?

We recommend using **Google Colab** for running these notebooks for several reasons:
- **No Setup Required**: Google Colab provides a ready-to-use Python environment with most libraries pre-installed. Just click and go!
- **Accessibility**: Since Colab runs in the cloud, you can access your notebooks from any device, anytime, anywhere.
- **Free Resources**: Colab offers free access to computing resources, including GPUs, making it ideal for experiments and learning.

### Getting Started with Google Colab

1. Open the notebook link provided in each section.
2. Sign in with your Google account if prompted.
3. Click on "Open in Colab" at the top of the notebook.
4. You're now ready to run the cells! Follow the instructions within the notebook to proceed with the tutorial.

### Contributing

We encourage contributions! If you have improvements or additional examples, please feel free to submit a pull request or open an issue.

### License

[MIT License](https://opensource.org/licenses/MIT)

---

This series is intended for educational purposes and is not affiliated with Medium directly. All concepts and tutorials are inspired by articles published on Medium and are used here to provide practical programming experience.

