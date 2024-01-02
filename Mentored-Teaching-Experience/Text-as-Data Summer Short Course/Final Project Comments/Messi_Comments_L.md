## Comments

+ Really enjoyed reading the proposal. 

+ I really liked the idea of using GPT-4 to label documents. IIRC there are a few articles arguing that they are as good as human coding. You note that LLMs like ChatGPT can manifest bias, which is true, but you should also note that BERT is an LLM and that BERT also exhibits biases. This is to say that no model is perfect, so I would recommend the general approach of using both methods and presenting the worse-performing model as a robustness check (if the performance is acceptable). 

+ Minor note: If you go down the route of fine-tuning BERT, you should look at DeBERTa, which is currently the industry standard for fine-tuning LLMs. 

+ Also, this makes me wonder if the propensity to "hate-share" has to do with other document-level covariates (in this case meta-data of MSNBC and FoxNews tweets). For example, you might expect hate-sharing behavior to differ by the type of news that MSNBC and FoxNews are sharing. Some tweets shared by these news outlets may be neutral reporting of facts. You would expect hate-sharing to occur much less in these types of tweets. Just a food for thought. 

+ This seems like a great start looking at the prevalence of "hate-sharing" as a phenomenon. Reading this part made me think about the subsequent research questions and the massive potential this project holds. 