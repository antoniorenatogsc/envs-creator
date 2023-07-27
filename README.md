# Gerador de Ambientes virtuais

$\space$

> Aqui estão disponíveis os pares de arquivos para criação dos ambientes virtuais compatíveis com os seguintes projetos:



1.   Previa de Faturamento

  *   previa-env-generate.txt
  *   previa-env-packages.txt


$\space$

2.   Atualização diária da Arrecadação

  *   arrecad-env-generate.txt
  *   arrecad-env-packages.txt

$\space$

Os arquivos *generate* serão utlizados para a criação do ambiente virtual, enquanto os arquivos *packages* para a instalação dos pacotes utilizados.


$\space$


## Tutorial

$\space$

>Para a criação do ambiente virtual (*env*) será necessário utilizar o *anaconda prompt*, e declarar uma sequência de comandos. Será feito o passo a passo para a criação do env **app-previa**, que seria utilizado para a aplicação Previa de Faturamento.

1.  Criação do *env*:

        conda create -n app-previa --file https://github.com/antoniorenatogsc/envs-creator/raw/main/previa-env-generate.txt

2.  Ativação do *env*:

        conda activate app-previa

3.  Instalação dos pacotes:

        pip install -r https://github.com/antoniorenatogsc/envs-creator/raw/main/previa-env-packages.txt

---
