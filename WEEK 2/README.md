# WEEK 2

Now that we have made ouselves comfortable python coding and Numpy it is time to start our jounrey on Neural Networking. You can start by following the below resources for the same. During this week you will become
acquainted with Artificial Neural Networks, which have proven to be highly effective in solving complex problems of different domains. Artificial Neural Networks (ANNs) are versatile machine learning models inspired
by the human brain. They consist of interconnected nodes, or neurons, organized into layers that process input data to produce output. Convolutional Neural Networks (CNNs), a specialized type of ANN, excel in image
recognition by leveraging convolutional layers.

https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi

https://www.coursera.org/learn/neural-networks-deep-learning?specialization=deep-learning

Now we will explore the seemingly complex structure of transformers, and uncover the simple components inside them that together power a large portion of the ongoing AI revolution. You will also learn about the most important innovation from previous sequential data processing techniques- attention. We will end by looking at how they power Large Language Models, like the now ubiquitous GPTs. Start with the following resources

https://youtu.be/CMrHM8a3hqw?si=CG1lwW5DL_nQVSQA
https://www.geeksforgeeks.org/natural-language-processing-overview/
https://youtu.be/viZrOnJclY0?si=kS7WCSG6DPK6vrcw

This page contains links to section-wise resources on this week's topics. Please go through all of them carefully.
## Transformers
Transformers mark a significant leap in neural networks for processing sequences, like text. This is made possible by self-attention, a crucial element that lets them analyze all elements in a sequence at once, not sequentially.

It's like understanding the context of each puzzle piece based on its connection with others. Self-attention helps the model grasp how each element relates to the rest. This ability makes transformers excellent at tasks where the context and relations between elements matter. This innovation has propelled AI's capabilities in various applications involving sequences, especially in applications related to NLP.

https://jalammar.github.io/illustrated-transformer/   A very informative and easy to understand post on how transformers work
https://www.youtube.com/watch?v=zxQyTK8quyY  by StatQuest with Josh Starmer

## Large Language Models (LLM)
Large Language Models, like transformers, represent a substantial advancement in neural networks for comprehending language intricacies. Self-attention empowers them to process entire sentences holistically rather than sequentially word by word. This capability enables words to derive meaning from others in a sophisticated, interwoven manner, leading to high proficiency in tasks like translation, where understanding word context is paramount.

Most LLMs nowadays use transformer architecture, and the terms are quite often used interchangeably. The major difference that LLMs have in comparision to traditional language models is that at such massive scales with large amounts of training data, these models start to exhibit "emergent properties" like zero-shot learning, where models are able to perform tasks they were never explicitly trained for with remarkable proficiency.

https://research.aimultiple.com/large-language-models/
https://www.geeksforgeeks.org/large-language-model-llm/

## Decoding Strategies
Decoding strategies refer to techniques used to influence the output sequences generated from the model's learned representations - the process of producing meaningful and coherent sequences of text based on the model's predictions. While it might seem like the right choice would be to always use the most probable prediction by the network, this many times leads to repititive and unnatural results. Many different strategies like random sampling and temperature scaling are employed - usually in combination - to get the desired kind of responses.

https://huggingface.co/blog/how-to-generate
https://txt.cohere.com/llm-parameters-best-outputs-language-ai/

## Hugging Face 🤗
Hugging Face 🤗, most commonly referred to as just 🤗, is an open-source community that is well-known for its contributions to natural language processing (NLP) and artificial intelligence (AI). It provides a platform for researchers, developers, and practitioners to access, share, and collaborate on various NLP models, tools, and resources.

## 🤗 Transformers
Hugging Face is particularly famous for its Transformers library, which has become a central hub for a wide range of pre-trained language models, including GPT variants, BERT, and other popular architectures. This library allows users to easily integrate and fine-tune these pre-trained models for various NLP tasks, such as text classification, named entity recognition, sentiment analysis, and more.

https://huggingface.co/docs/transformers/index

## Gradio
Gradio is an open-source Python library by HuggingFace that simplifies the process of creating user interfaces for machine learning models. It allows users to quickly build interactive interfaces for their models, enabling users to interact with and test the models' performance without requiring extensive coding knowledge. It supports a variety of input types making it easy to design intuitive user interfaces for different types of models and tasks.

By using Gradio, you can showcase your models, demonstrate their capabilities, and gather feedback from users in a more interactive and accessible manner.

https://www.gradio.app/docs/interface

## Fine-tuning Pretrained LLMs
Building an LLM from scratch is no easy task; it requires a massive amount of training data and computational power for pre-training. Hence it is much more efficient to simply fine-tune a pretrained LLM that can be imported, say from the Transformers library of Hugging Face. Fine-tuning is a process in which we limit the LLM to performing certain specific tasks, by re-training it on a specific dataset. Doing this not only specializes the LLM and makes it adapt to our needs; it also increases the model's accuracy on these specified tasks significantly.

Refer to the below links to get an idea of the pretraining process, and you will be able to appreciate the use of fine-tuning a lot more.
https://bekushal.medium.com/pre-training-fine-tuning-and-in-context-learning-in-large-language-models-llms-dd483707b122
https://www.nitorinfotech.com/blog/training-large-language-models-llms-techniques-and-best-practices/





