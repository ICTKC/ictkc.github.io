---
title: "Method for Expanding Event Commonsense Knowledge Graph Based on Large Language Models"
collection: publications
permalink: /publication/25-jos-huanqiaojuan
excerpt: ''
date: 2025-01-02
venue: 'Èí¼þÑ§±¨'
citation: 'HUANG Qiao-Juan, CAO Cun-Gen, WANG Ya, WANG Shi. Method for Expanding Event Commonsense Knowledge Graph Based on Large Language Models. Journal of Software, 2025,36(9):4153-4186'
---
Abstract
--
Commonsense knowledge is usually not explicitly expressed in natural languages but is implicitly understood in human cognition. Providing machines with commonsense knowledge has been a longstanding aim in artificial intelligence. Initially, this study manually constructs a high-precision, event-centric commonsense knowledge graph (ECKG) for seed events in Chinese. It contains 26 606 commonsense event triples encompassing causal, temporal, conditional, and other common event relationships. Although the constructed ECKG holds considerable value, its limited scale curtails practical applications. Besides, large-scale event commonsense knowledge graphs are rare in current studies. To overcome these challenges, this paper uses large language models from the GPT series to expand the above-mentioned three event relationships and sub-events of the proposed ECKG. The expansion method involves three primary steps. Firstly, specific prompts for event knowledge (ek-prompts) are designed by combining the events in the ECKG with four relationships, and GPT-4-Turbo is used to generate corresponding event triples. Secondly, the triples of the ECKG are integrated with accurate triples obtained by ek-prompts to create a specialized dataset. Additionally, GPT-3.5-Turbo is fine-tuned on the dataset to generate more specific event triples and validate the accuracy of new triples. Lastly, by analyzing the similarities among events in the ECKG and implementing an event-sharing mechanism, similar events within the same relationship are interconnected, ensuring consistency across similar event triples. Experimental results show that the newly acquired triples are of high quality, particularly those of the temporal relationships, with an accuracy rate of 98.2%. Ultimately, the proposed expansion method appends 2 433 012 commonsense event triples to the original ECKG, significantly expanding its scale and providing more commonsense knowledge for many applications in artificial intelligence.

[Download](https://www.jos.org.cn/jos/article/abstract/7262)
