# AI-Misinformation
Detecting and analyzing hallucinations in LLMs using Logistic Regression and Decision Tree models

**Overview**
We looked at how different AI models sometimes make things up (hallucinate) when answering questions.
Our project tested models like ChatGPT, Claude, Gemini, and Llama on a dataset of claims. We checked if their answers matched the truth or if they gave wrong or made‑up information.

The goal: figure out how often this happens and what patterns we can see.

**Visuals and Design**
We made charts to show how accurate the models were, compare logistic regression and decision tree, where the models got confused (confusion matrix), and how often each model hallucinated.

**Impact and Bias**
Why this matters: Wrong answers can spread misinformation, people may trust AI too much, answers can be reflections of human bias, mistakes may affect certain groups more than others.

**Citations and Documentation**
Dataset: RAGTruth (2024) — benchmark for hallucination detection
Models: ChatGPT, Claude, Gemini, Llama
Tools: Python, Pandas, Matplotlib, Scikit‑learn, Jupyter Notebook
Program: AI4ALL Ignite — Technology & Engineering Track

Niu, C., Wu, Y., Zhu, J., Xu, S., Shum, K., Zhong, R., … Zhang, T. (n.d.). Ragtruth: A hallucination corpus for developing trustworthy retrieval-augmented language models. Retrieved from https://aclanthology.org/2024.acl-long.585/
Ji, Z., Lee, N., Frieske, R., Yu, T., Su, D., Xu, Y., … Fung, P. (2024). Survey of hallucination in natural language generation. Retrieved from https://arxiv.org/abs/2202.03629
Huang, L., Yu, W., Ma, W., Zhong, W., Feng, Z., Wang, H., … Liu, T. (2024). A survey on hallucination in large language models: Principles, taxonomy, Challenges, and open questions. Retrieved from https://arxiv.org/abs/2311.05232

**Next Steps**
Things we'd like to add: use bigger and more diverse datasets, build a small tool that flags hallucinations automatically, make an interactive dashboard to explore results.
