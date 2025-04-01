# THRONE: An LVLM Hallucination Benchmark
Project page for *THRONE: An Object-based Hallucination Benchmark for the Free-form Generations of Large Vision-Language Models*, a paper published in CVPR 2024.

### TL;DR
Still evaluating your LVLM hallucination on yes-no or multi-choice questions? Nobody uses them this way in real life. Use benchmarks that analyze their free-form output, like THRONE!

### Authors
Prannay Kaul, Zhizhong Li, Hao Yang, Yonatan Dukler, Ashwin Swaminathan, C. J. Taylor, Stefano Soatto

### WIP
This page is a work in progress. Meanwhile, please follow these links:

[[Code](https://github.com/amazon-science/THRONE)] | [[arXiv](https://arxiv.org/abs/2405.05256)] | [[CVF](https://openaccess.thecvf.com/content/CVPR2024/html/Kaul_THRONE_An_Object-based_Hallucination_Benchmark_for_the_Free-form_Generations_of_CVPR_2024_paper.html)] | [[Poster](throne-cvpr-poster.pdf)]


# Abstract

Mitigating hallucinations in large vision-language models (LVLMs) remains an open problem. Recent benchmarks do not address hallucinations in open-ended free-form responses, which we term "Type I hallucinations". Instead, they focus on hallucinations responding to very specific question formats -- typically a multiple-choice response regarding a particular object or attribute -- which we term "Type II hallucinations". Additionally, such benchmarks often require external API calls to models which are subject to change. In practice, we observe that a reduction in Type II hallucinations does not lead to a reduction in Type I hallucinations but rather that the two forms of hallucinations are often anti-correlated. 

To address this, we propose THRONE, a novel object-based automatic framework for quantitatively evaluating Type I hallucinations in LVLM free-form outputs. We use public language models (LMs) to identify hallucinations in LVLM responses and compute informative metrics. By evaluating a large selection of recent LVLMs using public datasets, we show that an improvement in existing metrics do not lead to a reduction in Type I hallucinations, and that established benchmarks for measuring Type I hallucinations are incomplete. Finally, we provide a simple and effective data augmentation method to reduce Type I and Type II hallucinations as a strong baseline. 
