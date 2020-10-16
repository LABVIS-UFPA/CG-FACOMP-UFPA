# Computação Gráfica e Processamento de Imagens

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/LABVIS-UFPA/CG-FACOMP-UFPA/master)


Passo a passo de configuração do material de aula utilizado nas disciplinas de Computação Gráfica e Processamento de Imagem da FACOMP e PPGCC da UFPA.  
O processo de instalação da biblioteca OpenCV para utilização em python é descrito nesse documento. Alternativamente, uma [versão online está disponível](https://mybinder.org/v2/gh/LABVIS-UFPA/CG-FACOMP-UFPA/master).

## Python e pip
Python é a linguagem de programação em que esse material é feito, e pip é o gerenciador oficial de pacotes do Python, em instalações padrão do windows ele instala junto com o python. Todos os itens que começam com __pip__ podem ser copiados e colados no terminal diretamente.

## Instalação - Windows

* Instalação do interpretador
    * [Baixar Python](https://www.python.org/downloads/windows/) e instalar
    * Colocar Python no PATH
    * Colocar Python/Scripts no PATH

* Depedência necessárias
    * pip install numpy
    * pip install matplotlib

* IDE recomendado para programação de scripts (com posse de e-mail institucional é possível acesso a versão PRO):
    * [Pycharm Community](https://www.jetbrains.com/pycharm/download/#section=windows)

## OpenCV
A biblioteca selecionada para a prática dos algoritmos vistos em sala.

### Instalação Simples (Não suportada oficialmente)
* pip install opencv-python

### Binários do site (Oficial)
* [Baixar instalador](https://sourceforge.net/projects/opencvlibrary/?source=typ_redirect) e instalar
* Colocar cv2.pyd (opencv/build/python/2.7/x64) no site-packages (Python27/Lib/site-packages)

## Jupyter
Jupyter Notebook é uma aplicação web para visualização e execução de código fonte e documentos. É o ambiente utilizado para acompanhar a execução das técnicas de forma interativa.

* pip install jupyter
* pip install ipywidgets
* [Extensão de apresentação - RISE](https://github.com/damianavila/RISE)
* pip install RISE
* jupyter-nbextension install rise --py --sys-prefix
* jupyter-nbextension enable rise --py --sys-prefix

Comando para executar os notebooks (deve ser feito na pasta do projeto): jupyter notebook

## Extras
Direcionamentos extras, com conteúdo para outras plataformas e  

### Git
* [Git](https://git-scm.com/)
* [Github (opcional)](https://desktop.github.com/)
* Endereço do repositório: https://github.com/LABVIS-UFPA/CG-FACOMP-UFPA.git

### Documentação OpenCV
* [OpenCV](https://docs.opencv.org/3.4.1/)
* [Tutorial OpenCV](https://docs.opencv.org/3.4.1/d6/d00/tutorial_py_root.html)

### Tutorial - Compilar do código-fonte
* [Windows](https://docs.opencv.org/3.0-beta/doc/py_tutorials/py_setup/py_setup_in_windows/py_setup_in_windows.html)
* [Ubuntu](https://www.pyimagesearch.com/2016/10/24/ubuntu-16-04-how-to-install-opencv/)
* [macOS](https://www.pyimagesearch.com/2015/06/29/install-opencv-3-0-and-python-3-4-on-osx/)

# Créditos e Contato
* ##### Prof. Dr. Gustavo Resque - gustavoresqueufpa@gmail.com
* ##### MSc. Tiago Araújo  - tiagodavi70@gmail.com
