# Automação de Extração de Dados Doc9 challenge
Este projeto consiste em uma automação para extração de dados de uma tabela de um site utilizando a biblioteca Selenium em Python.

## Sobre este Projeto
Tem como objetivo: Automatizar o processo de extração de dados de uma tabela em um site, realizar o download de documentos e extrair informações desses documentos para posterior análise.

## Funcionalidades
- Extrair dados de uma tabela em um site
- Navegar por todas as páginas da tabela
- Baixar documentos associados a cada entrada da tabela
- Extrair informações desses documentos para análise
  
# Como Usar
- Pré-requisitos: <br/> 
Para executar este projeto, é necessário ter Python instalado em seu ambiente. Além disso, certifique-se de instalar as dependências listadas no arquivo requirements.txt executando:

```Python
$ pip install -r requirements.txt
```

obs: Também é necessário ter o WebDriver do Chrome instalado e configurado. Certifique-se de que o arquivo executável do WebDriver está no PATH do sistema ou defina o caminho no código onde inicializamos o WebDriver.

## Execução
- Altere o valor da variável "diretorio" para o caminho em que se encontra o arquivo "Doc9_challenge_001.ipynb" 
- Execute o arquivo Python Doc9_challenge_001.ipynb. O script irá navegar por todas as páginas da tabela, baixar documentos associados a cada entrada e extrair informações desses documentos.

# Tecnologias Utilizadas
- Python
- Selenium
- Pandas
- pytesseract (OCR - Reconhecimento Óptico de Caracteres)
- Pillow (PIL)
-Outras bibliotecas auxiliares para manipulação de dados

## Observações
Este projeto foi desenvolvido para fins de demonstração e aprendizado.
Certifique-se de ter permissões adequadas para acessar e extrair dados do site em questão.
O código pode precisar de ajustes dependendo das atualizações no layout ou comportamento do site.
Certifique-se de estar em conformidade com os termos de serviço do site antes de automatizar a extração de dados.

# Não se esqueça de alterar o valor da variável "diretório" 

# Em funcionamento:
![Doc9_challenge](https://github.com/felipeJJ/Doc9_challenge/assets/43899843/c5e7b876-e152-4116-9dcf-7ff4c58a15cf)

