# Using_Tavily
The repo is for an example of using Tavily

1. It provides Real-time web access
2. different triers - 
   a. Researcher - Free, 1000 API credits
   b. Project - 30 $ per month, 4000 API credits
   c. Add-on - 100 $ per month, 8000 API credits
   d. Custom - Custom rate limits

3. **How is Tavily different from other APIs?** 
Unlike Bing, Google and SerpAPI, Tavily Search API reviews multiple sources to find the most relevant content from each source, delivering concise, ready-to-use information optimized for LLM context.
4. **Advantage**
Purpose-built for AI: Designed with AI agents and LLMs in mind, ensuring ideal results for AI workflows like Retrieval Augmented Generation (RAG).
Customizable: Control the search depth, manage domains.
Real-time: Retrieves reliable, up-to-date information, ensuring your AI systems have the most relevant data.
Easy Integration: Simple API setup with support for Python libraries and partnerships with LangChain and LlamaIndex.
Scalable: Tavily is built to scale as your usage grows, making it a reliable solution for both startups and enterprise customers.
5. GPT Researcher is an open-source, autonomous agent powered by Tavily’s Search API.  This means the code that makes GPT Researcher work is publicly available.  Anyone can view, use, modify, and distribute it. This fosters transparency, collaboration, and community-driven development. You can find the code on platforms like GitHub.

GPT Researcher -> Understand a research task + Create a plan for gathering information + Execute that plan by searching for relevant data + Synthesize the findings into a comprehensive report

6. **How Tavily Handles scalability**
    a. Distributed Infrastructure: Tavily likely uses a distributed system architecture, where its search functionality is spread across multiple servers and data centers. This allows it to handle a large volume of search requests concurrently without performance degradation.As the number of users or queries increases, Tavily can add more servers to its infrastructure to accommodate the growing demand.
    b. Efficient Indexing and Search Algorithms: Tavily employs advanced algorithms for indexing and searching through vast amounts of data. These algorithms are optimized for speed and efficiency, allowing Tavily to quickly retrieve relevant information even with a massive index. 

In Tavily's output, the "score" field represents a relevance score that indicates how closely a retrieved document matches your search query. It's a value between 0 and 1, where higher scores indicate greater relevance.

**Note**
When performing retrieval using LangChain, cosine similarity is generally used as the default similarity metric.
Tavily's relevance scoring relies on proprietary AI algorithms that are not publicly disclosed. This is common for commercial search engines and AI platforms to protect their intellectual property and competitive advantage.
