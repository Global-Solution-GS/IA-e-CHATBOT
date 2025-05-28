# Global Solution 2025/1 - Chatbot para Eventos Climáticos Extremos

## Descrição do Projeto

Este projeto faz parte da Global Solution 2025/1 da FIAP para o curso de Análise e Desenvolvimento de Sistemas. O objetivo é desenvolver um chatbot utilizando o IBM Watson Assistant, focado em auxiliar usuários a lidar com problemas relacionados a eventos climáticos extremos. [cite: 58] Estes eventos podem incluir chuvas intensas, ondas de calor, frio extremo, ventos fortes ou tremores de terra. [cite: 58]

O chatbot visa, por exemplo, ajudar pessoas a se prepararem para desastres, entenderem alertas meteorológicos, encontrarem abrigos, cuidarem da saúde em condições climáticas severas ou se conscientizarem sobre os efeitos das mudanças climáticas e como agir. [cite: 59]

## Funcionalidades Implementadas (Requisitos Técnicos)

* **Intenções:** Foram configuradas 5 intenções principais, cada uma com pelo menos 12 exemplos de frases do usuário para garantir a assertividade do reconhecimento. [cite: 61]
* **Entidades:** Foram definidas 5 entidades, incluindo sinônimos, para permitir variações na linguagem do usuário e extrair informações relevantes das conversas. [cite: 62]
* **Variáveis de Contexto:** O chatbot utiliza variáveis de contexto para lembrar informações fornecidas anteriormente pelo usuário, permitindo um fluxo de conversa mais coeso e personalizado. [cite: 63]
* **Integração com Webchat:** O chatbot está integrado e funcional via Webchat (somente texto). [cite: 64]
* **Integração com Telegram:** O chatbot está integrado ao Telegram, com suporte para interações via texto e áudio, utilizando serviços de Speech-to-Text (STT) e Text-to-Speech (TTS). [cite: 64, 65]

## Tecnologias Utilizadas

* **IBM Watson Assistant:** Plataforma principal para desenvolvimento e treinamento do chatbot. [cite: 57]
* **Node-RED:** Utilizado para orquestrar o fluxo de integração, especialmente para o Telegram e serviços de STT/TTS (conforme implícito pela entrega do arquivo .json do fluxo). [cite: 68]
* **Serviço de Speech-to-Text (STT):** Para converter a fala do usuário (áudio no Telegram) em texto. [cite: 64]
* **Serviço de Text-to-Speech (TTS):** Para converter as respostas em texto do chatbot em áudio no Telegram. [cite: 64]
* **API do Telegram:** Para integração do chatbot com a plataforma de mensagens Telegram. [cite: 64]

## Demonstração em Vídeo

Uma demonstração completa do funcionamento do chatbot, tanto no Webchat quanto no Telegram (incluindo as funcionalidades de áudio), está disponível no YouTube. O vídeo explica a interação e o que a solução realiza. [cite: 66]
* **Link do Vídeo:** `[INSERIR O LINK PRIVADO DO YOUTUBE AQUI]` (Este link também consta no arquivo .txt de credenciais). [cite: 68]

## Arquivos do Projeto (Entregáveis)

Conforme os requisitos da disciplina, os seguintes arquivos compõem esta entrega:
* `dialog_skill.json`: Arquivo JSON contendo a Skill de Diálogo exportada do Watson Assistant. [cite: 68]
* `nodered_flow.json`: Arquivo JSON contendo o fluxo de integração desenvolvido no Node-RED. [cite: 68]
* `informacoes_grupo.txt`: Arquivo de texto contendo:
    * Nome dos membros do grupo. [cite: 68]
    * Credenciais dos serviços utilizados (Watson Assistant, STT, TTS, Telegram API Token). [cite: 68]
    * Link do vídeo privado no YouTube. [cite: 68]

## Membros do Grupo

* [Nome Completo do Aluno 1] - [RM do Aluno 1] - [Turma do Aluno 1]
* [Nome Completo do Aluno 2] - [RM do Aluno 2] - [Turma do Aluno 2]
* [Nome Completo do Aluno 3] - [RM do Aluno 3] - [Turma do Aluno 3]

*(Lembre-se de preencher as informações específicas do seu grupo e o link do vídeo)*
