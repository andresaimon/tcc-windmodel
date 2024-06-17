# TCC-WINDMODEL

- Este projeto foi desenvolvido através do sistema operacional Ubuntu 22.04.4 LTS, utilizando Python 3.10.12.

- Recomenda-se utilizar um ambiente virtual para execução do Jupyter Notebook. É necessário assegurar sobre a utilização dos dados no mesmo diretório em que for executado o projeto. Para criar um ambiente virtual, o comando abaixo pode ser utilizado:

```bash
python3 -m venv venv
```

- Fonte de dados: https://dados.ons.org.br/dataset/restricao_coff_eolica_detail
- Observação: os dados que estão na pasta "data" foram filtrados para a usina Caetité 2
- É necessário também realizar o download da pasta "natural_earth," que é utilizada para marcar pontos em coordenadas específicas em um mapa.

- Para ativar o ambiente virtual e realizar a instalação das bibliotecas utilizadas no projeto através do gerenciador de pacotes pip, executar o comando:

```bash
source venv/bin/activate
```

- As bibliotecas necessárias para executar os comandos utilizados neste projeto podem ser instaladas com:

```bash
pip install pandas
pip install geopandas
pip install shapely
pip install geobr
pip install numpy
pip install matplotlib
pip install scikit-learn
pip install tensorflow
```
