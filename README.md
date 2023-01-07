# Para-Classifier

Replicate PubMed200 research paper - https://arxiv.org/pdf/1612.05251.pdf
Implemented the model with some minor changes in this paper - https://arxiv.org/pdf/1710.06071.pdf

* Instead of using Glove embedding - 

--> Universal sentence encoder 

--> BERT embeddings

* inplace of `SGD` optimizer `Adam` is used.

And for some layers filter unit is temperd for faster calculations

Achived accuracy 
* for 20k dataset - 88%
* for 200k dataset - 90%


**Input Texts**
Countries worldwide are struggling to develop strategies and infrastructure for appropriate disposal of the increasing medical waste generated by the COVID-19 pandemic. This study examines the available knowledge and current practices in medical/healthcare waste management worldwide, particularly in countries with transitional economies, including the dependence of medical waste generation rate on various socioeconomic and environmental parameters. Here, we conducted a meta-analysis of medical and healthcare waste management practices in 78 countries. We identified impediments and challenges facing the integration of medical waste management into a prospective circular economy according to statistical correlations with human development index (HDI), life expectancy (LE), healthcare expenditure (HE) per capita of gross domestic product (GDP), and environmental performance index (EPI). The results highlight the importance of knowledge and awareness of best practices for infection and injury prevention for waste management among workers. An average of 38.9% of medical waste was segregated for proper management, and only 41% of workers were trained in-service for medical waste disposal. Plastic materials constituted approximately 35% of medical waste, presenting an opportunity for sustainable resource recovery and recycling. It is imperative for all countries to adopt environmentally sustainable management of medical waste to prevent catastrophic stockpiling of infectious waste during and after pandemics. Additionally, we present an outline for future studies on medical waste generation rate and various socioeconomic and environmental parameters that should be investigated in future work to promulgate an inventory of the database for sustainable management of medical/healthcare waste.

**Output in Sections**

<img width="896" alt="image" src="https://user-images.githubusercontent.com/75153245/211154512-3ae3731d-10b9-4199-a7f0-49d36dc0bfbd.png">
