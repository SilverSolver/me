# Laida Kushnareva : about

I am a Machine Learning Researcher focusing on Natural Language Processing with over five years of experience in Machine Learning Research and Development in big tech (Huawei, Google, Sberbank). As a graduate of the Faculty of Mechanics and Mathematics (MSU), I aim to unlock the potential hidden in the latent space of Language Models and make Artificial Intelligence more transparent and interpretable with beautiful tools given to us by mathematics. 

Aside from my research experience (gained mostly in Huawei), I also had experience as an engineer/developer, which included, in particular, designing and tuning Machine Learning models for improving GNSS navigation (in Google), entity extraction (in Sberbank), and developing small markup tools.

Below, you can find links to various resources in English (marked as "EN") and in Russian (marked as "RU") related to me and my work.

# Selected scientific papers

### [Artificial Text Detection via Examining the Topology of Attention Maps](https://aclanthology.org/2021.emnlp-main.50/) 

- A paper by Laida Kushnareva, Daniil Cherniavskii, Vladislav Mikhailov, Ekaterina Artemova, Serguei Barannikov, Alexander Bernstein, Irina Piontkovskaya, Dmitri Piontkovski, and Evgeny Burnaev. Published in **Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing**.
- **Abstract**: The impressive capabilities of recent generative models to create texts that are challenging to distinguish from the human-written ones can be misused for generating fake news, product reviews, and even abusive content. Despite the prominent performance of existing methods for artificial text detection, they still lack interpretability and robustness towards unseen models. To this end, we propose three novel types of interpretable topological features for this task based on Topological Data Analysis (TDA) which is currently understudied in the field of NLP. We empirically show that the features derived from the BERT model outperform count- and neural-based baselines up to 10\% on three common datasets, and tend to be the most robust towards unseen GPT-style generation models as opposed to existing methods. The probing analysis of the features reveals their sensitivity to the surface and syntactic properties. The results demonstrate that TDA is a promising line with respect to NLP tasks, specifically the ones that incorporate surface and structural information.
- [**Video presentation (EN)**](https://aclanthology.org/2021.emnlp-main.50.mp4).

### [Acceptability Judgements via Examining the Topology of Attention Maps](https://aclanthology.org/2022.findings-emnlp.7/)

- A paper by Daniil Cherniavskii, Eduard Tulchinskii, Vladislav Mikhailov, Irina Proskurina, Laida Kushnareva, Ekaterina Artemova, Serguei Barannikov, Irina Piontkovskaya, Dmitri Piontkovski, and Evgeny Burnaev. Published in **Findings of the Association for Computational Linguistics: EMNLP 2022**. 
- **Abstract**: The role of the attention mechanism in encoding linguistic knowledge has received special interest in NLP. However, the ability of the attention heads to judge the grammatical acceptability of a sentence has been underexplored. This paper approaches the paradigm of acceptability judgments with topological data analysis (TDA), showing that the geometric properties of the attention graph can be efficiently exploited for two standard practices in linguistics: binary judgments and linguistic minimal pairs. Topological features enhance the BERT-based acceptability classifier scores by 8%-24% on CoLA in three languages (English, Italian, and Swedish). By revealing the topological discrepancy between attention maps of minimal pairs, we achieve the human-level performance on the BLiMP benchmark, outperforming nine statistical and Transformer LM baselines. At the same time, TDA provides the foundation for analyzing the linguistic functions of attention heads and interpreting the correspondence between the graph features and grammatical phenomena. We publicly release the code and other materials used in the experiments.
- [**Video presentation (EN)**](https://aclanthology.org/2022.findings-emnlp.7.mp4).

### [Topological data analysis for speech processing](https://www.isca-archive.org/interspeech_2023/tulchinskii23_interspeech.pdf)

- A paper by Eduard Tulchinskii, Kristian Kuznetsov, Laida Kushnareva, Daniil Cherniavskii, Serguei Barannikov, Irina Piontkovskaya, Sergey Nikolenko, and Evgeny Burnaev. Published in **Proceedings of INTERSPEECH 2023**.
- **Abstract**: We apply topological data analysis (TDA) to speech classification problems and to the introspection of a pretrained speech model, HuBERT. To this end, we introduce a number of topological and algebraic features derived from Transformer attention maps and embeddings. We show that a simple linear classifier built on top of such features outperforms a fine-tuned classification head. In particular, we achieve an improvement of about 9% accuracy and 5% ERR on four common datasets; on CREMA-D, the proposed feature set reaches a new state of the art performance with accuracy 80.155. We also show that topological features are able to reveal functional roles of speech Transformer heads; e.g., we find the heads capable to distinguish between pairs of sample sources (natural/synthetic) or voices without any downstream fine-tuning. Our results demonstrate that TDA is a promising new approach for speech analysis, especially for tasks that require structural prediction.
- [**Website with appendices, an introduction to TDA, and other additional materials, related to this paper (EN)**](https://topohubert.github.io/speech-topology-webpages/).

### [Intrinsic Dimension Estimation for Robust Detection of AI-Generated Texts](https://proceedings.neurips.cc/paper_files/paper/2023/hash/7baa48bc166aa2013d78cbdc15010530-Abstract-Conference.html)

- A paper by Eduard Tulchinskii, Kristian Kuznetsov, Laida Kushnareva, Daniil Cherniavskii, Sergey Nikolenko, Evgeny Burnaev, Serguei Barannikov, and Irina Piontkovskaya. Published in **Advances in Neural Information Processing Systems 36 (NeurIPS 2023)**.
- **Abstract**: Rapidly increasing quality of AI-generated content makes it difficult to distinguish between human and AI-generated texts, which may lead to undesirable consequences for society. Therefore, it becomes increasingly important to study the properties of human texts that are invariant over text domains and various proficiency of human writers, can be easily calculated for any language, and can robustly separate natural and AI-generated texts regardless of the generation model and sampling method. In this work, we propose such an invariant of human texts, namely the intrinsic dimensionality of the manifold underlying the set of embeddings of a given text sample. We show that the average intrinsic dimensionality of fluent texts in natural language is hovering around the value 9 for several alphabet-based languages and around 7 for Chinese, while the average intrinsic dimensionality of AI-generated texts for each language is ≈ 1.5 lower, with a clear statistical separation between human-generated and AI-generated distributions. This property allows us to build a score-based artificial text detector. The proposed detector's accuracy is stable over text domains, generator models, and human writer proficiency levels, outperforming SOTA detectors in model-agnostic and cross-domain scenarios by a significant margin.

You can see the full list of papers and preprints on [my Google Scholar page](https://scholar.google.com/citations?view_op=list_works&hl=en&hl=en&user=rsTb_hYAAAAJ).

# Selected talks

- [**Popular lecture about chaotic systems** for a Russian-speaking skeptical society, 2014 **(RU)**](https://www.youtube.com/watch?v=RqV54_2wiEs)
- [**A talk based on papers "Artificial Text Detection via Examining the Topology of Attention Maps" and "Intrinsic Dimension Estimation for Robust Detection of AI-Generated Texts"** for the International Laboratory of Algebraic Topology and its Applications (ATA) in HSE University, 2023 **(RU)**](https://www.youtube.com/watch?v=DiIJjigF_I0)

# Blogs

- [**Telegram channel** (RU)](https://t.me/tech_priestess)
- [**Habr** (RU)](https://habr.com/ru/users/tech_priestess/)

# Contacts

- [LinkedIn](https://www.linkedin.com/in/laida-kushnareva/)
- Telegram id: @laida_kushnareva
