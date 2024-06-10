# Lifelong Learning for Large Language Models: Resources

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## Contents
- [Pretrained Language Models for Incremental Learning: Survey](#pretrained-language-models-for-incremental-learning-survey)
  - [Contents](#contents)
  - [Introduction](#introduction)
  - [Survey](#survey)
  - [Codebase](#codebase)
  - [Paper](#paper)

## Introduction
This repository collects awesome survey, resource, and paper for Lifelong Learning with Large Language Models. 
Please refer to [this repository](https://github.com/zzz47zzz/pretrained-lm-for-incremental-learning) for implementation.

## Survey
- [Revisiting Class-Incremental Learning with Pre-Trained Models: Generalizability and Adaptivity are All You Need](https://arxiv.org/abs/2303.07338) (arXiv 2023.03)
- [Deep Class-Incremental Learning: A Survey](https://arxiv.org/abs/2302.03648) (arXiv 2023.03)
- [A Comprehensive Survey of Continual Learning: Theory, Method and Application](https://arxiv.org/abs/2302.00487) (arXiv 2023.02)
- [Continual Lifelong Learning in Natural Language Processing: A Survey](https://aclanthology.org/2020.coling-main.574/) (Coling2020)
- [Continual Learning of Natural Language Processing Tasks: A Survey](https://arxiv.org/abs/2211.12701)

## Codebase
- https://github.com/UIC-Liu-Lab/ContinualLM
- https://github.com/aimagelab/mammoth
- https://github.com/zhoudw-zdw/RevisitingCIL
- https://github.com/G-U-N/PyCIL
- https://github.com/ZixuanKe/PyContinual

## Paper

### Content
- [Papers](#papers)
  - [2024](#2024)
  - [2023](#2023)
  - [2022](#2022)
  - [2021](#2023)
  - [2020](#2022)
  - [2019](#2019)
  - [2018](#2018)
  - [2017](#2017)

### Keywords Convention

![](https://img.shields.io/badge/Continual_Vertical_Domain_Pretraining-red) Continual Vertical Domain Pretraining

![](https://img.shields.io/badge/Continual_Language_Domain_Pretraining-orange) Continual Language Domain Pretraining

![](https://img.shields.io/badge/Continual_Temporal_Domain_Pretraining-yellow) Continual Temporal Domain Pretraining

![](https://img.shields.io/badge/Continual_Text_Classification-green) Continual Text Classification

![](https://img.shields.io/badge/Continual_Named_Entity_Recognition-brightgreen) Continual Named Entity Recognition

![](https://img.shields.io/badge/Continual_Relation_Extraction-blue) Continual Relation Extraction

![](https://img.shields.io/badge/Continual_Machine_Translation-violet) Continual Machine Translation

![](https://img.shields.io/badge/Continual_Instruction_Tuning-purple) Continual Instruction-Tuning

![](https://img.shields.io/badge/Continual_Knowledge_Editing-black) Continual Knowledge Editing

![](https://img.shields.io/badge/Continual_Alignment-lightgray) Continual Alignment

![](https://img.shields.io/badge/Retrieval_Based_Lifelong_Learning-beige) Retrieval-Based Lifelong Learning

![](https://img.shields.io/badge/Tool_Based_Lifelong_Learning-khaki) Tool-Based Lifelong Learning


### Papers
#### 2024
- **HOP to the Next Tasks and Domains for Continual Learning in NLP**, AAAI 2024. ![](https://img.shields.io/badge/Continual_Text_Classification-green) [[pdf](https://ojs.aaai.org/index.php/AAAI/article/view/29349/30546
)]

- **Bayesian Parameter-Efficient Fine-Tuning for Overcoming Catastrophic Forgetting**, Preprint 2024. ![](https://img.shields.io/badge/Continual_Text_Classification-green) [[pdf](https://arxiv.org/pdf/2402.12220)] [[Code](https://recherchetts.github.io/bayesian-peft/)]

- **Rehearsal-Free Modular and Compositional Continual Learning for Language Models**, NAACL 2024. ![](https://img.shields.io/badge/Continual_Text_Classification-green) [[pdf](https://arxiv.org/pdf/2404.00790)]

- **Incremental Sequential Labeling: A Tale of Two Shifts**, Preprint 2024. ![](https://img.shields.io/badge/Continual_Named_Entity_Recognition-brightgreen) [[pdf](https://arxiv.org/pdf/2402.10447)]

- **Few-shot Incremental Event Detection**, TALLIP 2024. ![](https://img.shields.io/badge/Continual_Named_Entity_Recognition-brightgreen) [[pdf](https://dl.acm.org/doi/pdf/10.1145/3634747)]

- **Self-generated Replay Memories for Continual Neural Machine Translation**, Preprint 2024. ![](https://img.shields.io/badge/Continual_Machine_Translation-violet) [[pdf](https://arxiv.org/pdf/2403.13130)] [[Code](https://github.com/m-resta/sg-rep)]

- **F-MALLOC: Feed-forward Memory Allocation for Continual Learning in Neural Machine Translation**, NAACL 2024. ![](https://img.shields.io/badge/Continual_Machine_Translation-violet) [[pdf](https://arxiv.org/pdf/2404.04846)] [[Code](https://github.com/WJMacro/ContinualMT)]


#### 2023
- **Mitigating Catastrophic Forgetting in Task-Incremental Continual Learning with Adaptive Classification Criterion**, Preprint 2023. ![](https://img.shields.io/badge/Continual_Text_Classification-green) [[pdf](https://arxiv.org/pdf/2305.12270)]

- **Learn or Recall? Revisiting Incremental Learning with Pre-trained Language Models**, Preprint 2023. ![](https://img.shields.io/badge/Continual_Text_Classification-green) ![](https://img.shields.io/badge/Continual_Named_Entity_Recognition-brightgreen) ![](https://img.shields.io/badge/Continual_Relation_Extraction-blue) [[pdf](https://arxiv.org/pdf/2312.07887)] [[Code](https://github.com/zzz47zzz/pretrained-lm-for-incremental-learning)]

- **Rehearsal-free Continual Language Learning via Efficient Parameter Isolation**, ACL 2023. ![](https://img.shields.io/badge/Continual_Text_Classification-green) [[pdf](https://aclanthology.org/2023.acl-long.612.pdf)] [[Code](https://github.com/Dicer-Zz/EPI)]

- **Class-Incremental Learning based on Label Generation**, ACL 2023. ![](https://img.shields.io/badge/Continual_Text_Classification-green) [[pdf](https://aclanthology.org/2023.acl-short.109.pdf)] [[Code](https://github.com/shaoyijia/VAG)]

- **Overcoming Catastrophic Forgetting in Massively Multilingual Continual Learning**, ACL (Findings) 2023. ![](https://img.shields.io/badge/Continual_Text_Classification-green) [[pdf](https://aclanthology.org/2023.findings-acl.48.pdf)]

- **InfoCL: Alleviating Catastrophic Forgetting in Continual Text Classification from An Information Theoretic Perspective**, EMNLP 2023. ![](https://img.shields.io/badge/Continual_Text_Classification-green) [[pdf](https://aclanthology.org/2023.findings-emnlp.969.pdf)] [[Code](https://github.com/Yifan-Song793/InfoCL)]

- **ConPET: Continual Parameter-Efficient Tuning for Large Language Models**, Preprint 2023. ![](https://img.shields.io/badge/Continual_Named_Entity_Recognition-brightgreen) [[pdf](https://arxiv.org/pdf/2309.14763)] [[Code](https://github.com/Raincleared-Song/ConPET)]

- **A Neural Span-Based Continual Named Entity Recognition Model**, AAAI 2023. ![](https://img.shields.io/badge/Continual_Named_Entity_Recognition-brightgreen) [[pdf](https://ojs.aaai.org/index.php/AAAI/article/view/26638/26410)] [[Code](https://github.com/Qznan/SpanK)]

- **Learning “O” Helps for Learning More： Handling the Unlabeled Entity Problem for Class-incremental NER**, ACL 2023. ![](https://img.shields.io/badge/Continual_Named_Entity_Recognition-brightgreen) [[pdf](https://aclanthology.org/2023.acl-long.328.pdf)] [[Code](https://github.com/rtmaww/O_CILNER)]

- **Teamwork Is Not Always Good： An Empirical Study of Classifier Drift in Class-incremental Information Extraction**, ACL (Findings) 2023. ![](https://img.shields.io/badge/Continual_Named_Entity_Recognition-brightgreen) ![](https://img.shields.io/badge/Continual_Relation_Extraction-blue) [[pdf](https://aclanthology.org/2023.findings-acl.141.pdf)] [[Code](https://github.com/VT-NLP/ICE)]

- **ProtoNER： Few Shot Incremental Learning for Named Entity Recognition Using Prototypical Networks**, BPM 2023. ![](https://img.shields.io/badge/Continual_Named_Entity_Recognition-brightgreen) [[pdf](https://arxiv.org/pdf/2310.02372)]

- **Task Relation Distillation and Prototypical Pseudo Label for Incremental Named Entity Recognition**, CIKM 2023. ![](https://img.shields.io/badge/Continual_Named_Entity_Recognition-brightgreen) [[pdf](https://arxiv.org/pdf/2308.08793)] [[Code](https://github.com/BladeDancer957/INER_RDP)]

- **Continual Named Entity Recognition without Catastrophic Forgetting**, CIKM 2023. ![](https://img.shields.io/badge/Continual_Named_Entity_Recognition-brightgreen) [[pdf](https://aclanthology.org/2023.emnlp-main.509.pdf)] [[Code](https://github.com/BladeDancer957/CPFD)]

- **SKD-NER:Continual Named Entity Recognition via Span-based Knowledge Distillation with Reinforcement Learning**, EMNLP 2023. ![](https://img.shields.io/badge/Continual_Named_Entity_Recognition-brightgreen) [[pdf](https://aclanthology.org/2023.emnlp-main.413.pdf)]

- **Novel Slot Detection With an Incremental Setting**, EMNLP (Findings) 2023. ![](https://img.shields.io/badge/Continual_Named_Entity_Recognition-brightgreen) [[pdf](https://aclanthology.org/2023.findings-emnlp.53.pdf)] [[Code](https://github.com/cs-liangchen-work/NovelIE)]

- **Incremental event detection via an improved knowledge distillation based model**, Neurocomputing 2023. ![](https://img.shields.io/badge/Continual_Named_Entity_Recognition-brightgreen) [[pdf](https://pdf.sciencedirectassets.com/271597/1-s2.0-S0925231223X00289/1-s2.0-S0925231223006422/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJGMEQCIEK1bj6Ly8ruhs9a2Zb2c5uJ49vKzMhJlcbiIbJJpcIZAiAFc1xzJtgK%2FpO%2Fkbz2KJxccOqTyVgGBW7HZ%2BEDgnGcVyq8BQjv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAUaDDA1OTAwMzU0Njg2NSIMWcVdnvyvyvCOf613KpAFTU%2FIhOI61FrBYfhW7wvTWc9Iia5pvrE5PmD2tHyfFtCTvkgVYnDSXfnIsGK%2FZMF0jZARLZ5NlXyPfR1%2B7HZiZ1vaDvadAfG0sLKtY%2ByplTKXA0FzrfRBcj0oG6%2F90Kf7bKQbj6eN3JexNRUIHneHOWcrlFHbZYuIroDvXNKa9ieEBj0pDBMFckBbvc%2BwuNzsZbipC5581zjP4joiiPf1oxw1VaClYKxGzRsyZGIwN5UxNX3kWxuAccBS%2FSDRcA2XpIg8wPEVT16FFSYmrK2tZ2tk2OjKGIu66Md9nUS4YV3BK5SCVGEfTug18d5Etwn%2FpTouhyVBcjUDF0ZR6bKREbFJyQQa6fC2W%2B62JmyYLxu2QSmqI%2F8SBV0a5C7KaYxiqHl0Ot4Yy%2BsIRe8zFkyw1EzLC%2BZEMED5KLyDztFn15mYnLdUu9sIrUBf6cXvmSzhDi7%2FSou7Teww4YFQwdQ6bnfyRZgeF%2B5BKli9d9WUWZmQE5Hp%2FAcQxGtdFCMiOkiB31uIbcbaBIu4%2Fg1WzNj0dtyu%2Fdrxahce2QdqyXpV5fLMepPzvNR1n6TzAX6K0otDDa3tX%2Fd%2Bzwe1TRX7DpkDDuC5yFWnZOAT7lGssLMH9aHZf0SZSv1JPxHk41ZY9MXiXXFqawtL1%2BcIoxoKVN3wJF6BGfcp3Yz98jv13D316X841Haitq85oBuwXCdb9QH6nKDZFn2NhinCVC5UhiRGTJItPxKdO9RKAsdrjX3lhJHiMT%2FOhUWAf%2BYvPdV1ukxUfgiA0ZHcqQ8AL4Rg1%2B9GPZZvTjgr6HbVRzsGUgNbRE38XJy0RAfuBPfOQcyyC2q6Y%2BdXj9Qxhcj7cErgw2Y15s4Gbu9O3RT3YDCmIOGCU4YwweeisgY6sgGyC5MQGJB5takEqm5cLtpQC2HodtOM70AANOdIQSGE%2Fl1d9JswbIXx2nyGlFFmxm6426QLCkdHe5PHWAhpLkmKWyN6X8krQ3H5617W%2FUe1cTM0SLHkKi6SoDe0QfpBiTNpKPQn%2BuczGYP3YeFGybQEaet5nWtK0YOd41MCQO2wWVHK1CuLQwJ9ZYlef4Aq9wtDXVpCSRaGfc1TmmolhHDOfC7YZY7dQNtHVz8GPYGHLjBp&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20240518T150903Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&sX-Amz-Credential=ASIAQ3PHCVTYRJJBNUDJ%2F20240518%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=958666ecc95b23232cf77236b4e51d1057271ab605b99aaf87ac92cfc0f904a7&hash=9b3545292353e6576b86cbb5b53f1cf0563d2f2676821cdfd397782aa16669d9&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0925231223006422&tid=spdf-130a1314-9dc9-458d-8716-9d499548602c&sid=3682f588522cd0438f8ac403cedfc1eb08f0gxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=0d095d565b0d0355&rr=885cc41e4dff84b5&cc=cn)]

- **Decomposing Logits Distillation for Incremental Named Entity Recognition**, SIGIR 2023. ![](https://img.shields.io/badge/Continual_Named_Entity_Recognition-brightgreen) [[pdf](https://dl.acm.org/doi/pdf/10.1145/3539618.3591970)]

- **Consistent Prototype Learning for Few-Shot Continual Relation Extraction**, ACL 2023. ![](https://img.shields.io/badge/Continual_Relation_Extraction-blue) [[pdf](https://aclanthology.org/2023.acl-long.409.pdf)] [[Code](https://github.com/XiudiChen/ConPL)]

- **Enhancing Continual Relation Extraction via Classifier Decomposition**, ACL (Findings) 2023. ![](https://img.shields.io/badge/Continual_Relation_Extraction-blue) [[pdf](https://aclanthology.org/2023.findings-acl.638.pdf)] [[Code](https://github.com/hemingkx/CDec)]

- **Improving Continual Relation Extraction by Distinguishing Analogous Semantics**, ACL 2023. ![](https://img.shields.io/badge/Continual_Relation_Extraction-blue) [[pdf](https://aclanthology.org/2023.acl-long.65.pdf)] [[Code](https://github.com/nju-websoft/CEAR)]

- **Serial Contrastive Knowledge Distillation for Continual Few-shot Relation Extraction**, ACL (Findings) 2023. ![](https://img.shields.io/badge/Continual_Relation_Extraction-blue) [[pdf](https://aclanthology.org/2023.findings-acl.804.pdf)] [[Code](https://github.com/nju-websoft/SCKD)]

- **ICA-Proto： Iterative Cross Alignment Prototypical Network for Incremental Few-Shot Relation Classification**, EACL (Findings) 2023. ![](https://img.shields.io/badge/Continual_Relation_Extraction-blue) [[pdf](https://aclanthology.org/2023.findings-eacl.171.pdf)]

- **Serial Contrastive Knowledge Distillation for Continual Few-shot Relation Extraction**, ACL (Findings) 2023. ![](https://img.shields.io/badge/Continual_Relation_Extraction-blue) [[pdf](https://aclanthology.org/2023.findings-acl.804.pdf)] [[Code](https://github.com/nju-websoft/SCKD)]

- **Continual Knowledge Distillation for Neural Machine Translation**, ACL 2023. ![](https://img.shields.io/badge/Continual_Machine_Translation-violet) [[pdf](https://aclanthology.org/2023.acl-long.443.pdf)] [[Code](https://github.com/THUNLP-MT/CKD)]

- **Knowledge Transfer in Incremental Learning for Multilingual Neural Machine Translation**, ACL 2023. ![](https://img.shields.io/badge/Continual_Machine_Translation-violet) [[pdf](https://aclanthology.org/2023.acl-long.852.pdf)] [[Code](https://github.com/THUNLP-MT/ktnmt)]

- **Continual Learning for Multilingual Neural Machine Translation via Dual Importance-based Model Division**, EMNLP 2023. ![](https://img.shields.io/badge/Continual_Machine_Translation-violet) [[pdf](https://aclanthology.org/2023.emnlp-main.736.pdf)] [[Code](https://github.com/raburabu91/BVP4CL)]


#### 2022
- **Continual Few-shot Intent Detection**, COLING 2022. ![](https://img.shields.io/badge/Continual_Text_Classification-green) [[pdf](https://aclanthology.org/2022.coling-1.26.pdf)]

- **Incremental Intent Detection for Medical Domain with Contrast Replay Networks**, ACL (Findings) 2022. ![](https://img.shields.io/badge/Continual_Text_Classification-green) [[pdf](https://aclanthology.org/2022.findings-acl.280.pdf)]

- **Continual training of language models for few-shot learning**, EMNLP 2022. ![](https://img.shields.io/badge/Continual_Text_Classification-green) [[pdf](https://aclanthology.org/2022.emnlp-main.695.pdf)]

- **Parameter-efficient Continual Learning Framework in Industrial Real-time Text Classification System**, NAACL 2022. ![](https://img.shields.io/badge/Continual_Text_Classification-green) [[pdf](https://aclanthology.org/2022.naacl-industry.35.pdf)]

- **Prompt Augmented Generative Replay via Supervised Contrastive Learning for Lifelong Intent Detection**, NAACL (Findings) 2022. ![](https://img.shields.io/badge/Continual_Text_Classification-green) [[pdf](https://aclanthology.org/2022.findings-naacl.84.pdf)]

- **Memory Efficient Continual Learning with Transformers**, NIPS 2022. ![](https://img.shields.io/badge/Continual_Text_Classification-green) [[pdf](https://openreview.net/pdf?id=U07d1Y-x2E)]

- **Few-Shot Class-Incremental Learning for Named Entity Recognition**, ACL 2022. ![](https://img.shields.io/badge/Continual_Named_Entity_Recognition-brightgreen) [[pdf](https://aclanthology.org/2022.acl-long.43.pdf)]

- **Learn and Review： Enhancing Continual Named Entity Recognition via Reviewing Synthetic Samples**, ACL (Findings) 2022. ![](https://img.shields.io/badge/Continual_Named_Entity_Recognition-brightgreen) [[pdf](https://aclanthology.org/2022.findings-acl.179.pdf)]

- **Incremental Prompting：Episodic Memory Prompt for Lifelong Event Dectection**, COLING 2022. ![](https://img.shields.io/badge/Continual_Named_Entity_Recognition-brightgreen) [[pdf](https://aclanthology.org/2022.coling-1.189.pdf)] [[Code](https://github.com/VT-NLP/Incremental_Prompting)]

- **Distilling Causal Effect from Miscellaneous Other-Class for Continual Named Entity Recognition**, EMNLP 2022. ![](https://img.shields.io/badge/Continual_Named_Entity_Recognition-brightgreen) [[pdf](https://aclanthology.org/2022.emnlp-main.236.pdf)] [[Code](https://github.com/zzz47zzz/CFNER)]

- **BNU： A Balance-Normalization-Uncertainty Model for Incremental Event Detection**, ICASSP 2022. ![](https://img.shields.io/badge/Continual_Named_Entity_Recognition-brightgreen) [[pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9747708)]

- **Similarity-Driven Adaptive Prototypical Network for Class-incremental Few-shot Named Entity Recognition**, ICTAI 2022. ![](https://img.shields.io/badge/Continual_Named_Entity_Recognition-brightgreen) [[pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10097986)]

- **HEFT： A History-Enhanced Feature Transfer framework for incremental event detection**, KBS 2022. ![](https://img.shields.io/badge/Continual_Named_Entity_Recognition-brightgreen) [[pdf](https://pdf.sciencedirectassets.com/271505/1-s2.0-S0950705122X00166/1-s2.0-S0950705122008061/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJHMEUCIDGej%2BZ9m2J2ytK5w36KWKcEv3gThuaWIHufatpHidkTAiEAjJYEcHYhW01TAkVvFeUvqUbfrBdHwQcYMnxxmjet93YquwUI7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAFGgwwNTkwMDM1NDY4NjUiDKzZZZZI3SMAHjMbuyqPBaAhyjLItjCl3zFmft%2BxDfWV2MfRrhy5%2Bdf5DpBoJjDrC4IrsKr5iocT0pD31pIiLMMSElG7KE84hTmE8dgkX5%2FRloLcvTuKCjuVs6fVJvRCspsveqr7upGzXl0DgKrMbCsGO%2BegT%2BDP7YcoHveQbZIryNAucTz7YJAU5NzAaF9ZbMV8UkiGfiVeo4PzK7hfliJuIYhpmCOE9PQsmuXlOlJIojXndgiJwW0x53Zk6zji9oxbbtHkCtDtG4fmK%2BAcjjarclM5Ih9iSHSU32N1Ez8FTGLt98Ta6T4AdIUjZynMR%2FVQCg4s9w%2BZup%2FUma3vsKvCdUGTNLAhugf6k9Y2p5%2FkEpyzxAuVAE5cbkthVbfZwAbpQZZlausIsq8zZoj%2F9A9liO8h4L4s%2BJ5WVA5sH3WTMAlVwFoW6nNIGSj3tbhWWudVvkrBcqTW5DnG%2BTSKH4Qns%2FEweyusiLmzx0eTQB9JjVdwgDs5iFO2KvQdmn%2F2NfLjSKJY1mO0TN%2BLn1f5G%2FyCBmthNJyNz0dyrUzkt5u%2Fvp6SBXXbwezklK%2FZJiAgKK7m4P4ocS%2B5yC%2B1ueXS2REcznQRFRzTIhU6kcT4uDt92wqIIaN23jQ16QVgn8U27%2Fn1kzEFqqh5FFly3r6zYOFgNtz8OuX9vdCif3pIwuZb9TDpCdQ6mIC7z3pWHzFwvHPBhmzHmI7WMSn%2FROlEXid2%2FpzFSe4laBDIgQv0yDa8BxlKHlZxt3vHi51z%2FXgZRBttoRsnU4H2cBPhUBoxDvcgsEntJF%2Br4Lm2DTFOm2mwKiND7tBcijwxErP9caOOZ6ZdLSeU9NYXYdrC8yMhUIFEtG9ysZaFLBp6AjQeCNIJsXrXrbBmmh3t8xukPLUwrumisgY6sQFh7rJYe3CCejqSjvILn5KdJ%2BE%2BiPN1D7zZ%2Fun1nTwKoH3U%2FktdVr%2FOmjv22mOdUduSvEv69pq97JwEYOmlIp42GlobQ9kzOriOiJ727M92UfjMhSPrwTcSmvLeTb54gLhmcLuiS0WZBdUfx%2F2XEYuahDYuLrcbCTH2m4InSytNbOeAWWIlTAnosDjEsHd2JlSk1V70ej13StBo5ZXYjfNllXbd2R%2Fw1kMOoYZTAK9QI9E%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20240518T150930Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY5532AY56%2F20240518%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=0f8e27f71a9a02306eee68911d2f0c2052ddbb046c6b91e476011c97eb80ec65&hash=e2913561864f523ed8763a508a574ea73fa2022b9b6490a137d91cdc987b830a&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0950705122008061&tid=spdf-4425fead-8428-44a4-85ca-dc5f5464a640&sid=3682f588522cd0438f8ac403cedfc1eb08f0gxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=0d095d565b0d0355&rr=885cc4c5cb9284b5&cc=cn)]

- **Consistent Representation Learning for Continual Relation Extraction**, ACL (Findings) 2022. ![](https://img.shields.io/badge/Continual_Relation_Extraction-blue) [[pdf](https://aclanthology.org/2022.findings-acl.268.pdf)] [[Code](https://github.com/thuiar/CRL)]

- **Continual Few-shot Relation Learning via Embedding Space Regularization and Data Augmentation**, ACL 2022. ![](https://img.shields.io/badge/Continual_Relation_Extraction-blue) [[pdf](https://aclanthology.org/2022.acl-long.198.pdf)] [[Code](https://github.com/qcwthu/Continual_Fewshot_Relation_Learning)]

- **Less is More: Rethinking State-of-the-art Continual Relation Extraction Models with a Frustratingly Easy but Effective Approach**, Preprint 2022. ![](https://img.shields.io/badge/Continual_Relation_Extraction-blue) [[pdf](https://aclanthology.org/2022.acl-long.198.pdf)]

- **Improving continual relation extraction through prototypical contrastive learning**, COLING 2022. ![](https://img.shields.io/badge/Continual_Relation_Extraction-blue) [[pdf](https://aclanthology.org/2022.coling-1.163.pdf)] [[Code](https://github.com/PaperDiscovery/CRECL)]

- **Learning Robust Representations for Continual Relation Extraction via Adversarial Class Augmentation**, EMNLP 2022. ![](https://img.shields.io/badge/Continual_Relation_Extraction-blue) [[pdf](https://aclanthology.org/2022.emnlp-main.420.pdf)] [[Code](https://github.com/Wangpeiyi9979/ACA)]

- **Prompt-based prototypical framework for continual relation extraction**, TASLP 2022. ![](https://img.shields.io/badge/Continual_Relation_Extraction-blue) [[pdf](https://dl.acm.org/doi/pdf/10.1109/TASLP.2022.3199655)]

- **Overcoming Catastrophic Forgetting beyond Continual Learning： Balanced Training for Neural Machine Translation**, ACL 2022. ![](https://img.shields.io/badge/Continual_Machine_Translation-violet) [[pdf](https://aclanthology.org/2022.acl-long.143.pdf)] [[Code](https://github.com/ictnlp/COKD)]

- **CLLE： A Benchmark for Continual Language Learning Evaluation in Multilingual Machine Translation**, EMNLP (Findings) 2022. ![](https://img.shields.io/badge/Continual_Machine_Translation-violet) [[pdf](https://aclanthology.org/2022.findings-emnlp.30.pdf)] [[Code](https://github.com/HITSZ-HLT/CLLE)]

- **Continual Learning of Neural Machine Translation within Low Forgetting Risk Regions**, EMNLP 2022. ![](https://img.shields.io/badge/Continual_Machine_Translation-violet) [[pdf](https://aclanthology.org/2022.emnlp-main.111.pdf)] [[Code](https://github.com/ictnlp/LFR-NMT)]

- **Entropy-Based Vocabulary Substitution for Incremental Learning in Multilingual Neural Machine Translation**, EMNLP 2022. ![](https://img.shields.io/badge/Continual_Machine_Translation-violet) [[pdf](https://aclanthology.org/2022.emnlp-main.720/)] [[Code](https://github.com/koukaiu/evs)]


#### 2021
- **Learning to Solve NLP Tasks in an Incremental Number of Languages**, ACL 2021. ![](https://img.shields.io/badge/Continual_Text_Classification-green) [[pdf](https://aclanthology.org/2021.acl-short.106.pdf)]

- **Adapting BERT for Continual Learning of a Sequence of Aspect Sentiment Classification Tasks**, NAACL 2021. ![](https://img.shields.io/badge/Continual_Text_Classification-green) [[pdf](https://aclanthology.org/2021.naacl-main.378.pdf)] [[Code](https://github.com/ZixuanKe/PyContinual)]

- **CLASSIC： Continual and Contrastive Learning of Aspect Sentiment Classification Tasks**, EMNLP 2021. ![](https://img.shields.io/badge/Continual_Text_Classification-green) [[pdf](https://aclanthology.org/2021.emnlp-main.550.pdf)] [[Code](https://github.com/ZixuanKe/PyContinual)]

- **Continual Learning for Text Classification with Information Disentanglement Based Regularization**, NAACL 2021. ![](https://img.shields.io/badge/Continual_Text_Classification-green) [[pdf](https://aclanthology.org/2021.naacl-main.218.pdf)] [[Code](https://github.com/GT-SALT/IDBR)]

- **Hyperparameter-free Continuous Learning for Domain Classification in Natural Language Understanding**, NAACL 2021. ![](https://img.shields.io/badge/Continual_Text_Classification-green) [[pdf](https://aclanthology.org/2021.naacl-main.212.pdf)] [[Code](https://github.com/tinghua-code/CCFI)]

- **Incremental Few-shot Text Classification with Multi-round New Classes： Formulation, Dataset and System**, NAACL 2021. ![](https://img.shields.io/badge/Continual_Text_Classification-green) [[pdf](https://aclanthology.org/2021.naacl-main.106.pdf)] [[Code](https://github.com/congyingxia/IncrementalFSTC)]

- **Achieving Forgetting Prevention and Knowledge Transfer in Continual Learning**, NIPS 2021. ![](https://img.shields.io/badge/Continual_Text_Classification-green) [[pdf](https://proceedings.neurips.cc/paper_files/paper/2021/file/bcd0049c35799cdf57d06eaf2eb3cff6-Paper.pdf)] [[Code](https://github.com/ZixuanKe/PyContinual)]

- **Iterative Network Pruning with Uncertainty Regularization for Lifelong Sentiment Classification**, SIGIR 2021. ![](https://img.shields.io/badge/Continual_Text_Classification-green) [[pdf](https://dl.acm.org/doi/pdf/10.1145/3404835.3462902)] [[Code](https://github.com/siat-nlp/IPRLS)]

- **Lifelong Intent Detection via Multi-Strategy Rebalancing**, Preprint 2021. ![](https://img.shields.io/badge/Continual_Text_Classification-green) [[pdf](https://arxiv.org/pdf/2106.11197)]

- **Lifelong Knowledge-Enriched Social Event Representation Learning**, EACL 2021. ![](https://img.shields.io/badge/Continual_Text_Classification-green) [[pdf](https://aclanthology.org/2021.eacl-main.317.pdf)] [[Code](https://pralav.github.io/lifelong_eventrep/?c=10)]

- **Lifelong Learning of Hate Speech Classification on Social Media**, NAACL 2021. ![](https://img.shields.io/badge/Continual_Text_Classification-green) [[pdf](https://aclanthology.org/2021.naacl-main.183.pdf)]

- **Continual Learning for Named Entity Recognition**, AAAI 2021. ![](https://img.shields.io/badge/Continual_Named_Entity_Recognition-brightgreen) [[pdf](https://ojs.aaai.org/index.php/AAAI/article/view/17600/17407)]

- **Lifelong Event Detection with Knowledge Transfer**, EMNLP 2021. ![](https://img.shields.io/badge/Continual_Named_Entity_Recognition-brightgreen) [[pdf](https://aclanthology.org/2021.emnlp-main.428.pdf)] [[Code](https://github.com/Perfec-Yu/Lifelong-ED)]

- **Curriculum-meta learning for order-robust continual relation extraction**, AAAI 2021. ![](https://img.shields.io/badge/Continual_Relation_Extraction-blue) [[pdf](https://ojs.aaai.org/index.php/AAAI/article/view/17241/17048)] [[Code](https://github.com/wutong8023/AAAI-CML)]

- **Refining Sample Embeddings with Relation Prototypes to Enhance Continual Relation Extraction**, ACL 2021. ![](https://img.shields.io/badge/Continual_Relation_Extraction-blue) [[pdf](https://aclanthology.org/2021.acl-long.20.pdf)] [[Code](https://github.com/fd2014cl/RP-CRE)]

- **Continual learning in multilingual nmt via language-specific embeddings**, WMT 2021. ![](https://img.shields.io/badge/Continual_Machine_Translation-violet) [[pdf](https://aclanthology.org/2021.wmt-1.62/)]

- **Continual Learning for Neural Machine Translation**, NAACL 2021. ![](https://img.shields.io/badge/Continual_Machine_Translation-violet) [[pdf](https://aclanthology.org/2021.naacl-main.310/)] [[Code](https://github.com/caoy1996/CLNMT)]

- **Towards Continual Learning for Multilingual Machine Translation via Vocabulary Substitution**, NAACL 2021. ![](https://img.shields.io/badge/Continual_Machine_Translation-violet) [[pdf](https://aclanthology.org/2021.naacl-main.93.pdf)]


#### 2020
- **Incremental Event Detection via Knowledge Consolidation Networks**, EMNLP 2020. ![](https://img.shields.io/badge/Continual_Named_Entity_Recognition-brightgreen) [[pdf](https://aclanthology.org/2020.emnlp-main.52.pdf)] [[Code](https://github.com/CPF-NLPR/IncrementalED)]

- **Continual Relation Learning via Episodic Memory Activation and Reconsolidation**, ACL 2020. ![](https://img.shields.io/badge/Continual_Relation_Extraction-blue) [[pdf](https://aclanthology.org/2020.acl-main.573.pdf)] [[Code](https://github.com/thunlp/ContinualRE)]

- **Findings of the First Shared Task on Lifelong Learning Machine Translation**, WMT 2020. ![](https://img.shields.io/badge/Continual_Machine_Translation-violet) [[pdf](https://aclanthology.org/2020.wmt-1.2.pdf)]


#### 2019
- **A Progressive Model to Enable Continual Learning for Semantic Slot Filling**, EMNLP 2019. ![](https://img.shields.io/badge/Continual_Named_Entity_Recognition-brightgreen) [[pdf](https://aclanthology.org/D19-1126.pdf)]

- **Meta-Learning Improves Lifelong Relation Extraction**, RepL4NLP 2019. ![](https://img.shields.io/badge/Continual_Relation_Extraction-blue) [[pdf](https://aclanthology.org/W19-4326.pdf)]

- **Sentence Embedding Alignment for Lifelong Relation Extraction**, NAACL 2019. ![](https://img.shields.io/badge/Continual_Relation_Extraction-blue) [[pdf](https://aclanthology.org/N19-1086.pdf)] [[Code](https://github.com/hongwang600/Lifelong_Relation_Detection)]

- **From Bilingual to Multilingual Neural Machine Translation by Incremental Training**, JASIST 2019. ![](https://img.shields.io/badge/Continual_Machine_Translation-violet) [[pdf](https://aclanthology.org/P19-2033.pdf)]


#### 2018
- **Regularized Training Objective for Continued Training for Domain Adaptation in Neural Machine Translation**, NGT 2018. ![](https://img.shields.io/badge/Continual_Machine_Translation-violet) [[pdf](https://aclanthology.org/W18-2705.pdf)] [[Code](https://github.com/khayrallah/OpenNMT-py-reg)]
