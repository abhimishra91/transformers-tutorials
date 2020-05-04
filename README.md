# PyTorch Transformers Tutorials 

### Introduction

The field of **NLP** was revolutionized in the year 2018 by introduction of **BERT** and his **Transformer** friends(RoBerta, XLM etc.).

These novel transformer based neural network architectures and new ways to training a neural network on natural language data introduced transfer learning to NLP problems. Transfer learning had been giving out state of the art results in the Computer Vision domain for a few years now and introduction of transformer models for NLP brought about the same paradigm change in NLP.

Companies like [Google](https://github.com/google-research/bert) and [Facebook]([https://github.com/pytorch/fairseq/tree/master/examples/roberta](https://github.com/pytorch/fairseq/tree/master/examples/roberta)) trained their neural networks on large swathes of Natural Language Data to grasp the intricacies of language thereby generating a  Language model. Finally these models were fine tuned to specific domain dataset to achieve state of the art results for a specific problem statement. They also published these trained models to open source community. The community members were now able to fine tune these models to their specific use cases.

[Hugging Face](https://github.com/huggingface) made it easier for community to access and fine tune these models using their Python Package: [Transformers](https://github.com/huggingface/transformers). 

### Motivation
Despite these amazing technological advancements applying these solutions to business problems is still a challenge given the niche knowledge required to understand and apply these method on specific problem statements. Hence, In the following tutorials i will be demonstrating how a user can leverage technologies along with some other python tools to fine tune these Language models to specific type of tasks. 
Before i proceed i will like to mention the following groups for the fantastic work they are doing and sharing which have made these notebooks and tutorials possible:

 - [Hugging Face Team](https://huggingface.co/)
 - Abhishek Thakur for his amazing [Youtube videos](https://www.youtube.com/user/abhisheksvnit)

The problem statements that i will be working with are:

 1. Text Classification - Multi-Class
 2. Text Classification - Multi-Label
 3. Sentiment Classification
 4. Named Entity Recognition	
 5. Question Answering
 6. Summary Writing

### Directory Structure

 1. `data`: This folder contains all the toy data used for fine tuning. 
 2. `utils`: This folder will contain any miscellaneous script used to prepare for the fine tuning.
 3. `models`: Folder to save all the artifacts post fine tuning. 

### Further Watching/Reading

I will try to cover the practical and implementation aspects of fine tuning of these language models on various NLP tasks. You can improve your knowledge on this topic by reading/watching the following resources.


 - Watching
	 - [Introduction in Simple terms](https://www.youtube.com/watch?v=gcHkxP9adiM)
	 - [Transfer Learning in NLP](https://www.youtube.com/watch?v=0T_Qr4qBrqc)
	 - [BERT Research Series from ChrisMcCormickAI](https://www.youtube.com/playlist?list=PLam9sigHPGwOBuH4_4fr-XvDbe5uneaf6)

- Reading
	 - [Transformers Documentation](https://huggingface.co/transformers/)
	 - [Pytorch Documentation](https://pytorch.org/docs/stable/index.html)
	 - [Google AI Blog](https://ai.googleblog.com/)
