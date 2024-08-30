# Envio de mensagens por WPP

Este projeto automatiza o envio de mensagens via WhatsApp Web utilizando Python, Selenium e um arquivo Excel contendo os contatos e mensagens.

## Índice

- [Visão Geral](#visão-geral)
- [Funcionalidades](#funcionalidades)
- [Requisitos](#requisitos)
- [Instalação](#instalação)
- [Como Usar](#como-usar)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Visão Geral

Este projeto foi desenvolvido para facilitar o envio de mensagens automáticas pelo WhatsApp. Utiliza Selenium para controlar o navegador e enviar mensagens personalizadas a partir de uma lista de contatos fornecida em um arquivo Excel.

## Funcionalidades

- Carrega automaticamente o WhatsApp Web.
- Lê contatos e mensagens de um arquivo Excel.
- Envia mensagens personalizadas para cada contato.
- Verifica se o WhatsApp Web foi carregado antes de tentar enviar as mensagens.

## Requisitos

- Python 3.x
- Jupyter Notebook
- Selenium
- Navegador Chrome (ou outro suportado pelo Selenium)
- WebDriver para o navegador (ex.: ChromeDriver para Chrome)
- pandas
- openpyxl

## Instalação

1. Clone este repositório:

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
	```
2. Crie um ambiente virtual e instale as dependências:
	```bash
	python -m venv env
	source env/bin/activate  # No Windows use `env\Scripts\activate`
	pip install -r requirements.txt
	```
3. Baixe o WebDriver compatível com o seu navegador e adicione-o ao PATH do sistema.


## Como Usar

1. Abra o Jupyter Notebook:

   ```bash
   jupyter notebook
	```
2. Abra o arquivo .ipynb do projeto.

3. Certifique-se de que o arquivo Excel com os contatos está no formato correto. Ele deve conter colunas para o nome e número de telefone.

4. Execute as células do notebook na ordem para iniciar o processo de envio de mensagens.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests com melhorias, correções de bugs ou novas funcionalidades.

## Licença

Este projeto está licenciado sob a [Licença MIT](https://opensource.org/licenses/MIT) - veja o arquivo LICENSE para mais detalhes.



