---
title: "自然语言处理（2026春 国科大计算机学院专业核心课）"
collection: teaching
type: "王石、资康莉、刘瑜"
permalink: /teaching/2026spring-nlp
venue: "课程编号：180086085404P2009Y"
date: 2026-03-01
location: "Beijing, China"
---

本课程重点介绍基于大模型的自然语言处理基础知识、核心技术以及应用方法，并简要介绍传统自然语言处理的相关知识。内容以深入浅出方式展开，对基础知识适当展开回顾，同时及时更新最新研究论文内容，旨在让学生系统地掌握大模型为主的自然语言处理技术，适合于从事该领域研究、工程应用的研究生或相关从业人员。

课程安排：
* 1-18周：玉泉路校区教学楼阶一5，5-7节（13:30-16:10）
* 第4/8/12周周日加课：玉泉路校区教学楼阶二5，5-7节（13:30-16:10）
* [教学日历](https://mp.weixin.qq.com/s/HrJRdASkM966jwhhZk0wnA)
* [PPT下载](https://pan.baidu.com/s/149uA2QzS4ozKvHltHT0TEQ) 提取码: im2q

# [第一部分 基础知识]

## [01 绪论](../files/2026spring_nlp_01_introduction.pdf)
* 人人都爱NLP
* Hello，NLP！
* NLP任务概览
* 初识大模型

## [02 神经网络](../files/2026spring_nlp_02_nn.pdf)
* 神经网络原理（MLP）
* 训练神经网络（BP）
* 常见网络结构（RNN/LSTM/GRU）
* Encoder-Decoder架构

## [03 注意力](../files/2026spring_nlp_03_attention.pdf)
* 带注意力的Encoder-Decoder
* 自注意力
* 位置编码
* Transformers
                    
## [04 词嵌入](../files/2026spring_nlp_04_embedding.pdf)
* 什么是词嵌入
* Word2Vec
* Glove
* 词元Token

## [练习1 - 从入门到变形](../files/2026spring_nlp_04.A_practice1.pdf)
* 手搓异或网络
* PyTorch版异或网络
* NNLM
* Transformer

# [第二部分 大语言模型]

## [05 预训练](../files/2026spring_nlp_05_plm.pdf)
* 什么是预训练
* 预训练方法
* 预训练大语言模型

## [06 提示](../files/2026spring_nlp_06_prompt.pdf)
* 什么是prompt
* 提示工程
* 提示学习

## [07 微调](../files/2026spring_nlp_07_tuning.pdf)
* 全量微调
* 参数高效微调
* 指令微调

## [08 推理优化](../files/2026spring_nlp_08_optimizing.pdf)
* KV缓存
* 注意力优化
* 模型瘦身(量化/稀疏/蒸馏)
* 混合专家MOE
* 批处理

## [09 对齐](../files/2026spring_nlp_09_alignment.pdf)
* 大模型对齐
* 强化学习
* 偏好优化
* 对齐评测

## [10 推理模型](../files/2026spring_nlp_10_reasoning.pdf)
* 什么是推理模型
* 推理方式
* 训练方法
* 典型代表
