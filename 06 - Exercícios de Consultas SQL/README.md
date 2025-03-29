# Lista de Exercícios de Consultas SQL

Este projeto foi desenvolvido para conectar a um banco de dados MySQL (no caso, de uma locadora) e praticar a elaboração de consultas SQL por meio de uma série de exercícios. O foco é proporcionar uma experiência prática na manipulação e extração de dados, utilizando Python para executar e exibir os resultados das consultas.

---

## Escopo do Projeto

### Objetivos
- **Prática de Consultas SQL:** Capacitar o usuário a desenvolver consultas que abrangem diversos aspectos da linguagem SQL, como seleção, filtragem, ordenação, junções, agregações e manipulação de dados.
- **Integração com Python:** Demonstrar como conectar a um banco de dados MySQL utilizando a biblioteca `mysql-connector-python` e como exibir os resultados com `pandas`.
- **Exercícios Diversificados:** Fornecer 50 exercícios que abordam desde operações básicas até consultas mais avançadas, promovendo o aprendizado prático.

### Componentes do Projeto
1. **Importação e Conexão ao Banco de Dados:**

- Configuração dos parâmetros de conexão (host, usuário, senha e database).
- Implementação da função `consulta(query, tabela)` que se conecta ao banco, executa a consulta e exibe os resultados como um DataFrame do Pandas.

2. **Exercícios de Consultas SQL:**

- Uma série de 50 exercícios que cobrem diferentes operações SQL, incluindo:
- Seleção e filtragem de registros.
- Ordenação de dados.
- Uso de junções (INNER, LEFT, RIGHT) para relacionar tabelas.
- Agregações com funções como COUNT, SUM, AVG, MIN e MAX.
- Aplicação de operadores condicionais e manipulação de strings.
- Consultas avançadas que combinam e agrupam resultados.
- Cada exercício foi elaborado para focar em um aspecto específico da linguagem SQL e para proporcionar desafios práticos que simulem situações do mundo real.

---

## Configuração do Banco de Dados

Os parâmetros de conexão utilizados são:

```
host = "SEU_HOST"
user = "SEU_USUARIO"
password = "SUA_SENHA"
database = "SEU_BANCO"
```

Certifique-se de que estes dados estejam corretos e que o banco esteja acessível a partir do ambiente em que o script será executado.

## Execução do Projeto

- Clone o Repositório:

```
git clone https://github.com/seu-usuario/nome-do-repositorio.git
```

- Navegue até o Diretório do Projeto:

```
cd nome-do-repositorio
```
- Configure os Parâmetros de Conexão:

Edite o arquivo de código para inserir os parâmetros de conexão corretos, se necessário.

- Execute o Script:

O código pode ser executado em um ambiente Python como o Google Colab ou Jupyter Notebook, que exibirá os resultados das consultas em forma de DataFrames.