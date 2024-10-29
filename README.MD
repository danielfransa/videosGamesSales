# Projeto de Mineração de Dados - Análise de Vendas de Jogos de Videogame

Este projeto é parte da disciplina de Mineração de Dados do Curso de Desenvolvimento de Software Multiplataformas da FATEC Araras, ministrada pela Professora Ivone Piedade Terra. O objetivo é explorar e analisar dados de vendas de jogos de videogame, abrangendo um período que vai dos anos 1980 até os anos 2010.

Nesta primeira etapa do projeto, realizamos a limpeza dos dados a partir de um arquivo .csv que contém informações detalhadas sobre vendas globais de jogos, além de dados sobre as avaliações de críticos e usuários, plataformas, desenvolvedoras e publishers.

## Objetivos

Limpar e preparar o conjunto de dados para análises futuras.
Examinar a quantidade de vendas.
Identificar as principais plataformas, publishers e desenvolvedoras que impactaram o mercado ao longo das décadas.

## Pré-requisitos

- Python 3.8 ou superior (utilizando versão do Python - 3.10.12)
- VS Code com a extensão Jupyter instalada


## Configuração do Ambiente

Para garantir que todos possam reproduzir o projeto facilmente, abaixo estão as instruções para criar um ambiente virtual, instalar as dependências e configurar o ambiente de desenvolvimento com Jupyter.

### Criar um Ambiente Virtual

  **1 - Abra o terminal na pasta raiz do projeto.**

  **2 - Execute o seguinte comando para criar um ambiente virtual:**

```bash
python3 -m venv venv
```

Ative o ambiente virtual:

**No Windows:**

```bash
.\venv\Scripts\activate
```
**No macOS/Linux:**

```bash
source venv/bin/activate
```

### Instale os Requirements

```bash
pip install -r requirements.txt
```

### Configurar o Jupyter no VS Code

Abra o projeto no VS Code.

No ambiente virtual ativado, selecione o kernel do Jupyter no VS Code:
Clique na opção de kernel no canto superior direito do notebook e escolha o ambiente virtual venv.
Agora você está pronto para executar o Jupyter Notebook e trabalhar na limpeza dos dados!