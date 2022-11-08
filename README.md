# SCC0252/5836 - Visualização Computacional (2022/2)

Monitor:    Breno Lívio Silva de Almeida, brenoslivio@usp.br

Docente:    Maria Cristina Ferreira de Oliveira, cristina@icmc.usp.br

Material base de Eric Macedo Cabral.

---

Para a execução adequada do conteúdo dos Jupyter Notebooks, instale as bibliotecas com suas respectivas versões descritas no arquivo `environment.yml`. Instruções para instalar pelo Conda se encontram no fim deste README.

---

## [Prática 01 - Processamento dos dados](https://nbviewer.org/github/brenoslivio/CompVis_ICMC/blob/main/Pratica_01/Pratica_01.ipynb)

Nesta prática foi introduzida a parte de processamento de dados utilizando ferramentas principais como Pandas, e técnicas diversas para o processamento adequado de dados antes da visualização.

## [Prática 02 - Visualização de dados](https://nbviewer.org/github/brenoslivio/CompVis_ICMC/blob/main/Pratica_02/Pratica_02.ipynb)

Com conhecimentos em processamento de dados, nos voltamos agora com a questão de como visualizar os dados. Exploramos diversos tipo de visualizações de acordo com o tipo dos dados disponíveis, principalmente se baseando em visualizações de catálogos como o [From data to Viz](https://www.data-to-viz.com/).


---

**Instalação das bibliotecas no Linux**

1 - Instalar Miniconda (veja a [documentação](https://docs.conda.io/en/latest/miniconda.html)):

```bash
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh

chmod +x Miniconda3-latest-Linux-x86_64.sh

./Miniconda3-latest-Linux-x86_64.sh

export PATH=~/miniconda3/bin:$PATH
```

2 - Criar ambiente no Conda:

```bash
conda env create -f environment.yml
```

3 - Ativar ambiente:

```bash
conda activate viscomp
```

4 - Desativar ambiente quando dentro dele:

```bash
conda deactivate 
```

5 - Remover ambiente:

```bash
conda env remove -n viscomp
```

**Instalação das bibliotecas no Windows e MacOS**

[Windows](https://conda.io/projects/conda/en/latest/user-guide/install/windows.html) e [MacOS](https://conda.io/projects/conda/en/latest/user-guide/install/macos.html).
