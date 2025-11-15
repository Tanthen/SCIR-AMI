[![Paper](https://img.shields.io/badge/paper-ACM_Multimedia BNI Track-red)](https://dl.acm.org/doi/abs/10.1145/3746027.3758178)
[![Conference](https://img.shields.io/badge/ACM_Multimedia-2025-blue)](https://acmmm2025.org/)

# SCIR-AMI
This repo is the official implementation of "Ensuring Responses Contain Appropriate Images: Timing Judgment for Multimodal Responses".

# Abstract
The integration of multimodal information, particularly visual content, into dialogue systems has primarily focused on interpreting user-provided inputs, while comparatively little attention has been given to the proactive use of such content to enhance responses. In this paper, we explore a new research direction that addresses this gap by enabling dialogue systems to autonomously determine when and how to supplement textual responses with relevant images, based on conversational context and user intent. To support this goal, we propose AMI (Automated Multimodal Insertion), a novel framework for dynamic, context-aware multimodal supplementation in dialogue. We also introduce RID (Response with Appropriate Image Dataset), a bilingual (Chinese-English) multimodal multi-turn dialogue dataset designed to train and evaluate systems on this capability. RID features fine-grained annotations on image insertion timing and rationale, along with carefully aligned image-text pairs to ensure semantic coherence. Our experiments demonstrate that models trained with RID not only generate more informative and engaging responses, but also exhibit a stronger ability to leverage visual content when it is truly beneficial. These findings highlight the potential of proactive multimodal supplementation and offer new insights for advancing the development of intelligent, human-like dialogue systems. Code and data are available at: https://github.com/Tanthen/SCIR-AMI.


## Citations

If you found this paper useful, citing the paper and dataset would be greatly appreciated.
```
@inproceedings{10.1145/3746027.3758178,
author = {Yang, Hao and Zheng, Tian and Zhao, Yanyan and Qin, Bing},
title = {Ensuring Responses Contain Appropriate Images: Timing Judgment for Multimodal Responses},
year = {2025},
isbn = {9798400720352},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3746027.3758178},
doi = {10.1145/3746027.3758178},
booktitle = {Proceedings of the 33rd ACM International Conference on Multimedia},
pages = {12501–12508},
numpages = {8},
keywords = {multimodal dialog, multimodal large language model, response generation},
location = {Dublin, Ireland},
series = {MM '25}
}
```
