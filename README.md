# Multimedia




## Event Extraction
- **Cross-media Structured Common Space for Multimedia Event Extraction;** Manling Li et al; Focus on image-text event extraction. A new benchmark and baseline are proposed. 
- **Visual Semantic Role Labeling for Video Understanding;** Arka Sadhu et al; A new benchmark is proposed. 
- **CLIP-Event: Connecting Text and Images with Event Structures;** Manling Li et al; The new model CLIP-Event, specifically designed for multi-modal event extraction. Introducing new pretraining tasks to enable strong zero-shot performances. 
- **GAIA: A Fine-grained Multimedia Knowledge Extraction System;** Manling Li et al; Demo paper. Extract knowledge (relation, event) from multimedia data. 

## Situation Recognition
- **Situation Recognition: Visual Semantic Role Labeling for Image Understanding;** Mark Yatskar et al; Focus on image understanding. Given images, do the semantic role labeling task. No text available. A new benchmark and baseline are proposed. 
- **Commonly Uncommon: Semantic Sparsity in Situation Recognition;** Mark Yatskar et al; Address the long-tail problem.


## Scene Graph
- **Visual Distant Supervision for Scene Graph Generation;** Yuan Yao et al
- **Learning to Generate Scene Graph from Natural Language Supervision;** Yiwu Zhong et al
- **Weakly Supervised Visual Semantic Parsing;** Alireza Zareian, Svebor Karaman, Shih-Fu Chang
- **Scene Graph Prediction with Limited Labels;** Vincent S. Chen, Paroma Varma, Ranjay Krishna, Michael Bernstein, Christopher Re, Li Fei-Fei
- **Neural Motifs: Scene Graph Parsing with Global Context;** Rowan Zellers et al
- **Fine-Grained Scene Graph Generation with Data Transfer;** Ao Zhang et al
- **Towards Open-vocabulary Scene Graph Generation with Prompt-based Finetuning;** Tao He et al
- **Action Genome: Actions as Composition of Spatio-temporal Scene Graphs;** Jingwei Ji et al; Spatio-temporal scene graphs. 
- **SGEITL: Scene Graph Enhanced Image-Text Learning for Visual Commonsense Reasoning;** Zhecan Wang et al; Application. Incorporating scene graphs in pretraining and fine-tuning improves performance of VCR tasks. 



## Planning
- **Multimedia Generative Script Learning for Task Planning;** Qingyun Wang et al; Next step prediction.
- **PlaTe: Visually-Grounded Planning with Transformers in Procedural Tasks;** Jiankai Sun et al; Procedure planning. 
- **P3IV: Probabilistic Procedure Planning from Instructional Videos with Weak Supervision;** He Zhao et al; Procedure planning. Using text as weak supervision to replace video clips. 
- **Procedure Planning in Instructional Videos;** Chien-Yi Chang et al; Procedure planning.


## Reasoning
- **VisualCOMET: Reasoning about the Dynamic Context of a Still Image;** Jae Sung Park et al; Benchmark dataset, requiring models to reason about a still iamge (what happen past & next). 
- **From Recognition to Cognition: Visual Commonsense Reasoning;** Rowan Zellers et al; Benchmark dataset, requiring models to go beyond the recognition level to cognition. Need to reason about a still image and give rationales. 



## Generation
- **ClipCap: CLIP Prefix for Image Captioning;** Ron Mokady et al; Train an light-weight encoder to convert CLIP embeddings to prefix token embeddings of GPT-2. 
- **Multimodal Knowledge Alignment with Reinforcement Learning;** Youngjae Yu et al; Use RL to train an encoder that projects multimodal inputs into the word embedding space of GPT-2. 


## Foundation Model & Pretraining
- **Multimodal Few-Shot Learning with Frozen Language Models;** Maria Tsimpoukelli et al; Use prefix-like image-embedding to stear the text generation process to achieve few-shot learning. 
- **Flamingo: a Visual Language Model for Few-Shot Learning;** Jean-Baptiste Alayrac et al; Designed for few-shot learning. 
- **OFA: Unifying Architectures, Tasks, and Modalities Through a Simple Sequence-to-Sequence Learning Framework;** Peng Wang et al; A unified model (framework) to handle text, image, and image-text tasks. 
- **Grounded Language-Image Pre-training;** Liunian Harold Li et al; Learning object-level, language- aware, and semantic-rich visual representations. Introducing phrase grounding to the pretraining task. 
- **Language Models with Image Descriptors are Strong Few-Shot Video-Language Learners;** Zhenhailong Wang et al
- **CPT: COLORFUL PROMPT TUNING FOR PRE-TRAINED VISION-LANGUAGE MODELS;** Yuan Yao et al
- **PEVL: Position-enhanced Pre-training and Prompt Tuning for Vision-language Models;** Yuan Yao et al; Introduce explicit object position modeling.A woman < 310 mask 406 475 > is watching the mask < 175 86 254 460 > ; 




## Prompting
- **Learning to Prompt for Vision-Language Models;** Kaiyang Zhou et al; Soft prompt tuning. Useing few-shot learning to improve performance on both in-distribution and out-of-distribution data. Few-shot setting. 
- **Unsupervised Prompt Learning for Vision-Language Models;** Tony Huang et al; Soft prompt tuning. Unsupervised setting. 
- **Tip-Adapter: Training-free CLIP-Adapter for Better Vision-Language Modeling;** Renrui Zhang et al; Few-shot setting.
- **CLIP-Adapter: Better Vision-Language Models with Feature Adapters;** Peng Gao et al; Few-shot setting.
- **Neural Prompt Search;** Yuanhan Zhang et al; Explore the combination of LoRA, Adapter, Soft prompt tuning. In full-data, few-shot, and domain shift settings. 
- **Visual Prompt Tuning;** Menglin Jia et al; Soft prompt tuning + head tuning. Show better performance in few-shot and full-data settings than full-parameters tuning. Quite different from the NLP field. 
- **Prompt Distribution Learning;** Yuning Lu et al; Soft prompt tuning. Few-shot setting.




## Analysis
- **What Does BERT with Vision Look At?** Liunian Harold Li et al


## Grounding
- **Flickr30k Entities: Collecting Region-to-Phrase Correspondences for Richer Image-to-Sentence Models;** Bryan A. Plummer et al; A new benchmark dataset, annotating phrase-region correspondences. 
- **Visual Grounding Strategies for Text-Only Natural Language Processing;** Propose to improve the NLP tasks performance by grounding to images. Two methods are proposed.  


## Benchmark & Evaluation
- **How Much Can CLIP Benefit Vision-and-Language Tasks?;** Sheng Shen et al; Explore two scenarios: 1) plugging CLIP into task-specific fine-tuning; 2) combining CLIP with V&L pre-training and transferring to downstream tasks. Show the boost in performance when using CLIP as the image encoder. 
