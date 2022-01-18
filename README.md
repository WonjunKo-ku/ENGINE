## ENGINE: Enhancing Neuroimaging and Genetic Information by Neural Embedding
<p align="center"><img width="100%" src="files/framework.png" /></p>

This repository provides a TensorFlow implementation of the following paper:
> **ENGINE: Enhancing Neuroimaging and Genetic Information by Neural Embedding**<br>
> [Wonjun Ko](https://scholar.google.com/citations?user=Fvzg1_sAAAAJ&hl=ko&oi=ao)<sup>1</sup>, [Wonsik Jung](https://scholar.google.co.kr/citations?user=W4y-TAcAAAAJ&hl=ko)<sup>1</sup>, [Eunjin Jeon](https://scholar.google.com/citations?user=U_hg5B0AAAAJ&hl=ko)<sup>1</sup>, [Ahmad Wisnu Mulyadi](https://scholar.google.co.kr/citations?user=u50w0cUAAAAJ&hl=ko)<sup>1</sup>, [Heung-Il Suk](https://scholar.google.co.kr/citations?user=dl_oZLwAAAAJ&hl=ko)<sup>1, 2</sup><br/>
> (<sup>1</sup>Department of Brain and Cognitive Engineering, Korea University) <br/>
> (<sup>1</sup>Department of Artificial Intelligence, Korea University) <br/>
> Official Version: TBA
> Presented in the 21st IEEE International Conference on Data Mining (ICDM2021 Acceptance rate: 20%)
> 
> **Abstract:** *Recently, deep learning, a branch of machine learning and data mining, has gained widespread acceptance in many applications thanks to its unprecedented successes. In this regard, pioneering studies employed deep learning frameworks for imaging genetics in virtue of their own representation caliber. But,existing approaches suffer from some limitations: (i) exploiting a simple concatenation strategy for joint analysis, (ii) a lack of extension to biomedical applications, and (iii) insufficient and inappropriate interpretations in the viewpoint of both data science and bio-neuroscience. In this work, we propose a novel deep learning framework to tackle the aforementioned issues simultaneously. Our proposed framework learns to effectively represent the neuroimaging and the genetic data jointly, and achieves state-of-the-art performance in its use for Alzheimer’s disease and mild cognitive impairment identification. Further, unlike the existing methods in the literature, the framework allows learning the relation between imaging phenotypes and genotypes in a nonlinear way without any prior neuroscientific knowledge. To demonstrate the validity of our proposed framework, we conducted experiments on a publicly available dataset and analyzed the results from diverse perspectives. Based on our experimental results, we believe that the proposed framework has a great potential to give new insights and perspectives in deep learning-based imaging genetics studies.*

## Dependencies
* [Python 3.6+](https://www.continuum.io/downloads)
* [TensorFlow 2.2.0+](https://www.tensorflow.org/)

## Downloading datasets
To download Alzheimer's disease neuroimaging initiative dataset
* http://www.loni.usc.edu/ADNI

To download AlzGene database
* http://www.alzgene.org

## Citation
TBA

## Usage
`engine.py` contains the proposed deep learning architectures, `utils.py` contains functions used for experimental procedures, and `engine_experiment.py` contains the main experimental functions.

## Acknowledgements
This work was supported by National Research Foundation of Korea (NRF) grant (No. 2019R1A2C1006543) and Institute for Information & Communications Technology Promotion (IITP) grant (No. 2019-0-00079; Department of Artificial Intelligence, Korea University) funded by the Korea government.
