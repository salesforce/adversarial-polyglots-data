# Adversarial Polyglots (data)
This repository is a companion repository to [`adversarial-polyglots`](https://github.com/salesforce/adversarial-polyglots) and contains data for the paper "[Code-Mixing on Sesame Street: Dawn of the Adversarial Polyglots](https://arxiv.org/abs/2103.09593)" (NAACL-HLT 2021).

Authors: [Samson Tan](https://samsontmr.github.io) and [Shafiq Joty](https://raihanjoty.github.io)

# XNLI<sub>CleanDL</sub> test set
The XNLI<sub>CleanDL</sub> used in our CAT experiments can be found under `XNLI_cleanDL`. In this setting, the premise and hypothesis are randomly chosen from different languages in the original 15 languages. This setting prevents the NLP model from using lexical overlap as a shortcut to doing well on the NLI task.

If you wish to generate variations of this test set, you can use [this script](https://github.com/salesforce/adversarial-polyglots/blob/master/scripts/generate_xnli_cleanDL.py) from the code repository.

# Translated XNLI Data
For the research community's convenience, we release the [XNLI test set](https://cims.nyu.edu/~sbowman/xnli) we translated to 18 other languages using machine-translation models released by [Helsinki-NLP](https://huggingface.co/Helsinki-NLP) under their [OPUS-MT](https://github.com/Helsinki-NLP/Opus-MT) project.

### Languages in the Released Dataset
* Afrikaans (af)
* Albanian(sq)
* Catalan (ca)
* Czech (cs)
* Danish (da)
* Dutch(nl)
* Estonian (et)
* Filipino (tl)
* Finnish (fi)
* Hebrew (he)
* Hungarian (hu)
* Indonesian (id)
* Italian(it)
* Macedonian (mk)
* Romanian (ro)
* Slovak (sk)
* Swedish (sv)
* Ukrainian (uk)


# Bumblebee
The JSONs used by `Bumblebee` in the XNLI setting can be found under `bumblebee_JSONs`.


# Citation
Please cite the following if you use the data in this repository:
```
@inproceedings{tan-joty-2021-code-mixing,
    title = "Code-Mixing on Sesame Street: {D}awn of the Adversarial Polyglots",
    author = "Tan, Samson and Joty, Shafiq",
    booktitle = "Proceedings of the 2021 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies",
    month = jun,
    year = "2021",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2021.naacl-main.282",
    pages = "3596--3616",
}

```
