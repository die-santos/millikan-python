# Uso do módulo Python Uncertainties para Cálculos de Incertezas no Experimento da Gota de Millikan

## Módulo Python Uncertainties

O [Módulo Python Uncertainties](https://pythonhosted.org/uncertainties/) é um módulo que manipula cálculos com números e incertezas, por exemplo (2,32 ± 0,02), onde 2,32 é o número e 0,02 é a incerteza. O Módulo Python Uncertainties também pode produzir derivadas de qualquer expressão.

O Módulo Python Uncertainties ameniza o trabalho árduo e complexo dos cálculos de incerteza. Os cálculos com incertezas e/ou derivadas podem ser realizados de forma interativa, a citar [Jupyter Notebook](https://jupyter.org/). Também podem ser realizados em programas escritos na linguagem de programação [Python](https://www.python.org/).

## Instalação do Módulo Python Uncertainties

### Distribuições Linux

Se você tem [pip](https://pypi.org/project/pip/), você pode instalar a versão mais recente com:

```pip install --upgrade uncertainties```

Se você tiver [setuptools](https://pypi.org/project/setuptools/), você poderá instalar/atualizar automaticamente este pacote com:

```easy_install --upgrade uncertainties```

### Windows

Para instalar este pacote com o [conda](https://pypi.org/project/pip/), execute um dos seguintes procedimentos:

```conda install -c conda-forge uncertainties``` 

```conda install -c conda-forge/label/gcc7 uncertainties``` 

```conda install -c conda-forge/label/cf201901 uncertainties```

### MacOS X

 Usuários que utilizam o gerenciador MacPorts podem instalar uncertainties utilizando:
 
 ```sudo port install py**-uncertainties```, onde ```**``` representa a versão do Python. 
 
# Inicialização do Python (módulos math e uncertainties)
 
### Carregando definições e funções matemáticas:

 ```python
 import math
```

### Carregando o módulo Python Uncertainties, que calcula a propagação de incertezas:

```python
import uncertainties import *
import uncertainties.umath import *
```
 
## Definição de parâmetros e fórmulas com incertezas

### Use a função "ufloat" para definir números reais com incertezas ('u' de uncertainties, 'float' de número de ponto flutuante):


```python
a = ufloat(23.45, 0.98); a
23.45+/-0.98
```
 
 ```python
 b = ufloat(21.32, 0.78); b
 21.32+/-0.78
```

```python
c = (a + b); c
print ("Result = {0:.2f}".format(c))
Result = 44.77+/-1.25
```





























 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 

