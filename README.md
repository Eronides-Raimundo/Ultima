

Descrição

Este repositório contém uma aplicação web desenvolvida em Laravel. A aplicação inclui funcionalidades de autenticação, validação de usuários, testes unitários com Pest/PHPUnit, implementação de logs e visualização de ações realizadas, além de comunicação com APIs externas. O deploy da aplicação foi realizado utilizando o GitHub como ferramenta de gerenciamento de versões.

Ferramentas Utilizadas

- **Laravel**: Framework PHP para o desenvolvimento da aplicação.
- **GitHub**: Ferramenta de gerenciamento de código-fonte e controle de versão.
- **Pest/PHPUnit**: Frameworks de testes unitários.
- **GitHub Actions**: Para CI/CD e deploy automático.
- **Laravel Logging**: Para registrar e visualizar logs da aplicação.

Funcionalidades

1. Autenticação e Validação

A aplicação implementa um sistema de autenticação básico, onde os usuários podem se registrar, fazer login, e realizar logout. A validação de dados é realizada utilizando o sistema de validação integrado do Laravel, garantindo que os dados fornecidos sejam corretos antes de serem processados.

- **Registro de Usuário**: Usuários podem se registrar informando nome, e-mail e senha.
- **Login**: Usuários podem se autenticar utilizando e-mail e senha.
- **Logout**: Usuários podem se deslogar a qualquer momento.

2. Testes Unitários

Foram implementados testes unitários utilizando o framework Pest (para testes mais concisos e expressivos) e PHPUnit (para compatibilidade com o ecossistema Laravel). 

Os testes incluem:

- Verificação de funcionalidades de autenticação.
- Testes de validação de dados.
- Testes de endpoints da API.

Para rodar os testes, use o seguinte comando:

```bash
php artisan test

Essa documentação completa, incluindo as instruções para rodar o projeto localmente e a descrição de funcionalidades, como autenticação, validação, testes, logs, comunicação de APIs, e deploy com GitHub Actions.

