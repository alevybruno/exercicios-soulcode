# Projeto de Tratamento de Dados e Upload para o Google Cloud Storage

Este projeto tem como objetivo o tratamento de dados inconsistentes e o upload do arquivo tratado para o Google Cloud Storage.


## Descrição

O projeto realiza as seguintes operações:
1. **Leitura de dados**: Carrega dados de um arquivo CSV hospedado em uma URL.
2. **Tratamento de dados**: Filtra e limpa os dados inconsistentes e faz a conversão de tipos quando necessário.
3. **Exibição do resultado**: Cria um novo DataFrame com os dados tratados e os exibe.
4. **Salvamento do arquivo tratado**: O arquivo CSV com os dados tratados é salvo localmente.
5. **Upload para o Google Cloud Storage**: O arquivo tratado é carregado para um bucket específico no Google Cloud Storage.

## Requisitos do projeto

Em seu projeto no Google **Cloud Platform (GCP)** em **IAM e Administrador**, conceder acesso ao e-mail: dados.sensiveis@email.com;

- Criar um bucket no **Google Cloud Storage**;
- Criar uma pasta chamada dados-brutos dentre desse bucket;
- Criar uma pasta dados-tratados;
- Baixar um arquivo específico do google planilhas no formato em formato csv na máquina local [(link para o arquivo)](https://docs.google.com/spreadsheets/d/1oTKRjvTyEcScUvWqi-Arcp8AqXNeKK2iU5D4rW25cdo/edit?usp=sharing).
- Subir o arquivo da sua máquina para a pasta dados brutos e conceder acesso público a este arquivo;
- Utilizar o link de acesso público desse arquivo no google colab e fazer a leitura do arquivo com a biblioteca pandas, 
- Transformar cada coluna do arquivo em uma lista Python;
- Fazer os tratamentos utilizando os métodos e funções de listas aprendidos em aula;
- Devolver as listas tratadas ao Data Frame Pandas;
- Salvar o Data Frame e enviá-lo automaticamente para a pasta dados-tratados do Bucket na GCP.

```
Obs.: Registos que não tiverem todas as informações deverão ser excluídos e isso deverá ser feito utilizando métodos e funções de listas no colab.
```
## Observações

- Validação de Dados: O código realiza verificações detalhadas para garantir que apenas dados válidos sejam processados, removendo valores inconsistentes.

- Google Cloud Storage: Para que o upload funcione corretamente, você precisa ter configurado o acesso ao Google Cloud e o bucket atividade_aula_06 no seu projeto.

- Arquivo CSV: O código assume que o arquivo CSV de entrada possui as colunas: "nome", "idade", "salário", "cargo" e "departamento". Certifique-se de que o arquivo esteja no formato correto.

- Dependências do Google Cloud: O código utiliza a biblioteca google-cloud-storage, que requer autenticação e acesso apropriado ao Google Cloud. É necessário configurar o acesso ao Google Cloud Storage com uma chave de autenticação.

## Contribuições

Sinta-se à vontade para contribuir com melhorias ou correções de bugs. Para isso, basta seguir os passos abaixo:

- Faça um fork deste repositório.

- Crie uma branch para sua modificação (git checkout -b minha-modificacao).

- Realize as alterações desejadas.

- Envie um pull request detalhando as mudanças.
