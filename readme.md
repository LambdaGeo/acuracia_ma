# Accuracy Assessment of Land Use and Land Cover Classification: A Case Study in the São Luís Intermediate Region with MapBiomas

This repository contains the source code and procedures used in the article: **"Avaliação da Acurácia na Classificação de Uso e Cobertura da Terra: Um Estudo de Caso na Região Intermediária de São Luís com o MapBiomas"**.

The study provides a localized accuracy assessment of [MapBiomas](https://brasil.mapbiomas.org/) data, building upon the original source code developed for the Collection 8 accuracy analysis. This repository is a fork of the original project, specifically adapted for the São Luís intermediate region.

* **Original Repository:** [MapBiomas Accuracy - Collection 8](https://github.com/mapbiomas-brazil/accuraccy/tree/mapbiomas80)
* **Full Article:** [Read it here (DOI: 10.33360/geonordeste.v36i.21680)](https://doi.org/10.33360/geonordeste.v36i.21680)

## Authors

* **Thomas Victor de Sousa Malheiros Rocha**
    * M.Sc. in Environmental Science and Technology
    * Federal University of Maranhão (UFMA)
    * *thomasvictor990@gmail.com*

* **Sérgio Souza Costa**
    * Ph.D. in Applied Computing
    * Associate Professor at the Federal University of Maranhão (UFMA)
    * *sergio.costa@ufma.br*

* **Luís Fernando Cirqueira da Silva Correia**
    * M.Sc. in Environmental Science and Technology
    * Federal University of Tocantins (UFT)
    * *luis.correia@discente.ufma.br*

* **Denilson da Silva Bezerra**
    * Ph.D. in Earth System Science
    * Assistant Professor at the Federal University of Maranhão (UFMA)
    * *denilson.bezerra@ufma.br*

## Getting Started

Follow the steps below to reproduce the analysis:

### 1. Clone the repository
```bash
git clone [https://github.com/LambdaGeo/acuracia_slz.git](https://github.com/LambdaGeo/acuracia_slz.git)
cd acuracia_slz

2. Create a virtual environment
It is highly recommended to use a virtual environment to isolate project dependencies.
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

3. Install dependencies
The necessary libraries are listed in the requirements.txt file.
pip install -r requirements.txt

4. Run the Notebook
The main analysis is performed within a Jupyter Notebook. Ensure your virtual environment is active and launch Jupyter:
jupyter notebook 2_acuracia_sa23z.ipynb

