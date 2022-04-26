# Afro Chest X-ray

The **Chest X-ray Imaging Dataset for Multiple Cardio-respiratory Diseases in
Ethiopia** (**Afro Chest X-ray** for short) is a project funded by the
[LacunaFund](https://lacunafund.org/) whose aim is to close the gap in health
disparities by fostering interdisciplinary collaborations that create, expand,
or aggregate labeled training and evaluation datasets.


## Description

Cardio-respiratory diseases (cardiovascular and respiratory diseases) are
recognized as serious, worldwide public health concerns that have remained
among the leading causes of death globally. There are not many publicly
available datasets from Africa making it difficult to determine whether tools
and techniques developed in other geographies are as effective in our context.
In this project, we propose to create a labeled chest X-ray dataset for
multiple cardio respiratory diseases in Ethiopia. We will publish the dataset as
open source. We believe this dataset will stimulate researchers and
practitioners in Africa and beyond to push the limits of current methods to
adapt them to the African context and build assistive technologies that could
empower the scarce radiologists.


## Impact

We envision this dataset to have an impact primarily in research and
applications of the medical imaging domain. It will also be essential for
researchers in natural language processes and entrepreneurs in medical imaging.
Below we highlight some relevant research directions:

**Bias in Machine learning:** This dataset will be useful to study the effect
of selection bias in building machine learning models for X-ray images. There
are massive datasets such as
[CheXpert](https://stanfordmlgroup.github.io/competitions/chexpert/) gathered
from different populations. The typical way to leverage models trained on big
dadaist's in one population and apply them to another is through transfer
learning. Our project will enable researchers to study the implications of
selection bias in machine learning. For instance, how models trained on a big
dataset from a different population and adapted to our population at test time
compares with models built on a relatively smaller dataset on the same
population and what effects they have across demography.

**Interpretable Machine Learning:** This dataset will allow researchers to study
interpretive models for image classification. Computer vision models are
interpretable in this case when they classify X-ray images on the basis of
features that a radiologist can directly understand.

**Medical Information Extraction:** Large parts of X-ray reports are in written
text form. Most of them are written in unstructured form. The usage of standard
electronic health records will be convenient to process medical data. Our
dataset can serve as a foundation to build and evaluate such natural language
processing tools.

**Real-world Products:** As shortage of radiologists is a common phenomena in
medically under-served regions such as Ethiopia, we believe entrepreneurs who
want to solve this problem can leverage this dataset as a starting point to
provide services that can improve health care services in rural areas.


## Team

We are a group of researchers and medical professionals from Addis Ababa
University, Tikur Anbessa Specialized Hospital, Ayder Referral Hospital,
Menelik II Comprehensive Specialized Hospital, Kotebe general hospital and
Lesan AI, who are joining hands to build a diverse dataset for
cardio-respiratory diseases in Ethiopia.
