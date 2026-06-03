# 🚀 Automação de Testes - C# + SpecFlow

Framework de automação de testes desenvolvido em C#, utilizando SpecFlow para implementação de testes BDD, cobrindo cenários de API e Front-End.

## Tecnologias

- .NET
- C#
- SpecFlow
- NUnit
- Selenium WebDriver
- RestSharp
- FluentAssertions

## Estrutura do Projeto

```text
├── Drivers
├── Features
│   ├── Api
│   └── FrontEnd
├── Helpers
├── Models
├── Pages
└── StepDefinitions
```

## Principais Camadas

- **Drivers:** gerenciamento dos navegadores.
- **Features:** cenários BDD escritos em Gherkin.
- **StepDefinitions:** implementação dos passos dos cenários.
- **Pages:** implementação do padrão Page Object Model (POM).
- **Models:** objetos de requisição e resposta.
- **Helpers:** métodos utilitários reutilizáveis.

## Clonando o Repositório

```bash
git clone https://github.com/tidenis/specflowseleniumrestsharp.git
```

## Boas Práticas Adotadas

- BDD com SpecFlow
- Page Object Model (POM)
- Separação de responsabilidades
- Reutilização de componentes
- Testes independentes
- Fácil manutenção e escalabilidade
