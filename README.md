# Layout Model Training Corpus
This repository contains the datasets for identification of the layouts like paragraphs, headers, footers, images, tables etc.
>
Please reach out to 📧 nlp-nmt@tarento.com 📧 for any clarification/interpretation/usage of the linked datasets.
>

Dataset Type   |  Version |  Count            |  Corpus Download Link |
:------------- | :-------:|-----------------: | --------------------: |
Layout         | 1.0      | 3,911             | [Layout Dataset](https://layout-mt-corpus.s3-us-west-2.amazonaws.com/layout.zip) |
Cell           | 1.0      | 2,609             | [Cell Dataset](https://layout-mt-corpus.s3-us-west-2.amazonaws.com/cell.zip) |


## Layout Datasets
Source  : https://www.primaresearch.org/datasets/Layout_Analysis and Indian Judicial Judgements
### Description
This dataset is the combination of prima layout dataset(double column) and Indian judicial judgements(single column). It includes various types of layout like paragraph, header, footer, image, table, separator and mathematical formula. 
>
Each image is mapped with a respective XML file(Pascal format) with same name, which contains layout related information like class of layout, coordinates etc.
>
>
>
## Cell Datasets
Source  : https://www.primaresearch.org/datasets/Layout_Analysis and Indian Judicial Judgements
### Description
This dataset is a combination of prima layout dataset(double column) and Indian judicial judgements(single column). It includes only one type of layout table. By using some pre processing other layouts(paragraph, image,header,footer,seperator,mathematical formula) are masked out in the image
>
Each image is mapped with a respective XML file(Pascal format) with same name, which contains table cell level information like class, coordinates etc.

