# Automação de Testes - iFood

Este repositório contém os scripts de automação para testar funcionalidades do website iFood. Os testes são escritos em Python, utilizando o Selenium WebDriver para simular interações do usuário com o website.

## Estrutura do Projeto

project/ 
│ 
├── drivers/ # Contém o ChromeDriver necessário para a execução dos testes    
│ └── chromedriver 
│
│ 
├── docs/ # Documentação dos casos de teste 
│ └── test_cases.docx 
│ 
├── tests/ # Scripts de testes individuais 
│ ├── test_case1.py 
│ ├── test_case2.py 
│ └── ... 
│ 
├── .gitignore # Configuração do Git para ignorar arquivos desnecessários 
├── README.md # Documentação do projeto 
└── requirements.txt # Dependências do projeto


## Pré-Requisitos

Antes de executar os testes, certifique-se de que você tem o Python instalado em sua máquina, juntamente com a biblioteca Selenium. Além disso, é necessário que o ChromeDriver esteja na sua versão mais recente e compatível com a versão do seu navegador Chrome.

## Configuração do Ambiente

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seuusuario/projeto_automacao_ifood.git
   cd projeto_automacao_ifood

2. **Instale as dependências:**
É recomendado usar um ambiente virtual para evitar conflitos de dependências:

python -m venv venv
source venv/bin/activate  # No Windows use `venv\Scripts\activate`
pip install -r requirements.txt

## Execução dos testes
# Para executar um teste específico, navegue até o diretório do projeto e execute:
python tests/nome_do_teste.py

# Para executar todos os testes, você pode usar o seguinte comando:
python -m unittest discover -s tests

## Documentação dos Testes
Você pode encontrar a documentação detalhada dos casos de teste no arquivo docs/test_cases.docx. Este documento contém todas as informações necessárias sobre cada caso de teste implementado.

### Contato
Responsável pelo projeto: Arivaldo Silva Braga Filho
E-mail: arivaldofilho26@hotmail.com
GitHub: https://github.com/ArivaldoFilho
