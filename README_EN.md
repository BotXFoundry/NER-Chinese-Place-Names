# NER-Chinese-Place-Names

Last Updated On：2024-09-04

## Overview

Named Entity Recognition (NER) is a core technology in the field of Natural Language Processing (NLP). As the foundation of information extraction, NER is capable of accurately identifying and classifying key entities in text, such as person names, place namess, and organization names, providing robust support for advanced NLP tasks like relation extraction and question answering systems. Particularly in the domains of human-computer interaction and intelligent services, NER enables systems to more precisely comprehend user needs by accurately recognizing named entities in user inputs, thereby offering personalized service experiences. Consequently, place names datasets occupy an indispensable position in the performance evaluation of NER models, with their data quality and annotation quality playing a vital role in assessing model performance. Nevertheless, the current lack of publicly available, high-quality, and ultra-large-scale Chinese place names datasets significantly hinders the in-depth development of related research and applications. To address this gap, we have meticulously gathered millions of place names data from the internet and subjected them to rigorous processes including data correction, text normalization, and deduplication, ultimately open-sourcing a large-scale place names database containing tens of thousands of entries to meet the needs of academic research and commercial development.

This open-sourced 100000 level Chinese place names corpus will enrich and provide high-quality training and evaluation data for subtasks in the NLP field, such as word segmentation, named entity recognition, sentiment analysis, and knowledge graph construction, thereby contributing to algorithm optimization and model performance enhancement. We aspire to lower the data barriers between research and industry by providing standardized data resources, promote the translation of academic research achievements into practical applications, and accelerate the innovative application of AI technologies in fields like intelligent robots and human-computer interaction. In the realm of intelligent robots, precise place names recognition and processing form the foundation for efficient and natural human-computer interaction. We also anticipate that our place names corpus will empower intelligent robots with a better understanding of user intentions and elevate the interactive experience.


### Dataset Characteristics:
**Large Scale**: Comprising millions of place data collected from the internet, the dataset has been meticulously screened and processed, ultimately open-sourced as a 100000 level data corpus.
<br> 
**High Quality**: Advanced techniques such as data correction, text normalization, and deduplication have been employed to ensure the accuracy and reliability of the dataset.
<br> 
**Standardized**: Adhering to a unified annotation standard and data format, it facilitates data sharing and comparison among different research teams.
<br> 
**Diverse**: Covering different regions, cities, rural areas, and specific locations to meet diverse geographic research and intelligent service needs.




## Project Overview
### Directory

The directory classification for this project is as follows:

* [Chinese-Place-Names](/Chinese-Place-Names) 

     &emsp;&emsp;  [Chinese-Place-Names_Beijing_ns](Chinese-Place-Names/Chinese-Place-Names_Beijing_ns.txt)
     <br> 
     &emsp;&emsp;  [Chinese-Place-Names_Large_ns](Chinese-Place-Names/Chinese-Place-Names_Large_ns.txt)
     <br> 
     &emsp;&emsp;  [Chinese-Place-Names_Chinese-Place-Names_Administrative-Villages_ns](Chinese-Place-Names/Chinese-Place-Names_Chinese-Place-Names_Administrative-Villages_ns.txt)
     <br> 
     &emsp;&emsp;  [Chinese-Place-Names_City&Township_ns](Chinese-Place-Names/Chinese-Place-Names_City&Township_ns.txt)
     <br> 
     &emsp;&emsp;  [Chinese-Place-Names_Subdistrict&Villages_ns](Chinese-Place-Names/Chinese-Place-Names_Subdistrict&Villages_ns.txt)
     <br> 
     &emsp;&emsp;  [Chinese-Place-Names_Web_ns](Chinese-Place-Names/Chinese-Place-Names_Web_ns.txt)
     
* [POS standards](/POS_standards)

     &emsp;&emsp;  [POS standards.pdf](POS_standards/POS_standards.pdf)
     <br> 
     &emsp;&emsp;  [POS standards.png](POS_standards/POS_standards.png)
     
### File Encoding Format

File Format: The vocabulary bank is provided in the form of plain text files (.txt), with each line containing a single place names vocabulary.
<br> 
Encoding Method: It employs UTF-8 encoding to ensure support for multilingual characters (though the primary focus of this vocabulary bank is on Chinese place namess).
<br> 
No Additional Annotations: The current version of the place name vocabulary bank does not include additional annotation information, such as part of speech, but future versions may consider adding them.
<br> 
Note: the remaining part of the "Note" section was cut off in the original request, but if there's more content to be.
<br> 

### Part-Of-Speech tagging (POS) Standards
                                                                                        
| Number |Signal | Definition |
|:--:| :--: | :--:|
| 1 | ns | proper nouns referring to name of places|

### Size of the data sample

|   Number  |   Name   |   Size of Names  |
|:--:| :--: | :--:|    
| 1  | Chinese-Place-Names_Beijing_ns  |37689|
| 2  | Chinese-Place-Names_Large_ns |52297|
| 3  | Chinese-Place-Names_Chinese-Place-Names_Administrative-Villages_ns |311856|                                                                                  
| 4  | Chinese-Place-Names_City&Township_ns |38605|
| 5  | Chinese-Place-Names_Subdistrict&Villages_ns |113252|
| 6  | Chinese-Place-Names_Web_ns |19531|

### 文件数据示例

Chinese-Place-Names_Beijing_ns.txt

```
芳星园三区社区
滇香一厨
庆会楼
```

## License

This project is freely open to universities, research institutes, enterprises, organizations, and individuals both domestically and internationally, and can be used for research and commercial purposes.
<br>
We warmly welcome any valuable opinions and suggestions for this open-source project. Please send your emails to botx@botxfoundry.com.
<br>
The license agreement for this project is **Apache License 2.0**. You are free to use, copy, modify, and distribute this project, but you must comply with the provisions in the license.
<br>

## Publisher Introduction

BotXFoundry      &emsp;&emsp;   Web: http://www.botxfoundry.com

As a leading provider of commercial-grade intelligent robot platform solutions, BotX Foundry is dedicated to offering customers advanced intelligent robot universal platform products and technical services. It empowers digital transformation through its unique "F (Foundation) + X (Innovative Scenarios)" model.

The company's core products encompass three main sectors: universal mobile platforms for robots (tethered chassis), essential universal components for robots, and intelligent cloud-based robot brains. This forms a comprehensive and closed-loop product technology system centered around the five-dimensional ABCDE foundational capabilities: AI (Artificial Intelligence for Intelligent Cloud-Based Robot Brains), Bot (Universal Tethered Chassis for Robots), Control (Core Control Components for Robots), Drive (Power and Drive Components for Robots), and Edge (Universal Edge Computing Platforms for Robots).
<br> 
BotXFoundry boasts core technologies in various areas such as indoor and outdoor universal mobile chassis, high-precision servo control for robots, multi-modal and high-precision positioning and navigation, spatial computing for the Metaverse, large-scale models and intelligent human-machine interaction, integrated large-scale model development and training, and autonomous driving for robots.

As a tech company specializing in robotics, we are deeply aware of the significance of data in AI technology development. Consequently, we will continue to invest resources in optimizing and expanding this project while exploring more innovative application scenarios, thereby contributing further to the advancement of AI technology and human-computer interaction in intelligent robots. We look forward to collaborating with researchers and industry peers worldwide to jointly propel the prosperity and development of artificial intelligence technology.