# ESPERANTO: A Large Dataset for AI Text Detection

## Overview:
The provided dataset is the dataset from our paper titled "[ESPERANTO: Evaluating Synthesized Phrases to Enhance Robustness in AI Detection for Text Origination](https://arxiv.org/abs/2409.14285)."
This dataset has been collected for research purposes and is intended to assist researchers in detecting AI generated text. If you decide to use this dataset, please make sure to cite our papers [ESPERANTO](https://arxiv.org/abs/2409.14285) and [Seeing Through AI's Lens](https://dl.acm.org/doi/abs/10.1145/3648188.3675136). 

## Dataset Description:
ESPERANTO dataset encompasses 72k instances of human-written texts and their corresponding AI-generated versions. Additionally, a further 720k instances were generated from both human and AI-produced content via the technique of back translation (find more details on [ESPERANTO](https://arxiv.org/abs/2409.14285) paper).
This dataset has a diverse range of writing styles, and includes four distinct text categories: News articles to represent journalistic style, paper abstracts to exemplify scientific style, Amazon product reviews to represent the informative review style, and responses to questions of ELI5 forum posted on Reddit to reflect the everyday writing style prevalent on the internet.

## Files' guidance:

$\textcolor{lime}{\<category\>\\_\<LLM\>\\\_\<source\>.csv \\;}$ or $\textcolor{lime}{\<category\>\\\_\<source\>.csv \\;}$: 

$\textcolor{lime}{category\\; }$: Category of text (news, arxiv, ELI5, or review).

$\textcolor{lime}{LLM\\; }$: LLM used to generate AI counterparts of human written texts.

$\textcolor{lime}{source\\; }$: Human written text or AI genearetd text (Human or AI).

## Columns' guidance:

$\textcolor{cyan}{Human\\; }$: Original human written text.

$\textcolor{cyan}{AI\\; }$: AI generated text.

$\textcolor{cyan}{PT\\; }$: Back-translated text of Human or AI column, and Portuguese as intermediate language.

$\textcolor{cyan}{ES\\; }$: Back-translated text of Human or AI column, and Spanish as intermediate language.

$\textcolor{cyan}{FR\\; }$: Back-translated text of Human or AI column, and French as intermediate language.

$\textcolor{cyan}{IT\\; }$: Back-translated text of Human or AI column, and Italian as intermediate language.

$\textcolor{cyan}{ZH\\; }$: Back-translated text of Human or AI column, and Chinese as intermediate language.

$\textcolor{cyan}{NL\\; }$: Back-translated text of Human or AI column, and Dutch as intermediate language.

$\textcolor{cyan}{DA\\; }$: Back-translated text of Human or AI column, and Danish as intermediate language.

$\textcolor{cyan}{JA\\; }$: Back-translated text of Human or AI column, and Japanese as intermediate language.

$\textcolor{cyan}{DE\\; }$: Back-translated text of Human or AI column, and German as intermediate language.

$\textcolor{cyan}{KO\\; }$: Back-translated text of Human or AI column, and Korean as intermediate language.


## Citation:
If you find our dataset useful in your research, please consider citing our papers:
```
@article{ayoobi2024esperanto,
  title={ESPERANTO: Evaluating Synthesized Phrases to Enhance Robustness in AI Detection for Text Origination},
  author={Ayoobi, Navid and Knab, Lily and Cheng, Wen and Pantoja, David and Alikhani, Hamidreza and Flamant, Sylvain and Kim, Jin and Mukherjee, Arjun},
  journal={arXiv preprint arXiv:2409.14285},
  year={2024}
}
```

```
@inproceedings{ayoobi2024seeing,
  title={Seeing Through AI's Lens: Enhancing Human Skepticism Towards LLM-Generated Fake News},
  author={Ayoobi, Navid and Shahriar, Sadat and Mukherjee, Arjun},
  booktitle={Proceedings of the 35th ACM Conference on Hypertext and Social Media},
  pages={1--11},
  year={2024}
}
```

## Acknowledgment:
This dataset was collected using the resources provided by [Esperanto Technologies](https://www.esperanto.ai/).

## Contact:
If you have any questions or need further assistance regarding this dataset, please feel free to contact us at nayoobi@cougarnet.uh.edu.
