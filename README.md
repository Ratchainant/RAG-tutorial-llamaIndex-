# RAG-tutorial-llamaIndex-
This repository is created for hands-on practice in the classroom.  It is based on the [original documents of llamaIndex](https://docs.llamaindex.ai/en/stable/understanding/rag/)

> [!NOTE]
> If you haven't, [install LlamaIndex](https://docs.llamaindex.ai/en/stable/getting_started/installation/) and complete the [starter tutorial](https://docs.llamaindex.ai/en/stable/getting_started/starter_example/) before you read this. It will help ground these steps in your experience.

# Introduction to RAG

LLMs are trained on enormous bodies of data but they aren't trained on your data. Retrieval-Augmented Generation (RAG) solves this problem by adding **your** data to the data LLMs already have access to. You will see references to RAG frequently in this documentation. Query engines, chat engines and agents often use RAG to complete their tasks.

In RAG, your data is loaded and prepared for queries or "indexed". User queries act on the index, which filters your data down to the most relevant context. This context and your query then go to the LLM along with a prompt, and the LLM provides a response.

Even if what you're building is a chatbot or an agent, you'll want to know RAG techniques for getting data into your application.

![](/images/basic_rag.png)
