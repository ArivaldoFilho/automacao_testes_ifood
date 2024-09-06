# Projeto de Automação de Testes - iFood

Este projeto contém a automação de testes para 10 casos de teste do iFood utilizando **Selenium WebDriver** com **Python**. A estrutura do projeto segue o padrão Page Object Model (POM) para facilitar a manutenção e a escalabilidade dos testes.

## Requisitos

- Python 3.8+
- Google Chrome (versão compatível com o `chromedriver` utilizado)
- Virtualenv (opcional, mas recomendado)

## Configuração do Ambiente

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/usuario/projeto-automacao-ifood.git
   cd projeto-automacao-ifood


project/
│
├── drivers/           # Contém o ChromeDriver necessário para execução dos testes
├── docs/              # Documentação com especificações dos casos de teste
├── pages/             # Page Objects representando as páginas do iFood
├── tests/             # Scripts de automação para os 10 casos de teste
├── utils/             # Funções auxiliares e utilitárias
├── logs/              # Logs gerados durante a execução dos testes
├── reports/           # Relatórios de execução dos testes
├── .gitignore         # Arquivos que o Git deve ignorar
├── README.md          # Instruções para execução e configuração
└── requirements.txt   # Bibliotecas e dependências do projeto
