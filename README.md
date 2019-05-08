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

 Usuários que utilizam o gerenciador MacPorts pode instalar uncertainties utilizando:
 
 ```sudo port install py**-uncertainties```, onde ```**``` representa a versão do Python. 
 
 # Manipulando cálculos com números e incertezas
 
 ## Inicialização do Python (módulos math e uncertainties)
 
 ```python
 import math
 import uncertainties import *
 import uncertainties.umath import *
 ```
 
## Definição de parâmetros e fórmulas com incertezas

### Use a função "ufloat" para definir números reais com incertezas ('u' de uncertainties, 'float' de número de ponto flutuante):
 

Distância  𝑑 = (2,50 ± 0,01) 𝑚𝑚  entre as placas do capacitor:

```python
d = ufloat(0.00250,0.00001); d
0.0025+/-1e-05
```
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 

