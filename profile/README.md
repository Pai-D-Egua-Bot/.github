
# 🚀 Pai D'Égua Bot: Uma Assistente Virtual Inteligente voltada para a Mobilidade na Amazônia

### Acesso rapido 
- [Acesse aqui o repository do projeto](https://github.com/Pai-D-Egua-Bot/py-chat-bot-whatsapp/tree/main)

## 🌟 Visão Geral
O **Pai D'Égua Bot** é uma ferramenta de automação de chat com IA em Python, projetada para interagir com usuario atravez do chat integrado com IA e algoritimos para melhorar interações no WhatsApp e para enfrentar desafios de mobilidade em regiões densas, especialmente durante eventos de grande porte. Utilizando o poder do Selenium e da Inteligência Artificial generativa Gemini, este bot automatiza o envio e recebimento de mensagens, gerencia notificações, e oferece orientações turísticas detalhadas e sugestões de transporte.

## 🔄 Fluxograma

Quer entender melhor como essa magia acontece? Confira o nosso [Fluxograma aqui](https://github.com/Pai-D-Egua-Bot/py-chat-bot-whatsapp/tree/main/diagramas)!

## 🐳 Dockerizando o Projeto

- [Acesse aqui o Docker helper](https://github.com/Pai-D-Egua-Bot/py-chat-bot-whatsapp/tree/main?tab=readme-ov-file#-dockerizando-o-projeto)
Quer rodar o Pai D'Égua Bot de forma rápida e prática? Docker é a solução! Siga os passos abaixo e veja o bot em ação:


## 🚀 Desplegando no Heroku (Opção Desativada)

Infelizmente, a opção de deploy no Heroku está desativada por enquanto. Mas não se preocupe, há muito mais formas de aproveitar o Pai D'Égua Bot!

## 💡 Funcionalidades

Confira tudo o que o Pai D'Égua Bot pode fazer por você:

- **Login Automatizado:** Acesse o WhatsApp Web automaticamente e mantenha-se logado.
- **Navegação por Contatos:** Encontre e inicie conversas com qualquer contato em segundos.
- **Envio de Mensagens:** Envie mensagens automatizadas sem esforço.
- **Leitura de Mensagens:** Recupere as últimas mensagens de qualquer chat.
- **Gerenciamento de Notificações:** Nunca perca uma mensagem importante novamente!
- **Automatização de Vendas:** Facilite sua rotina de vendas com automação inteligente.
- **Acesso via Terminal:** Agora você pode iniciar o bot diretamente pelo terminal, sem precisar de uma interface gráfica.
- **QR Code pelo Terminal:** Obtenha o QR Code do WhatsApp diretamente no terminal.
- **Automatização Completa do Login:** Simplesmente inicie o programa e deixe o bot cuidar do resto!
- **Edição de Produtos:** Adicione ou modifique produtos diretamente pelo bot. Confira o guia de uso para mais detalhes.
- **Orientações de Mobilidade e Informações Turísticas:** O Pai D'Égua Bot fornece sugestões de locais turísticos e orientações de transporte com links diretos para aplicativos como Google Maps, Uber e Moovit.

## 🕵️‍♂️ Bot Transparente

- **Sobre os Dados:** Seus dados de sessão (cookies necessários para manter o login) estão seguros na pasta **./dados/**. Cuide bem deles e evite compartilhá-los!

## 🔧 Pré-requisitos

Antes de começar, certifique-se de ter tudo pronto:

- Python 3.x
- Selenium WebDriver
- Google Chrome e ChromeDriver
- Pandas
- Outros pacotes listados no `requirements.txt`

## 🏗 Metodologia

O chatbot **Pai D'Égua Bot** foi desenvolvido utilizando uma abordagem modular, com a divisão de responsabilidades em camadas, onde cada camada realiza funções específicas. A arquitetura é composta pelas camadas de interação, automação e rotinas:

### Arquitetura e Fluxo

- **Inicialização:** O sistema começa com a inicialização das dependências e o login no WhatsApp Web. A partir daí, o bot verifica continuamente por novas mensagens.
- **Rotinas:** Quando uma nova mensagem é detectada, a camada de rotinas é acionada, processando a mensagem e determinando a resposta adequada, seja por meio de scripts personalizados ou consultas à IA.
- **Resposta Dinâmica:** Respostas são geradas com base nas consultas à Gemini, utilizando algoritmos de fuzzy matching e bases de dados para fornecer informações contextuais e precisas, como orientações de transporte e sugestões turísticas.
