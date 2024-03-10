# project/Barbarossa: Fine-tuning LLMs on Azerbaijani instruction-tuning dataset

1. **Introduction**

"project/Barbarossa", a pioneering initiative to fine-tune large language models (LLMs) on the Azerbaijani translation of the Stanford Alpaca dataset. This project represents a significant step in enhancing natural language processing capabilities for the Azerbaijani language. Utilizing the self-instruct method, our aim is to improve the understanding and generation of Azerbaijani text in AI models.

The project is named 'Barbarossa' inspired by the Ottoman naval commander Barbaros Hayrettin Pasha, a figure synonymous with exploration, mastery, and transformation in maritime history. Just as Barbarossa played a pivotal role in establishing Ottoman supremacy in the Mediterranean through strategic conquests and naval innovation, this project aims to navigate the uncharted waters of Azerbaijani language AI. The name 'Barbarossa' symbolizes our ambition to lead and innovate in this field, much like the historical figure who transformed the maritime dynamics of his era.


2. **Background**
   
Stanford Alpaca Dataset: This dataset, pivotal in the realm of natural language processing, serves as a comprehensive corpus designed for instruction-based learning. It includes a wide array of tasks and prompts that test a model's ability to follow instructions and generate contextually relevant responses.

Instruction-Tuning and Self-Instruct Method: Instruction-tuning refers to the process of adapting models to understand and execute tasks based on natural language instructions. The self-instruct method further refines this approach by allowing models to improve their ability to interpret and act on instructions through iterative self-learning processes.

Need for Azerbaijani Language Support in LLMs: Despite the rapid advancement in AI and natural language processing, the Azerbaijani language has seen limited representation and support within large language models. This project aims to bridge this gap, trying to understand the AI's understanding and generation capabilities in Azerbaijani.

3. **Objectives**
   
Our primary objective with this project is to offer insights into the feasibility and outcomes of fine-tuning large language models (LLMs) for the Azerbaijani language. The fine-tuning process, carried out with limited resources, aims to provide valuable learnings rather than creating a model ready for production use. __Consequently, we recommend approaching this model as a reference or guide for understanding the potential and challenges involved in fine-tuning LLMs for specific languages. It serves as a foundational step towards further research and development, rather than a direct solution for production environments.__ Our goals include:

- Demonstrating the capability to fine-tune LLMs on Azerbaijani language data.
- Providing a foundation for future advancements and research in Azerbaijani language AI.


4. **Methodology**
   
The process involved several key steps:

Preparation of the Fine-tuning Dataset: The Stanford Alpaca dataset, originally in English, was translated into Azerbaijani using translation API. Special attention was given to maintaining the integrity and nuances of the instructional content.

We initially selected over 45+ large language models (LLMs) for fine-tuning, but upon careful analysis and consideration of the fine-tuning outcomes, it became apparent that not all the initially selected models performed to the anticipated standards.

Adaptation Strategy: The fine-tuning process was guided by the self-instruct method, which emphasizes the model's ability to understand and generate responses based on instructional data. This approach not only enhances the model's linguistic capabilities but also its understanding of context and ability to follow complex instructions.

5. **Usage and Guidelines**


We are excited to share our fine-tuned models with the community and encourage their use in a variety of applications. 

*Please note: The models listed below represent the preliminary versions fine-tuned for Azerbaijani language tasks, made available for open-source collaboration. These are not the fully optimized versions, which are retained for internal development and further research at Alas Development Center.*

 --- | LLM name |  Finetuned LLM url (Huggingface) | 
--- | --- | --- |
1 | az-gptneo | [alasdevcenter/az-gptneo](https://huggingface.co/alasdevcenter/az-gptneo) | 
2 | az-longchat-base | [alasdevcenter/az-longchat-base](https://huggingface.co/alasdevcenter/az-longchat-base) | 
3 | az-mpt | [alasdevcenter/az-mpt](https://huggingface.co/alasdevcenter/az-mpt) | 
4 | az-llama2 | [alasdevcenter/az-llama2](https://huggingface.co/alasdevcenter/az-llama2) | 
5 | az-dolly | [alasdevcenter/az-dolly](https://huggingface.co/alasdevcenter/az-dolly) | 
6 | az-gpt2-alpaca | [alasdevcenter/az-gpt2-alpaca](https://huggingface.co/alasdevcenter/az-gpt2-alpaca) | 
7 | az-longchat | [alasdevcenter/az-longchat](https://huggingface.co/alasdevcenter/az-longchat) | 
8 | az-tinyllama | [alasdevcenter/az-tinyllama](https://huggingface.co/alasdevcenter/az-tinyllama) | 
9 | az-openchat | [alasdevcenter/az-openchat](https://huggingface.co/alasdevcenter/az-openchat) | 
10 | az-vicgalle-gpt2 | [alasdevcenter/az-vicgalle-gpt2](https://huggingface.co/alasdevcenter/az-vicgalle-gpt2) | 
11 | az-stablelm | [alasdevcenter/az-stablelm](https://huggingface.co/alasdevcenter/az-stablelm) | 
12 | az-vigogne | [alasdevcenter/az-vigogne](https://huggingface.co/alasdevcenter/az-vigogne) | 
13 | az-tulu | [alasdevcenter/az-tulu](https://huggingface.co/alasdevcenter/az-tulu) | 
14 | az-orca-mini | [alasdevcenter/az-orca-mini](https://huggingface.co/alasdevcenter/az-orca-mini) | 
15 | az-opt | [alasdevcenter/az-opt](https://huggingface.co/alasdevcenter/az-opt) | 
16 | az-mistral | [alasdevcenter/az-mistral](https://huggingface.co/alasdevcenter/az-mistral) | 
17 | az-instruct-gpt | [alasdevcenter/az-instruct-gpt](https://huggingface.co/alasdevcenter/az-instruct-gpt) | 
18 | az-hermes | [alasdevcenter/az-hermes](https://huggingface.co/alasdevcenter/az-hermes) | 
19 | az-galpaca | [alasdevcenter/az-galpaca](https://huggingface.co/alasdevcenter/az-galpaca) | 
20 | az-deepseek | [alasdevcenter/az-deepseek](https://huggingface.co/alasdevcenter/az-deepseek) | 
21 | az-decilm | [alasdevcenter/az-decilm](https://huggingface.co/alasdevcenter/az-decilm) | 
22 | az-chopt | [alasdevcenter/az-chopt](https://huggingface.co/alasdevcenter/az-chopt) | 
23 | az-flan-t5 | [alasdevcenter/az-flan-t5](https://huggingface.co/alasdevcenter/az-flan-t5) | 
24 | az-pandalm | [alasdevcenter/az-pandalm](https://huggingface.co/alasdevcenter/az-pandalm) | 
25 | az-wizardlm | [alasdevcenter/az-wizardlm](https://huggingface.co/alasdevcenter/az-wizardlm) | 
26 | az-alpacagpt | [alasdevcenter/az-alpacagpt](https://huggingface.co/alasdevcenter/az-alpacagpt) | 
27 | az-baize-base | [alasdevcenter/az-baize-base](https://huggingface.co/alasdevcenter/az-baize-base) | 
28 | az-cerebras | [alasdevcenter/az-cerebras](https://huggingface.co/alasdevcenter/az-cerebras) | 
29 | az-bloom | [alasdevcenter/az-bloom](https://huggingface.co/alasdevcenter/az-bloom) | 



      
6. **Team members**

The success of project/Barbarossa is a testament to the collective effort of a multidisciplinary team, comprising AI researchers, software engineers, and project managers. 


[Nijat Zeynalov](https://az.linkedin.com/in/nijat-zeynalov-064163142),
[Natig Mamishov](https://az.linkedin.com/in/natig-mamishov),
[Zaur Taghiyev](https://az.linkedin.com/in/zaur-tagiyev),
[Narmin Ibrahimova](https://az.linkedin.com/in/nərmin-ibrahimova-bab29821a),
[Ali Alakbarli](www.linkedin.com/in/ali-alakbarli-3a1613281),
[Matin Huseyngulu](www.linkedin.com/in/matin-huseyngulu-719a98204),
[Kamran Abbasov](http://linkedin.com/in/kamranabbasov),
[Bayram Bayramli](https://www.linkedin.com/in/bayram-bayramlı),
[Rashad Damirov](https://www.linkedin.com/in/rəşad-dəmirov-89b124280),
[Said Shikhizada](https://www.linkedin.com/in/said-shikhizada),
[Agababa Taghizade](https://www.linkedin.com/in/agababa-tagizade/),
[Elvin Nasibov](https://www.linkedin.com/in/elvin-nasibov-793879214/),
[Ilkin Ismayilzade](https://www.linkedin.com/in/ilkin-ismayilzade-24038528a/)

      
7. **Acknowledgement and Usage Terms**

We are thrilled to offer these finely-tuned large language models to the public, free of charge. Our goal is to foster a collaborative and inclusive environment where technological advancements are accessible to all, especially for the development and enhancement of AI in the Azerbaijani language.


8. **Research and Development Notice**

Our journey through Project Barbarossa presented several technical challenges, most notably in computing resources. The computational intensity required for fine-tuning large language models (LLMs) necessitated strategic decisions to optimize our resource allocation effectively. Given these constraints, a strategic decision was made to publicly share only the models that were fine-tuned for 5000 steps. This decision was rooted in our aim to demonstrate the potential adaptability and initial performance of these models on Azerbaijani, under limited fine-tuning.

This decision allows us to contribute valuable insights and tools to the field of AI research, specifically in Azerbaijani language processing, while retaining the fully optimized versions of these models for internal use and further development. The models made available are intended to serve as a foundation for research, offering a glimpse into the potential of AI in enhancing language processing capabilities for Azerbaijani.

It's important to note that the shared models, while a significant step forward, represent preliminary results of our work. These models are part of an ongoing research effort and should be approached as such. We encourage the community to experiment with and build upon these initial models, keeping in mind their training context and optimization scope.

Our decision not to open-source the fully fine-tuned versions is based on a strategic approach to balancing contribution with the continuation of in-depth research and development. We believe this approach will foster innovation while allowing us to further refine and enhance AI capabilities for the Azerbaijani language.
