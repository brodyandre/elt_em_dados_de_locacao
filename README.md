# Realizando ELT em dados de Locação

# Análise de Dados de Locação de Imóveis 📊🏠

Este repositório contém o código utilizado para realizar a análise e transformação de dados de locação de imóveis. O objetivo principal é explorar os dados de aluguel, identificar tendências ao longo do tempo e realizar uma visualização interativa da variação dos valores de aluguel.

## Descrição do Projeto

O projeto visa a análise dos pagamentos de aluguel ao longo do tempo, com a limpeza e transformação dos dados para posterior visualização e obtenção de insights. O conjunto de dados está em formato JSON e contém informações detalhadas sobre os pagamentos, valores de aluguel, datas de pagamento, entre outros.

As principais etapas realizadas no código são:
1. **Leitura e Carregamento dos Dados**: Leitura do arquivo JSON e conversão para um DataFrame do Pandas.
2. **Limpeza e Transformação dos Dados**: Conversão de colunas de datas e valores monetários para formatos mais apropriados.
3. **Exploração dos Dados**: Normalização e expansão de dados aninhados para facilitar a análise.
4. **Visualização**: Criação de gráficos que mostram a variação do valor do aluguel ao longo do tempo.

## Índice

1. [Tecnologias e Dependências](#tecnologias-e-dependências)
2. [Como Executar](#como-executar)
3. [Base de Dados](#base-de-dados)
4. [Estrutura de Arquivos](#estrutura-de-arquivos)
5. [Exemplo de Saída](#exemplo-de-saída)
6. [Licença](#licença)

## Tecnologias e Dependências ⚙️

Este projeto utiliza as seguintes tecnologias e bibliotecas:

- **Python 3.x**
- **Pandas**: Para manipulação e análise de dados.
- **NumPy**: Para operações numéricas.
- **Matplotlib**: Para visualização de dados gráficos.
- **Seaborn**: Para gráficos mais estilizados.

### Como Instalar as Dependências

Para rodar este projeto localmente, é necessário instalar as dependências. Para isso, você pode usar o `pip`. Se você estiver usando um ambiente virtual (recomendado), instale as dependências da seguinte forma:

```bash
pip install pandas numpy matplotlib seaborn
```

### 1. Como Executar 🚀

Clone este repositório para sua máquina local:

```bash
git clone https://github.com/brodyandre/analise_de_locacao_de_imoveis.git
```
### 2. Navegue até o diretório do projeto:

```bash
cd analise_de_locacao_de_imoveis
```
### 3. Abra o notebook e execute as células para carregar e analisar os dados.

```bash
jupyter notebook
```
### 4. Se você não tiver o Jupyter Notebook instalado, você pode instalá-lo via:

```bach
pip install notebook
```
### 5. Após rodar as células, o gráfico da variação do valor do aluguel ao longo do tempo será gerado.

## Base de Dados 📂

O conjunto de dados utilizado neste projeto pode ser baixado através do seguinte link:

- [**dados_locacao_imoveis.json**](https://cdn3.gnarususercontent.com.br/2928-transformacao-manipulacao-dados/dados_locacao_imoveis.json)


Estrutura de Arquivos 📁

Aqui está a estrutura do repositório:

```bash
analise_de_locacao_de_imoveis/
│
├── README.md                 # Este arquivo de documentação
├── dados_locacao_imoveis.json # Arquivo JSON com os dados de locação
├── analise_locacao_imoveis.ipynb # Notebook contendo o código de análise
└── requirements.txt          # Arquivo com as dependências do projeto
```

### Licença 📄
Este projeto está licenciado sob a Licença MIT - consulte o arquivo LICENSE para mais detalhes.

Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para abrir uma issue ou enviar um pull request.

Criado com 💻 por Luiz André de Souza
