# Generative AI on Google Cloud with LangChain

<a href="https://www.packtpub.com/en-us/product/generative-ai-on-google-cloud-with-langchain-9781835889336"><img src="https://m.media-amazon.com/images/I/81C2ZcI-sdL._SL1500_.jpg" alt="Generative AI on Google Cloud with LangChain" height="256px" align="right"></a>

This is the code repository for [Generative AI on Google Cloud with LangChain](https://www.packtpub.com/en-us/product/generative-ai-on-google-cloud-with-langchain-9781835889336), published by Packt.

**Design scalable generative AI solutions with Python, LangChain, and Vertex AI on Google Cloud**


## What is this book about?

This book provides expert guidance for building scalable, enterprise-ready applications with Google Cloud's generative AI. You will also learn to harness Vertex AI and LangChain for text generation, summarization, and question answering.

This book covers the following exciting features: 
* Build enterprise-ready applications with LangChain and Google Cloud
* Navigate and select the right Google Cloud generative AI tools
* Apply modern design patterns for generative AI applications
* Plan and execute proof-of-concepts for enterprise AI solutions
* Gain hands-on experience with LangChain’s and Google Cloud’s AI products
* Implement advanced techniques for text generation and summarization
Leverage Vertex AI Search and other tools for scalable AI solutions

If you feel this book is for you, get your [copy](https://www.amazon.com/Generative-Google-Cloud-LangChain-generative/dp/B0DKT8DCRT/ref=sr_1_1?sr=8-1) today!


## Instructions and Navigations
All of the code is organized into folders.

The code will look like the following:
```python
from langchain_core.runnables import RunnablePassthrough
chain_rps = RunnableParallel(
    origin=RunnablePassthrough(),
    output=increment_by_one
)
chain_rps.invoke(1)
```

**Following is what you need for this book:**
If you’re an application developer or ML engineer eager to dive into GenAI, this book is for you. Whether you're new to LangChain or Google Cloud, you'll learn how to use these tools to build scalable AI solutions. This book is ideal for developers familiar with Python and machine learning basics looking to apply their skills in GenAI. Professionals who want to explore Google Cloud's powerful suite of enterprise-grade GenAI products and their implementation will also find this book useful.

With the following software and hardware list you can run all code files present in the book (Chapter 1-13).

### Software and Hardware List

| Chapter  | Software required                                                                    | OS required                        |
| -------- | -------------------------------------------------------------------------------------| -----------------------------------|
|  	1-13	   | LangSmith (free tier)                              | Windows, macOS, or Linux and ChromeOS |
|  	1-13	   | Vertex AI API on Google Cloud                              |  |
|  	1-13	   | A custom Google Search enabled and a Google Cloud API key                              |  |
|  	1-13	   | Vertex Vector Search, Vertex Agent Builder               |  |
|  	1-13	   | LangSmith (free tier)                 |  |


### Related products <Other books you may enjoy>  
* Modern Generative AI with ChatGPT and OpenAI Models  [[Packt]](https://www.packtpub.com/en-us/product/modern-generative-ai-with-chatgpt-and-openai-models-9781805123330) [[Amazon]](https://www.amazon.com/dp/1805123335)

* ChatGPT for Cybersecurity Cookbook [[Packt]](https://www.packtpub.com/en-us/product/chatgpt-for-cybersecurity-cookbook-9781805124047) [[Amazon]](https://www.amazon.com/dp/1805124048)
  
## Get to Know the Author
**Leonid Kuligin** is an active contributor to LangChain and the author of the many Google Cloud integrations on LangChain. He has been building complex tech products for almost 20 years, developing intense data and Machine Learning applications. Leonid has a degree in Applied Mathematics and Physics, and a degree in Finance. Since 2023, he has been working with key Google Cloud customers on various generative AI initiatives.

**Dr. Maximilian Tschochohei** leads AI Engineering at Google Cloud Consulting EMEA and is responsible for implementing AI applications for Google Cloud customers. He brings insights into LangChain Before joining Google, he spent many years of experience in strategy and technology consulting with the Boston Consulting Group.

**Jorge Zaldivar** is an AI Engineer at Google and also a contributor to LangChain’s integrations with Google. He has a decade of experience building complex Machine Learning applications and products applied to the energy and financial industries.
