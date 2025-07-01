[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15776455.svg)](https://zenodo.org/doi/10.5281/zenodo.15776455)

# Ancient Greek WSD data
Gold standard datasets for Ancient Greek Word Sense Disambiguation (WSD). Each dataset contains a GLAUx ID and its associated sense: to get the Greek sentence, you have to look up the ID in the [GLAUx corpus](https://github.com/alekkeersmaekers/glaux).

Three of the five datasets (κόσμος, μῦς, ἁρμονία) are **not** original work: they are simply created through linking [the original datasets](https://figshare.com/articles/dataset/Ancient_Greek_semantic_annotation_datasets/7882940) annotated by Alessandro Vatri and Viivi Lähteenoja to the GLAUx corpus, and are added here because some of my past and future experiments on WSD were/will be based on them. Other than that, I did not modify the original datasets (I only dropped some sentences because it was not possible to link them to GLAUx). These datasets also have a third column describing the subsense as present in the original annotation.

The other two datasets (φωνή, γλῶσσα) were annotated by Toon Van Hal, Wouter Mercelis and myself (Alek Keersmaekers), and are described in the paper mentioned below ('How to cite').

# How to cite
If you make use of **the φωνή and/or γλῶσσα datasets**, please refer to:
> Mercelis, Wouter, Toon Van Hal & Alek Keersmaekers. Forthcoming. “Tongue, language or noise? Word Sense Disambiguation in Ancient Greek with corpus-based methods.” Madrid. (Berlin: De Gruyter)

If you make use of **any of the other datasets**, you do not have to cite me, but can just refer to [the original datasets](https://figshare.com/articles/dataset/Ancient_Greek_semantic_annotation_datasets/7882940) in the way their authors prefer.

# License
The φωνή and γλ͂ωσσα data are available under a [CC BY-SA 4.0 license](https://creativecommons.org/licenses/by-sa/4.0/). As for the datasets created by Vatri and Lähteenoja, they provided a [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.
