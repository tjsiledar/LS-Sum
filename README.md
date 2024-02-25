# Synthesize, if you do not have: Effective Synthetic Dataset Creation Strategies for Self-Supervised Opinion Summarization in E-commerce

Paper Link: [Synthesize, if you do not have: Effective Synthetic Dataset Creation Strategies for Self-Supervised Opinion Summarization in E-commerce](https://aclanthology.org/2023.findings-emnlp.899/)

## Abstract
In e-commerce, opinion summarization is the process of condensing the opinions presented in product reviews. However, the absence of large amounts of supervised datasets presents challenges in generating both aspect-specific and general opinion summaries. Existing approaches have attempted to address these challenges through synthetic dataset creation (SDC). However, general opinion summarization models struggle to generate summaries faithful to the input reviews whereas aspect-specific opinion summarization models are limited due to their reliance on human-specified aspects and seed words. To address this, we propose SDC strategies tailored for general and aspect-specific opinion summarization. We experimented on three e-commerce test sets: Oposum+, Amazon, and Flipkart. For general opinion summarization, pre-trained language model (PLM) fine-tuned on our general synthetic dataset surpass the SOTA on average by 2.3 R1 points. Faithfulness evaluation metrics and human evaluations indicate that our model-generated summaries are more faithful to the input compared to others. For aspect-specific opinion summarization, PLM fine-tuned on our aspect-specific synthetic dataset surpass SOTA by ~ 1 R1 point without the aid of any human-specified aspects or seed words.

## Citation
```
@inproceedings{siledar-etal-2023-synthesize,
    title = "Synthesize, if you do not have: Effective Synthetic Dataset Creation Strategies for Self-Supervised Opinion Summarization in {E}-commerce",
    author = "Siledar, Tejpalsingh  and
      Banerjee, Suman  and
      Patil, Amey  and
      Singh, Sudhanshu  and
      Chelliah, Muthusamy  and
      Garera, Nikesh  and
      Bhattacharyya, Pushpak",
    editor = "Bouamor, Houda  and
      Pino, Juan  and
      Bali, Kalika",
    booktitle = "Findings of the Association for Computational Linguistics: EMNLP 2023",
    month = dec,
    year = "2023",
    address = "Singapore",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.findings-emnlp.899",
    doi = "10.18653/v1/2023.findings-emnlp.899",
    pages = "13480--13491",
    abstract = "In e-commerce, opinion summarization is the process of condensing the opinions presented in product reviews. However, the absence of large amounts of supervised datasets presents challenges in generating both aspect-specific and general opinion summaries. Existing approaches have attempted to address these challenges through synthetic dataset creation (SDC). However, general opinion summarization models struggle to generate summaries faithful to the input reviews whereas aspect-specific opinion summarization models are limited due to their reliance on human-specified aspects and seed words. To address this, we propose SDC strategies tailored for general and aspect-specific opinion summarization. We experimented on three e-commerce test sets: Oposum+, Amazon, and Flipkart. For general opinion summarization, pre-trained language model (PLM) fine-tuned on our general synthetic dataset surpass the SOTA on average by 2.3 R1 points. Faithfulness evaluation metrics and human evaluations indicate that our model-generated summaries are more faithful to the input compared to others. For aspect-specific opinion summarization, PLM fine-tuned on our aspect-specific synthetic dataset surpass SOTA by {\textasciitilde} 1 R1 point without the aid of any human-specified aspects or seed words.",
}

```