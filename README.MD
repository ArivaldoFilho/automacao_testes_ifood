** link para os vídeos das execuções dos casos de testes **
https://1drv.ms/f/s!AgvOPBfXx0dNga8_-jYsfYj9zDpByA?e=a0RZ7d

# Automação de Testes - iFood

Este repositório contém os scripts de automação para testar funcionalidades do website iFood. Os testes são escritos em Python, utilizando o Selenium WebDriver para simular interações do usuário com o website.

## Estrutura do Projeto

```
project/
│
├── drivers/            # Contém o ChromeDriver necessário para a execução dos testes
│   └── chromedriver
│
├── docs/               # Documentação dos casos de teste
│   └── test_cases.docx
│
├── tests/              # Scripts de testes individuais
│   ├── ct_001.py
│   ├── ct_002.py
│   └── ...
│
├── .gitignore          # Configuração do Git para ignorar arquivos desnecessários
├── README.md           # Documentação do projeto
└── requirements.txt    # Dependências do projeto
```

## Pré-Requisitos

Antes de executar os testes, certifique-se de que você tem o **Python** instalado em sua máquina, juntamente com a biblioteca **Selenium**. Além disso, é necessário que o **ChromeDriver** esteja na sua versão mais recente e compatível com a versão do seu navegador Chrome.

## Configuração do Ambiente

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seuusuario/projeto_automacao_ifood.git
   cd projeto_automacao_ifood
   ```

2. **Instale as dependências:**

   É recomendado usar um ambiente virtual para evitar conflitos de dependências:

   ```bash
   python -m venv venv
   source venv/bin/activate  # No Windows use `venv\Scripts\activate`
   pip install -r requirements.txt
   ```

## Execução dos Testes

- **Para executar um teste específico:**

   Navegue até o diretório do projeto e execute:

   ```bash
   python tests/nome_do_teste.py
   ```

- **Para executar todos os testes:**

   Você pode usar o seguinte comando:

   ```bash
   python -m unittest discover -s tests
   ```

## Documentação dos Testes

A documentação detalhada dos casos de teste pode ser encontrada no arquivo `docs/test_cases.docx`. Este documento contém todas as informações necessárias sobre cada caso de teste implementado.

## Contato

Responsável pelo projeto: **Arivaldo Silva Braga Filho**  
E-mail: [arivaldofilho26@hotmail.com](mailto:arivaldofilho26@hotmail.com)  
GitHub: [ArivaldoFilho](https://github.com/ArivaldoFilho)

