# QA Web Automation

Projeto de automação de testes web desenvolvido com Java, Playwright e JUnit 5.

## Objetivo

Demonstrar conhecimentos em automação de testes, arquitetura de frameworks de QA e boas práticas de desenvolvimento aplicadas ao contexto de Quality Assurance.

O projeto utiliza o SauceDemo como aplicação de testes para implementação de cenários funcionais automatizados.

## Tecnologias

* Java
* Playwright
* JUnit 5
* Maven
* Git
* GitHub Actions (em desenvolvimento)

## Estrutura do Projeto

```text
src
├── test
│   ├── java
│   │   ├── base
│   │   ├── pages
│   │   ├── tests
│   │   └── utils
```

### Base

Contém configurações compartilhadas e inicialização do Playwright.

### Pages

Implementação do padrão Page Object Model (POM), responsável por encapsular elementos e ações das páginas.

### Tests

Cenários automatizados e validações.

### Utils

Classes auxiliares reutilizáveis pelo framework.

## Cenários Automatizados

* Login com credenciais válidas
* Login com credenciais inválidas
* Validação de mensagens de erro
* Navegação para página de produtos
* Fluxo de compra (em desenvolvimento)

## Como executar

```bash
mvn test
```

## Boas práticas aplicadas

* Page Object Model (POM)
* Separação de responsabilidades
* Código reutilizável
* Testes independentes
* Estrutura escalável para novos cenários

## Autor

David Andrade
