# foco-de-queimadas-brasil
Focos de queimadas no brasil é um sistema gerador de mapas interativos de focos de incêndios do Brasil. Os dados são estraídos da base pública que pode ser adquiridos no link [https://dataserver-coids.inpe.br/queimadas/queimadas/focos/csv/diario/Brasil/](https://dataserver-coids.inpe.br/queimadas/queimadas/focos/csv/diario/Brasil/)

## Requisitos para gerfar os mapas:
- Possuir o Python e o Git no computador
- Saber um pouco de programação python
- Clonar ou fazer download desse repositório

## Criação do ENV e instalação das bibliotecas:
Copie e cole os comandos:
~~~bash
# clona o repo
git clone https://github.com/elizeubarbosaabreu/foco-de-queimadas-brasil.git
# navega para dentro do diretório
cd foco-de-queimadas-brasil
# cria a env
python3 -m venv env
# ativa a env
source env/bin/activate
# instala as dependencias
pip install -r requirements.txt
# Abrir o arquivo no vs code com a extensão jupyter
code mapa.ipynb
~~~

Obs: também da para utilizar com o [Jupyter Notebook](https://jupyter.org/) ou com o [Google Colab](colab.research.google.com).


