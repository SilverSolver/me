# Laida Kushnareva : about

I am a Machine Learning Researcher focusing on Natural Language Processing with over five years of experience in Machine Learning Research and Development in big tech (Huawei, Google, Sberbank). As a graduate of the Faculty of Mechanics and Mathematics (MSU), I aim to unlock the potential hidden in the latent space of Language Models and make Artificial Intelligence more transparent and interpretable with beautiful tools given to us by mathematics. 

Aside from my research experience (gained mostly in Huawei), I also had experience as an engineer/developer, which included, in particular, designing and tuning Machine Learning models for improving GNSS navigation (in Google), entity extraction (in Sberbank), and developing small markup tools.

Below, you can find links to various resources in English (marked as "EN") and in Russian (marked as "RU") related to me and my work.

# Selected scientific papers (EN)

### [**Artificial Text Detection via Examining the Topology of Attention Maps**](https://aclanthology.org/2021.emnlp-main.50/)

- A paper by Laida Kushnareva, Daniil Cherniavskii, Vladislav Mikhailov, Ekaterina Artemova, Serguei Barannikov, Alexander Bernstein, Irina Piontkovskaya, Dmitri Piontkovski, and Evgeny Burnaev.
- Published in Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing **(EMNLP 2021)**.
- **Abstract**: The impressive capabilities of recent generative models to create texts that are challenging to distinguish from the human-written ones can be misused for generating fake news, product reviews, and even abusive content. Despite the prominent performance of existing methods for artificial text detection, they still lack interpretability and robustness towards unseen models. To this end, we propose three novel types of interpretable topological features for this task based on Topological Data Analysis (TDA) which is currently understudied in the field of NLP. We empirically show that the features derived from the BERT model outperform count- and neural-based baselines up to 10\% on three common datasets, and tend to be the most robust towards unseen GPT-style generation models as opposed to existing methods. The probing analysis of the features reveals their sensitivity to the surface and syntactic properties. The results demonstrate that TDA is a promising line with respect to NLP tasks, specifically the ones that incorporate surface and structural information.
- [**Video presentation**](https://aclanthology.org/2021.emnlp-main.50.mp4) (EN).

### [**Topological data analysis for speech processing**](https://www.isca-archive.org/interspeech_2023/tulchinskii23_interspeech.pdf)

- A paper by Eduard Tulchinskii, Kristian Kuznetsov, Laida Kushnareva, Daniil Cherniavskii, Serguei Barannikov, Irina Piontkovskaya, Sergey Nikolenko, and Evgeny Burnaev.
- Published in Proceedings of **INTERSPEECH 2023**.
- **Abstract**: We apply topological data analysis (TDA) to speech classification problems and to the introspection of a pretrained speech model, HuBERT. To this end, we introduce a number of topological and algebraic features derived from Transformer attention maps and embeddings. We show that a simple linear classifier built on top of such features outperforms a fine-tuned classification head. In particular, we achieve an improvement of about 9% accuracy and 5% ERR on four common datasets; on CREMA-D, the proposed feature set reaches a new state of the art performance with accuracy 80.155. We also show that topological features are able to reveal functional roles of speech Transformer heads; e.g., we find the heads capable to distinguish between pairs of sample sources (natural/synthetic) or voices without any downstream fine-tuning. Our results demonstrate that TDA is a promising new approach for speech analysis, especially for tasks that require structural prediction.
- [**Website with appendices, an introduction to TDA, and other additional materials, related to this paper**](https://topohubert.github.io/speech-topology-webpages/) (EN).

### [**Intrinsic Dimension Estimation for Robust Detection of AI-Generated Texts**](https://proceedings.neurips.cc/paper_files/paper/2023/hash/7baa48bc166aa2013d78cbdc15010530-Abstract-Conference.html)

- A paper by Eduard Tulchinskii, Kristian Kuznetsov, Laida Kushnareva, Daniil Cherniavskii, Sergey Nikolenko, Evgeny Burnaev, Serguei Barannikov, and Irina Piontkovskaya.
- Published in Advances in Neural Information Processing Systems 36 **(NeurIPS 2023)**.
- **Abstract**: Rapidly increasing quality of AI-generated content makes it difficult to distinguish between human and AI-generated texts, which may lead to undesirable consequences for society. Therefore, it becomes increasingly important to study the properties of human texts that are invariant over text domains and various proficiency of human writers, can be easily calculated for any language, and can robustly separate natural and AI-generated texts regardless of the generation model and sampling method. In this work, we propose such an invariant of human texts, namely the intrinsic dimensionality of the manifold underlying the set of embeddings of a given text sample. We show that the average intrinsic dimensionality of fluent texts in natural language is hovering around the value 9 for several alphabet-based languages and around 7 for Chinese, while the average intrinsic dimensionality of AI-generated texts for each language is ≈ 1.5 lower, with a clear statistical separation between human-generated and AI-generated distributions. This property allows us to build a score-based artificial text detector. The proposed detector's accuracy is stable over text domains, generator models, and human writer proficiency levels, outperforming SOTA detectors in model-agnostic and cross-domain scenarios by a significant margin.

### [**AI-generated text boundary detection with RoFT**](https://arxiv.org/abs/2311.08349)

- A paper by Laida Kushnareva, Tatiana Gaintseva, German Magai, Serguei Barannikov, Dmitry Abulkhanov, Kristian Kuznetsov, Eduard Tulchinskii, Irina Piontkovskaya, and Sergey Nikolenko.
- **Outstanding Paper Award** in the First Conference Of Language Modelling **(CoLM 2024)**.
- **Abstract**: Due to the rapid development of large language models, people increasingly often encounter texts that may start as written by a human but continue as machine-generated. Detecting the boundary between human-written and machine-generated parts of such texts is a challenging problem that has not received much attention in literature. We attempt to bridge this gap and examine several ways to adapt state of the art artificial text detection classifiers to the boundary detection setting. We push all detectors to their limits, using the Real or Fake text benchmark that contains short texts on several topics and includes generations of various language models. We use this diversity to deeply examine the robustness of all detectors in cross-domain and cross-model settings to provide baselines and insights for future research. In particular, we find that perplexity-based approaches to boundary detection tend to be more robust to peculiarities of domain-specific data than supervised fine-tuning of the RoBERTa model; we also find which features of the text confuse boundary detection algorithms and negatively influence their performance in cross-domain settings.

### [**Feature-Level Insights into Artificial Text Detection with Sparse Autoencoders**](https://aclanthology.org/2025.findings-acl.1321/)

- A paper by Kristian Kuznetsov, Laida Kushnareva, Anton Razzhigaev, Polina Druzhinina, Anastasia Voznyuk, Irina Piontkovskaya, Evgeny Burnaev, and Serguei Barannikov.
- Published in **Findings of the Association for Computational Linguistics: EMNLP 2025**.
- **Abstract**: Artificial Text Detection (ATD) is becoming increasingly important with the rise of advanced Large Language Models (LLMs). Despite numerous efforts, no single algorithm performs consistently well across different types of unseen text or guarantees effective generalization to new LLMs. Interpretability plays a crucial role in achieving this goal. In this study, we enhance ATD interpretability by using Sparse Autoencoders (SAE) to extract features from Gemma-2-2B’s residual stream. We identify both interpretable and efficient features, analyzing their semantics and relevance through domain- and model-specific statistics, a steering approach, and manual or LLM-based interpretation of obtained features. Our methods offer valuable insights into how texts from various models differ from human-written content. We show that modern LLMs have a distinct writing style, especially in information-dense domains, even though they can produce human-like outputs with personalized prompts. The code for this paper is available at https://github.com/pyashy/SAE_ATD. 

You can see the full list of papers and preprints on my [**Google Scholar**](https://scholar.google.com/citations?view_op=list_works&hl=en&hl=en&user=rsTb_hYAAAAJ) (EN). You can also see the list of my papers on ACL venues specifically [**here**](https://aclanthology.org/people/laida-kushnareva/) (EN).

# Selected talks (RU)

- [**Popular lecture about chaotic systems**](https://www.youtube.com/watch?v=DiIJjigF_I0) for a Russian-speaking skeptical society, 2014
- [**A talk based on papers "Artificial Text Detection via Examining the Topology of Attention Maps" and "Intrinsic Dimension Estimation for Robust Detection of AI-Generated Texts"**](https://www.youtube.com/watch?v=RqV54_2wiEs) for the International Laboratory of Algebraic Topology and its Applications (ATA) in HSE University, 2023
- **Lecture on Transformer acrhitecture** for Deep Learning School: [**part 1**](https://www.youtube.com/watch?v=lK0hqrVHrUA), [**part 2**](https://www.youtube.com/watch?v=cKPDBXjD9lo), [**part 3**](https://www.youtube.com/watch?v=BgFqtC866qE), 2023
- A talk "[**How to fool AI-generated text detectors**](https://www.youtube.com/watch?v=nqP23FBl4Rc)" for DataFest, 2024.

# Blogs (RU)

- [**Telegram channel**](https://t.me/tech_priestess)
- [**Habr articles**](https://habr.com/ru/users/tech_priestess/publications/articles/)

# Contacts

- [LinkedIn](https://www.linkedin.com/in/laida-kushnareva/)
- Telegram id: @laida_kushnareva
