# Projeto de Extração de Dados do Banco MySQL para Google Cloud Storage

## Visão Geral
Este projeto tem como objetivo conectar-se a um banco de dados MySQL, extrair dados de diferentes tabelas, processá-los e armazená-los no Google Cloud Storage em formato CSV.

## Escopo do Projeto

- Criar uma instância com MySQL no Google Cloud SQL
- Criar um banco de dados com o nome loja nesta instância
- Popular esse banco de dados com os dados do arquivo deste link: [Google Colab](https://colab.research.google.com/drive/18--jmuhLkQbKsJ5jJdI8W6y0ManYtr0r?usp=sharing).

- Criar um colab para fazer a conexão com este banco loja:
- Trazer todas as informações de todas as tabela desse banco para o ambiente Python/Pandas
- Enviar todas as tabelas desse banco para um bucket no google cloud storage chamado loja, dentro de uma pasta chamada tabelas;
- Conceder acesso ao projeto no IAM para dados.sensiveis@email.com

## Tecnologias Utilizadas
- **Python**
- **MySQL Connector** para conectar ao banco de dados
- **Pandas** para manipulação de dados
- **Google Cloud Storage** para armazenar os arquivos CSV
- **Google Colab** como ambiente de execução (opcional)

## Estrutura do Projeto
O projeto segue os seguintes passos:
1. **Instalação de dependências**
2. **Conexão com o banco de dados MySQL**
3. **Consulta e extração de dados** de diversas tabelas
4. **Conversão dos dados para DataFrames do Pandas**
5. **Autenticação no Google Cloud Storage**
6. **Exportação dos arquivos CSV para o bucket do GCP**

## Como Executar
### 1. Instale as Dependências
Antes de executar o código, instale as bibliotecas necessárias:
```bash
!pip install mysql-connector-python google-cloud-storage pandas
```

### 2. Configure a Conexão com o Banco de Dados
No script, altere os valores para o seu banco de dados:
```python
host = "SEU_HOST"
user = "SEU_USUARIO"
password = "SUA_SENHA"
database = "SEU_BANCO"
```

### 3. Execute o Script
No Google Colab ou ambiente local, execute o script para extrair os dados e enviá-los ao Google Cloud Storage.

## Observações
- O bucket do Google Cloud precisa estar previamente configurado.
- Certifique-se de ter permissão para acessar o banco de dados e o bucket no GCP.
- O código utiliza autenticação do Google Cloud via `auth.authenticate_user()`, necessário para rodar no Google Colab.

