# Criação e Análise de RFV

Este é um projeto de criação de um Webapp que calcula o RFV do Banco de Dados proposto.

## O que é RFV ?

RFV significa **recência, frequência, valor** e é utilizado para segmentação de clientes baseado no comportamento 
    de compras dos clientes e agrupa eles em clusters parecidos. Utilizando esse tipo de agrupamento podemos realizar 
    ações de marketing e CRM melhores direcionadas, ajudando assim na personalização do conteúdo e até a retenção de clientes.

Para cada cliente é preciso calcular cada uma das componentes abaixo:

    - Recência (R): Quantidade de dias desde a última compra.
    - Frequência (F): Quantidade total de compras no período.
    - Valor (V): Total de dinheiro gasto nas compras do período.

## Utilização

Para visualizar o webapp, acesse o link abaixo:
[Webapp RFV](https://shop-marketing.onrender.com)

### Requisistos

Para executar o webapp localmente ou contribuir para o projeto, você precisará das seguintes dependências:

- Python 3.x
- Bibliotecas Python (listadas no arquivo `requirements.txt`)

### Instalação

Para instalar o webapp em sua máquina, siga estas etapas:

1. Abra o terminal na pasta em que deseja que o repositório seja instalado.

 - bash
 - git clone https://github.com/KaioPauloSilva/EBAC_Shop-Marketing-Data.git
 - cd EBAC_Shop-Marketing-Data
 - pip install -r requirements.txt

### Executando o projeto

Para executar o webapp, siga estas etapas:

- Navegue até a pasta onde o repositório está localizado localmente.
- Abra o Git Bash ou CMD.
  Execute o seguinte comando:
- streamlit run app_RFV.py

## Ajuda

Observe que a máquina na qual o webapp está hospedado pode ser lenta, pois é uma versão gratuita.

## Autor

Kaio Paulo  
[@KaioPauloSilva](https://www.linkedin.com/in/kaio-paulo-silva-331807187/)