# SBBD25-paper-em-llm
Repository with information about the paper "Entity Matching com Large Language Models: estudo comparativo com abordagem de Entity Blocking"

## Orca2 model

### Requirements

Python version: `3.12`

Environment - Packages in `requirements-orca2.txt`:

```
accelerate
google
jupyter
ollama
pandas
protobuf
scikit-learn
sentencepiece
```

Install requirements in a virtual environment with  ```pip install -r requirements-orca2.txt```.

### Notebook

The notebook file `orca2-em.ipynb` works in the way below:

1. Import required packages;
2. Load file of Abt-Buy testset;
3. Get data of products used in testset matchings;
4. Run the Orca2 model 10 times and get the metric values;
5. Calculate the mean of metric values (Precision, Recall and F1-Score) for each class possible in the dataset and the mean of runtime of all 10 executions.

## Paper

Paper named "Entity Matching com Large Language Models: estudo comparativo com abordagem de Entity Blocking" and published at Simpósio Brasileiro de Banco de Dados 2025 ([SBBD 2025](https://sbbd.org.br/2025/)).

<!-- If you need to cite this paper, use the following options:

- BibTex:

```
@INPROCEEDINGS{247828,
    AUTHOR="Rodolfo Bolconte Donato and Tiago Brasileiro Araújo",
    TITLE="Entity Matching com Large Language Models: estudo comparativo com abordagem de Entity Blocking",
    BOOKTITLE="SBBD 2025 - Short Papers () ",
    ADDRESS="",
    DAYS="29-2",
    MONTH="sep",
    YEAR="2025",
    ABSTRACT="Entity Matching é essencial na gestão de dados, identificando informações de diferentes fontes que representam a mesma entidade. Tradicionalmente modelos Pré-Treinados são utilizados para esta tarefa, mas a recente adoção dos Large Language Models (LLMs) em diversas áreas sugere seu potencial na realização da mesma. Este trabalho compara o Ditto, uma abordagem que utiliza técnicas de otimização em conjunto com modelos Pré-Treinados, com o Orca2, um LLM desenvolvido a partir do Llama2 voltado para otimização de raciocínio, que embora apresente resultados iniciais inferiores, é evidente o potencial para, com avanços computacionais futuros, igualar ou superar abordagens pré-treinadas. Nesse sentido, o trabalho visa conduzir estudos experimentais para avaliar a viabilidade do Orca2 na tarefa de Entity Matching, verificando a precisão dos resultados e o desempenho computacional exigido.",
    KEYWORDS="Experiments and analyses",
    URL="http://XXXXX/247828.pdf"
}
``` -->