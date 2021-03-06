# XCOPA: A Multilingual Dataset for Causal Commonsense Reasoning

The Cross-lingual Choice of Plausible Alternatives dataset is a benchmark to evaluate the ability of machine learning models to transfer commonsense reasoning across languages. The dataset is the translation and reannotation of the English [**COPA**](https://people.ict.usc.edu/~gordon/copa.html) ([**Roemmele et al. 2011**](#cite)) and covers 11 languages from 11 families and several areas around the globe. The dataset is challenging as it requires both the command of world knowledge and the ability to generalise to new languages. All the details about the creation of XCOPA and the implementation of the baselines are available in the [**paper**](#).

[**Languages**](#languages) | [**Baselines**](#baselines) | [**Cite**](#cite) | [**Paper**](https://ducdauge.github.io/files/xcopa.pdf)

## Examples

| Language | Premise | Question | Choice 1 | Choice 2 |
|---|---|---|---|---|
| qu | Sipasqa cereal mikhunanpi kuruta tarirqan. | Result | Payqa pukunman ñuqñuta churakurqan. | Payqa manam mikhuyta munarqanchu. |
| en | The girl found a bug in her cereal. | Result | She poured milk in the bowl. |She lost her appetite. |
| th | ตาของฉันแดงและบวมฉันร | Cause | องไห | ฉันหัวเราะ |
| en | My eyes became red and puffy. | Cause | I was sobbing. | I was laughing. |

## Languages

| ISO 639-2 | Name | Family | Area<sup>1</sup> |
|---|---|---|---|
| et | Estonian | Uralic | Northern Europe |
| ht | Haitian Creole | French Creole | Carribean |
| id | Indonesian | Austronesian | Southeastern Asia |
| it | Italian | Indo-European | Southern Europe |
| qu | Southern Quechua<sup>2</sup> | Quechuan | Southern America |
| sw | Swahili | Niger-Congo | Eastern Africa |
| ta | Tamil | Dravidian | Southern Asia |
| th | Thai | Kra-Dai | Southeastern Asia |
| tr | Turkish | Turkic | Western Asia |
| vi | Vietnamese | Austroasiatic | Southeastern Asia |
| zh | Mandarin Chinese | Sino-Tibetan | Eastern Asia |

<sup>1</sup> According to the United Nations geoscheme.

<sup>2</sup> Translation by [Irma Alvarez Ccoscco](https://es.wikipedia.org/wiki/Irma_Alvarez_Ccoscco), an Eastern Apurímac Quechua speaker.

## Baselines

![](baselines.png)

## Cite

If you use the data from this repository, please cite both XCOPA ```\cite{ponti2020xcopa}``` and the original COPA paper ```\cite{roemmele2011choice}```.

```
@article{ponti2020xcopa,
  title={{XCOPA: A} Multilingual Dataset for Causal Commonsense Reasoning},
  author={Edoardo M. Ponti, Goran Glava\v{s}, Olga Majewska, Qianchu Liu, Ivan Vuli\'{c} and Anna Korhonen},
  journal={arXiv preprint},
  year={2020},
  url={https://ducdauge.github.io/files/xcopa.pdf}
}

@inproceedings{roemmele2011choice,
  title={Choice of plausible alternatives: An evaluation of commonsense causal reasoning},
  author={Roemmele, Melissa and Bejan, Cosmin Adrian and Gordon, Andrew S},
  booktitle={2011 AAAI Spring Symposium Series},
  year={2011},
  url={https://people.ict.usc.edu/~gordon/publications/AAAI-SPRING11A.PDF},
}
```
