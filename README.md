# 🤖 GenAI Career Assistant

Are you aiming for a career in Generative AI? This project offers a personalized assistant to help you achieve your goals. Developed using LangChain and Large Language Models (LLMs), this `agent` is designed to guide you through every step of your career journey.

> **Important Note:** This application does not have a graphical user interface (GUI). All interactions are performed by running code cells within the provided Jupyter Notebook (`.ipynb`) file.
> ![Ekran görüntüsü 2025-07-07 123832](https://github.com/user-attachments/assets/29d7e973-59d3-410b-a196-aa9b003a7d6e)

## ✨ Key Features

### 📚 Learning & Content Creation
Offers tailored learning pathways in GenAI, covering key topics and skills. It also assists you in creating tutorials, blogs, and posts based on your interests or queries.


---

### 💬 Q&A Support
Provides on-demand Q&A sessions for when you need guidance on complex GenAI concepts or specific coding issues.


---

### 📄 Resume Building & Review
Offers one-on-one resume consultations and guidance. The assistant crafts personalized, market-relevant resumes that are optimized for current job trends to make your profile stand out.


---

### 🎙️ Interview Preparation
Hosts Q&A sessions on common and technical interview questions. It can also simulate real interview scenarios and conduct mock interviews to help you build confidence and prepare effectively.


---

### 🔍 Job Search Assistance
Guides you through the entire job search process, offering tailored insights and support to help you navigate the job market efficiently.


## 🚀 Getting Started

Follow these steps to run the GenAI Career Assistant on your local machine.

### Prerequisites
*   Python 3.8+
*   Jupyter Notebook or Jupyter Lab
*   An OpenAI API Key (or an API key from another LLM provider)

### Steps

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/hitaskomur/Carrier_Coach_Assistan_with_Langgraph-Agentic_AI-.git
    cd Carrier_Coach_Assistan_with_Langgraph-Agentic_AI-
    ```

2.  **Install the Required Libraries:**
    ```bash
    pip install langchain langchain-groq langgraph langchain-community IPython python-dotenv jupyter
    ```

3.  **Set Up Your API Key:**
    *   Add your API key to the file in the following format:
      ```
      OPENAI_API_KEY="your_api_key"
      ```

4.  **Run the Assistant:**
    *   Start Jupyter Notebook from your terminal:
      ```bash
      jupyter notebook main.py
      ```
    *   Open the notebook file in your browser. Run the code cells sequentially to interact with the assistant and start using its features.

---

**With the GenAI Career Assistant, your journey to a career in Generative AI becomes organized, personalized, and efficient!**

# ----------------------------------------------------------
# ----------------------------------------------------------
# Here is some examples of key features orderly :

## 📚 Learning & Content Creation : 
# Langchain and Langgraph Tutorial

Langchain and Langgraph are two powerful tools in the field of Natural Language Processing (NLP) that enable us to generate and manipulate language. In this tutorial, we will explore the concepts and usage of both Langchain and Langgraph, along with coding examples.

**Langchain**

Langchain is a Python library that allows us to generate and manipulate language by transforming and combining language inputs. It uses a novel approach called "language chaining" to generate text that is coherent, context-aware, and highly customizable.

**Concepts**

Here are some key concepts related to Langchain:

* **Language Chaining**: Langchain uses language chaining to generate text. This involves breaking down a language input into smaller units, such as phrases or sentences, and then combining them in a specific order to create a new text.
* **Language Patterns**: Langchain uses language patterns to identify and manipulate specific language structures, such as verb tenses, sentence structures, and word order.
* **Language Embeddings**: Langchain uses language embeddings to represent language inputs as vectors in a high-dimensional space. This allows it to capture subtle nuances in language and generate text that is more coherent and natural-sounding.

**Usage**

Here are some common use cases for Langchain:

* **Text Generation**: Langchain can be used to generate text based on a given input, such as a prompt or a set of rules.
* **Text Manipulation**: Langchain can be used to manipulate existing text, such as rewriting sentences or rephrasing paragraphs.
* **Language Translation**: Langchain can be used to translate text from one language to another.

**Coding Example**

Here is an example of how to use Langchain to generate text:
```
import langchain

# Create a Langchain instance
langchain_instance = langchain.Langchain()

# Define a language pattern for generating text
pattern = "The {adjective} {noun} jumped over the {adjective} {noun}."

# Define a set of language embeddings for the pattern
embeddings = {
    "adjective": ["happy", "sad", "angry"],
    "noun": ["dog", "cat", "house"]
}

# Generate text using the Langchain instance
text = langchain_instance.generate_text(pattern, embeddings)

print(text)
```
This code defines a language pattern and a set of language embeddings, and then uses the Langchain instance to generate text based on those inputs.

**Langgraph**

Langgraph is a Python library that allows us to generate and manipulate language by creating and traversing graphs of language concepts. It uses a novel approach called "language graphing" to generate text that is coherent, context-aware, and highly customizable.

**Concepts**

Here are some key concepts related to Langgraph:

* **Language Graphs**: Langgraph uses language graphs to represent language concepts as nodes and edges in a graph.
* **Language Embeddings**: Langgraph uses language embeddings to represent language inputs as vectors in a high-dimensional space. This allows it to capture subtle nuances in language and generate text that is more coherent and natural-sounding.
* **Graph Traversal**: Langgraph uses graph traversal algorithms to navigate the language graph and generate text based on the relationships between language concepts.

**Usage**

Here are some common use cases for Langgraph:

* **Text Generation**: Langgraph can be used to generate text based on a given input, such as a prompt or a set of rules.
* **Text Manipulation**: Langgraph can be used to manipulate existing text, such as rewriting sentences or rephrasing paragraphs.
* **Language Translation**: Langgraph can be used to translate text from one language to another.

**Coding Example**

Here is an example of how to use Langgraph to generate text:
```
import langgraph

# Create a Langgraph instance
langgraph_instance = langgraph.Langgraph()

# Define a language graph for generating text
graph = {
    "nodes": [
        {"id": "A", "label": "happy"},
        {"id": "B", "label": "sad"},
        {"id": "C", "label": "angry"},
        {"id": "D", "label": "dog"},
        {"id": "E", "label": "cat"},
        {"id": "F", "label": "house"}
    ],
    "edges": [
        {"from": "A", "to": "D", "label": "jumps over"},
        {"from": "B", "to": "E", "label": "jumps over"},
        {"from": "C", "to": "F", "label": "jumps over"}
    ]
}

# Define a set of language embeddings for the graph
embeddings = {
    "A": {"happy": 0.5, "sad": 0.3, "angry": 0.2},
    "B": {"happy": 0.3, "sad": 0.5, "angry": 0.2},
    "C": {"happy": 0.2, "sad": 0.3, "angry": 0.5},
    "D": {"dog": 0.5, "cat": 0.3, "house": 0.2},
    "E": {"dog": 0.3, "cat": 0.5, "house": 0.2},
    "F": {"dog": 0.2, "cat": 0.3, "house": 0.5}
}

# Generate text using the Langgraph instance
text = langgraph_instance.generate_text(graph, embeddings)

print(text)
```
This code defines a language graph and a set of language embeddings, and then uses the Langgraph instance to generate text based on those inputs.

**Conclusion**

In this tutorial, we have explored the concepts and usage of Langchain and Langgraph, two powerful tools in the field of Natural Language Processing. We have also provided coding examples for both Langchain and Langgraph, demonstrating how to use these libraries to generate and manipulate language.

**Resource References**

For further learning, you can refer to the following resources:

* Langchain documentation: <https://langchain.readthedocs.io/>
* Langgraph documentation: <https://langgraph.readthedocs.io/>
* Natural Language Processing with Python: <https://www.packtpub.com/product/natural-language-processing-with-python/9781789342221>

Note: The JSON string for tool calls is not provided as per the instructions.
# -------------------------------------------------
## 💬 Q&A Support :

User Query: I am confused between Langgraph and CrewAI when to use what for Agent Creation? 

Expert Response: I'm happy to help you with that!

LangGraph and CrewAI are both popular tools used for agent creation, but they serve different purposes and are suited for different use cases. Let me break it down for you:

**LangGraph:**
LangGraph is a language-based agent creation platform that focuses on generating conversational AI models. It's designed to help you build conversational interfaces, such as chatbots, voice assistants, and virtual agents. LangGraph uses a unique approach that combines natural language processing (NLP) and machine learning to create highly customizable and adaptable conversational agents.

When to use LangGraph:

1. You're building a conversational interface, such as a chatbot or voice assistant, and need a platform that can generate highly customizable and adaptable conversational agents.
2. You're working with text-based interfaces and want to create conversational flows that can understand and respond to user input.
3. You need a platform that can handle complex conversations, including multi-turn dialogues and conditional logic.

**CrewAI:**
CrewAI is a platform that focuses on building augmented intelligence (AI) agents for various applications, including customer service, sales, marketing, and more. It uses a combination of machine learning, NLP, and human-in-the-loop training to create highly effective and context-aware AI agents.

When to use CrewAI:

1. You're building an AI-powered application that requires a high level of context awareness and understanding of user behavior.
2. You need a platform that can handle multiple tasks and workflows, such as customer service, sales, and marketing.
3. You're working with unstructured data and need a platform that can extract relevant information and make accurate predictions.

In summary, if you're building a conversational interface or need a platform that can generate highly customizable and adaptable conversational agents, LangGraph might be the better choice. If you're building an AI-powered application that requires context awareness and can handle multiple tasks and workflows, CrewAI might be the better fit.

Which one are you leaning towards, or do you have any specific requirements that might help me provide a more tailored recommendation? 

User Query: I'm happy to help you with that!

LangGraph and CrewAI are both popular tools used for agent creation, but they serve different purposes and are suited for different use cases. Let me break it down for you:

**LangGraph:**
LangGraph is a language-based agent creation platform that focuses on generating conversational AI models. It's designed to help you build conversational interfaces, such as chatbots, voice assistants, and virtual agents. LangGraph uses a unique approach that combines natural language processing (NLP) and machine learning to create highly customizable and adaptable conversational agents.

When to use LangGraph:

1. You're building a conversational interface, such as a chatbot or voice assistant, and need a platform that can generate highly customizable and adaptable conversational agents.
2. You're working with text-based interfaces and want to create conversational flows that can understand and respond to user input.
3. You need a platform that can handle complex conversations, including multi-turn dialogues and conditional logic.

**CrewAI:**
CrewAI is a platform that focuses on building augmented intelligence (AI) agents for various applications, including customer service, sales, marketing, and more. It uses a combination of machine learning, NLP, and human-in-the-loop training to create highly effective and context-aware AI agents.

When to use CrewAI:

1. You're building an AI-powered application that requires a high level of context awareness and understanding of user behavior.
2. You need a platform that can handle multiple tasks and workflows, such as customer service, sales, and marketing.
3. You're working with unstructured data and need a platform that can extract relevant information and make accurate predictions.

In summary, if you're building a conversational interface or need a platform that can generate highly customizable and adaptable conversational agents, LangGraph might be the better choice. If you're building an AI-powered application that requires context awareness and can handle multiple tasks and workflows, CrewAI might be the better fit.

Which one are you leaning towards, or do you have any specific requirements that might help me provide a more tailored recommendation? 

Expert Response: LangGraph is a powerful tool for building conversational AI models. Here are some more specific use cases and best practices to keep in mind when using LangGraph:

**Use cases:**

1. **Chatbots:** LangGraph is well-suited for building chatbots that can understand and respond to user input. You can create conversational flows that can handle multiple turns and conditional logic.
2. **Virtual assistants:** LangGraph can be used to build virtual assistants that can understand voice commands and respond accordingly.
3. **Customer service:** LangGraph can be used to build AI-powered customer service platforms that can understand and respond to customer inquiries.
4. **Marketing:** LangGraph can be used to build AI-powered marketing platforms that can understand and respond to customer queries, as well as generate personalized marketing messages.

**Best practices:**

1. **Define your use case:** Before building your conversational AI model, define your use case and goals. This will help you focus on the specific features and functionality you need.
2. **Use high-quality training data:** LangGraph requires high-quality training data to learn from. Make sure your training data is accurate, diverse, and relevant to your use case.
3. **Design your conversational flow:** LangGraph allows you to design custom conversational flows. Make sure to think about the user journey and create a flow that is intuitive and easy to follow.
4. **Test and refine:** Once you've built your conversational AI model, test it thoroughly and refine it as needed. LangGraph provides tools to help you test and refine your model.
5. **Monitor and analyze:** Monitor and analyze your conversational AI model's performance regularly to identify areas for improvement.

**Tips and tricks:**

1. **Use LangGraph's pre-built intents:** LangGraph provides pre-built intents that can help you get started quickly. These intents can be customized to fit your specific use case.
2. **Use conditional logic:** LangGraph allows you to create conditional logic in your conversational flow. This can help you create more complex and nuanced conversations.
3. **Use entity recognition:** LangGraph provides entity recognition capabilities that can help you extract relevant information from user input.
4. **Use natural language processing (NLP) techniques:** LangGraph provides NLP techniques such as sentiment analysis and language modeling that can help you understand user input and generate more accurate responses.

I hope this helps! Do you have any specific questions about using LangGraph or building conversational AI models? 

User Query: LangGraph is a powerful tool for building conversational AI models. Here are some more specific use cases and best practices to keep in mind when using LangGraph:

**Use cases:**

1. **Chatbots:** LangGraph is well-suited for building chatbots that can understand and respond to user input. You can create conversational flows that can handle multiple turns and conditional logic.
2. **Virtual assistants:** LangGraph can be used to build virtual assistants that can understand voice commands and respond accordingly.
3. **Customer service:** LangGraph can be used to build AI-powered customer service platforms that can understand and respond to customer inquiries.
4. **Marketing:** LangGraph can be used to build AI-powered marketing platforms that can understand and respond to customer queries, as well as generate personalized marketing messages.

**Best practices:**

1. **Define your use case:** Before building your conversational AI model, define your use case and goals. This will help you focus on the specific features and functionality you need.
2. **Use high-quality training data:** LangGraph requires high-quality training data to learn from. Make sure your training data is accurate, diverse, and relevant to your use case.
3. **Design your conversational flow:** LangGraph allows you to design custom conversational flows. Make sure to think about the user journey and create a flow that is intuitive and easy to follow.
4. **Test and refine:** Once you've built your conversational AI model, test it thoroughly and refine it as needed. LangGraph provides tools to help you test and refine your model.
5. **Monitor and analyze:** Monitor and analyze your conversational AI model's performance regularly to identify areas for improvement.

**Tips and tricks:**

1. **Use LangGraph's pre-built intents:** LangGraph provides pre-built intents that can help you get started quickly. These intents can be customized to fit your specific use case.
2. **Use conditional logic:** LangGraph allows you to create conditional logic in your conversational flow. This can help you create more complex and nuanced conversations.
3. **Use entity recognition:** LangGraph provides entity recognition capabilities that can help you extract relevant information from user input.
4. **Use natural language processing (NLP) techniques:** LangGraph provides NLP techniques such as sentiment analysis and language modeling that can help you understand user input and generate more accurate responses.

I hope this helps! Do you have any specific questions about using LangGraph or building conversational AI models? 

Expert Response: You're welcome! It was great chatting with you and helping you understand more about LangGraph and its use cases. If you have any more questions or need further assistance in the future, don't hesitate to reach out. Until next time, farewell! 

User Query: You're welcome! It was great chatting with you and helping you understand more about LangGraph and its use cases. If you have any more questions or need further assistance in the future, don't hesitate to reach out. Until next time, farewell! 
# -------------------------------------------------
## 🎙️ Interview Preparation

# Generative AI Interview Questions

These questions are designed to assess a candidate's knowledge and skills in Generative AI, a rapidly growing field that encompasses various techniques for generating new content, such as text, images, music, and more.

**Section 1: Fundamentals**

1. What is Generative Adversarial Networks (GANs), and how do they differ from traditional machine learning models?
2. Explain the concept of Generative Models and their applications.
3. How do you measure the quality of generated text or images in a generative model?
4. What are some common challenges in training generative models, and how do you address them?
5. Describe the difference between a generative model and a discriminative model.

**Section 2: Techniques and Applications**

1. How do you implement a Variational Autoencoder (VAE) and what are its advantages and disadvantages?
2. What is the concept of Style Transfer, and how do you implement it using GANs?
3. Describe the use of Generative Adversarial Networks (GANs) in image-to-image translation tasks.
4. How do you apply Generative Models to Natural Language Processing (NLP) tasks, such as language translation or text summarization?
5. What is the concept of Generative Replay, and how do you implement it to improve the performance of generative models?

**Section 3: Evaluation and Comparison**

1. How do you evaluate the performance of a generative model, and what metrics do you use?
2. What are some common pitfalls when comparing the performance of different generative models?
3. Describe the concept of diversity in generative models, and how do you measure it?
4. How do you compare the quality of generated text or images from different generative models?
5. What are some common techniques for visualizing the output of generative models?

**Section 4: Advanced Topics**

1. How do you implement a conditional GAN (cGAN) and what are its applications?
2. What is the concept of InfoGAN, and how do you implement it to disentangle latent representations?
3. Describe the use of Generative Models in time-series forecasting tasks.
4. How do you apply Generative Models to audio processing tasks, such as music generation or audio denoising?
5. What is the concept of Generative Data Augmentation, and how do you implement it to improve the performance of generative models?

These questions are designed to assess a candidate's understanding of the fundamental concepts, techniques, and applications of Generative AI. The questions are divided into four sections: Fundamentals, Techniques and Applications, Evaluation and Comparison, and Advanced Topics.
Here is a list of Generative AI junior level interview questions:

**Section 1: Fundamentals**

1. What is Generative Adversarial Networks (GANs), and how do they differ from traditional machine learning models?
2. Describe the concept of Generative Models and their applications.
3. What are some common metrics used to evaluate the quality of generated text or images in a generative model?
4. How do you handle overfitting in generative models?
5. What is the concept of modes in generative models, and how do you deal with them?

**Section 2: Techniques and Applications**

1. How do you implement a Variational Autoencoder (VAE) and what are its advantages and disadvantages?
2. What is the concept of Style Transfer, and how do you implement it using GANs?
3. Describe the use of Generative Adversarial Networks (GANs) in image-to-image translation tasks.
4. How do you apply Generative Models to Natural Language Processing (NLP) tasks, such as text generation or language modeling?
5. What is the concept of Generative Replay, and how do you implement it to improve the performance of generative models?

**Section 3: Evaluation and Comparison**

1. How do you evaluate the performance of a generative model, and what metrics do you use?
2. What are some common pitfalls when comparing the performance of different generative models?
3. Describe the concept of diversity in generative models, and how do you measure it.
4. How do you compare the quality of generated text or images from different generative models?
5. What are some common techniques for visualizing the output of generative models?

**Section 4: Advanced Topics**

1. How do you implement a conditional GAN (cGAN) and what are its applications?
2. What is the concept of InfoGAN, and how do you implement it to disentangle latent representations?
3. Describe the use of Generative Models in time-series forecasting tasks.
4. How do you apply Generative Models to audio processing tasks, such as music generation or audio denoising?
5. What is the concept of Generative Data Augmentation, and how do you implement it to improve the performance of generative models?

Note: These questions are designed to assess a candidate's understanding of the fundamental concepts, techniques, and applications of Generative AI at a junior level.
# -------------------------------------------------
## 🔍 Job Search Assistance

**Data Scientist Jobs in Sweden**
================================

Sweden is a hub for innovation, and data scientists play a vital role in driving growth across various industries, including tech, healthcare, and manufacturing. With a strong focus on data-driven decision-making, data scientists in Sweden analyze complex datasets to provide actionable insights and solutions.

**Data Scientist Salary in Sweden 2025**
------------------------------------

According to [Leverage Edu](https://leverageedu.com/learn/data-scientist-salary-in-sweden/), the demand for data scientists in Sweden is high due to its strong tech ecosystem, with companies like Spotify and Ericsson providing high salaries.

**Average Data Scientist Salary Range in Sweden**
---------------------------------------------

The average Data Scientist salary range in Sweden is from SEK 578,755 to SEK 866,841. You can view Data Scientist salaries across top companies broken down by base, stock, and bonus on [Levels.fyi](https://www.levels.fyi/t/data-scientist/locations/sweden).

**Best Cities to Study Data Science in Sweden**
---------------------------------------------

The best cities to study Data Science in Sweden are:

* Uppsala
* Stockholm
* Lund
* Linköping

You can find more information on the number of universities and their ranks in Sweden on [EduRank.org](https://edurank.org/cs/data-science/se/).

**Top Universities for Data Science in Sweden**
---------------------------------------------

Some of the top universities for Data Science in Sweden are:

* Uppsala University's Department of Information Technology (offers a data science Master's program with specializations in data engineering, machine learning, and statistics)
* Other top universities include [list universities]

You can find more information on the best universities for Data Science in Sweden on [Globalscholarships.com](https://globalscholarships.com/best-universities-data-science-sweden/).

I hope this refactored version is helpful! Let me know if you have any further requests.
