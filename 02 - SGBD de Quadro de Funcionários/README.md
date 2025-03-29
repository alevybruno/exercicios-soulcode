# Sistema de Gerenciamento de Dados de Funcionários de uma Empresa

## Descrição do Projeto

Este projeto tem como objetivo criar um sistema de gerenciamento de dados de funcionários de uma empresa. O sistema permite cadastrar, exibir, listar, atualizar e remover funcionários de maneira eficiente, garantindo o controle dos dados da equipe.

---
## Escopo

Você foi contratado para desenvolver um sistema básico de gerenciamento de funcionários para uma pequena empresa. O sistema deve ser capaz de receber e armazenar informações sobre os funcionários e realizar operações básicas de manipulação desses dados.

### Requisitos

Utilize a função `input()` para realizar um cadastro coletando dados do usuário, como nome, cidade e estado em que reside, idade, escolaridade, cargo e salário.

### Funcionalidades do Sistema

O sistema deve oferecer as seguintes funcionalidades:

1. **Adicionar um novo funcionário ao sistema**, solicitando informações como nome, cargo, salário, e-mail, etc.
2. **Atualizar as informações de um funcionário existente** com base em um identificador único (como um número de identificação ou nome). Exibir informações de um funcionário específico.
3. **Listar todos os funcionários cadastrados.**
4. **Permitir a remoção de um funcionário do sistema.**

### Observações Finais

Certifique-se de implementar um sistema de identificação único para cada funcionário. Valide as entradas do usuário para garantir que as operações sejam realizadas corretamente e sem erros. Documente adequadamente seu código com comentários explicativos para ajudar na compreensão. Esse projeto permite aos alunos praticar e consolidar conceitos fundamentais em Python, como operadores, estruturas de controle, estruturas de dados e funções, enquanto constroem um aplicativo útil para gerenciar informações de funcionários de uma empresa fictícia.

---

## Funcionalidades

- **Cadastrar Funcionários:** Permite adicionar novos funcionários ao sistema.
- **Exibir Funcionário:** Busca e exibe os dados de um funcionário específico pelo ID.
- **Listar Funcionários:** Exibe todos os funcionários cadastrados no sistema.
- **Atualizar Funcionário:** Permite modificar informações de um funcionário já cadastrado.
- **Remover Funcionário:** Exclui um funcionário do sistema com base no ID fornecido.

## Estrutura do Código

O sistema é composto pelas seguintes classes:

- **Funcionario:** Representa um funcionário, contendo seus atributos e métodos para atualização de informações.
- **SistemaEmpresa:** Gerencia os funcionários cadastrados, armazenando-os em uma lista e fornecendo funções para manipulação dos dados.

Além disso, o sistema inclui um **menu interativo**, permitindo que os usuários realizem operações de forma intuitiva.

## Possíveis Melhorias Futuras

- Implementação de um banco de dados para armazenar os funcionários de forma persistente.
- Interface gráfica para facilitar a interação com os usuários.
- Autenticação de usuários para maior segurança.

## Contribuição

Sinta-se à vontade para contribuir com melhorias no projeto! Basta seguir os passos:

1. Fork este repositório.
2. Crie uma nova branch para suas modificações.
3. Faça um commit das alterações.
4. Envie um pull request para revisão.