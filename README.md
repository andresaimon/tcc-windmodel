# TCC-WINDMODEL

- Desenvolvido no sistema operacional Ubuntu 22.04.4 LTS, utilizando Python 3.10.12.

- Instalar ambiente virtual para execução do Jupyter Notebook. Assegurar sobre a utilização dos dados no mesmo diretório em que for executado o projeto.

```bash
python3 -m venv venv
```

- Fonte de dados: https://dados.ons.org.br/dataset/restricao_coff_eolica_detail
- Observação: os dados que estão na pasta data foram filtrados para a usina Caetité 2
- Necessário também realizar o download da pasta natural_earth, que é utilizada para marcar pontos em coordenadas específicas

- Para ativar o ambiente virtual e realizar a instalação das bibliotecas utilizadas no projeto através do gerenciados de pacotes pip, executar o comando:

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
