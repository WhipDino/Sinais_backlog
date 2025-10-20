# App Sinais - 3ESR

### João Victor --> RM550453
### Pedro Henrique Farath --> RM98608
### Lucca Vilaça --> RM551538
### Luana Cabezaollias --> RM99320
### Juliana Maita --> RM99224

## Link Azure DevOps -> https://dev.azure.com/RM550453/SINAIS_SPRINT4/_boards/board/t/SINAIS_SPRINT4%20Team/Issues
## Link vídeo -> https://youtu.be/GkQqUdnKQhw

## 📹 Demonstração em Vídeo
Clique na imagem abaixo para assistir à demonstração completa do projeto:

[![Assista à demonstração no YouTube](https://img.youtube.com/vi/GkQqUdnKQhw/hqdefault.jpg)](https://youtu.be/GkQqUdnKQhw)

## Sobre o projeto

## 🎯 Descrição Geral  
Projeto desenvolvido para a disciplina de **Qualidade e Testes de Software**, com foco em **automação de testes de API** utilizando o **Postman**.  

O sistema **SINAIS** simula uma plataforma voltada para **controle e prevenção de vício em apostas online**, permitindo validar funcionalidades que promovem o uso responsável de jogos.  

---

## 🗂️ Planejamento e Gerenciamento – *Azure DevOps (Boards)*  
Toda a parte de **planejamento e gerenciamento das tarefas** foi realizada no **Azure Boards**, onde foram criados os **casos de teste**, **tarefas** e **histórias de usuário** representando o ciclo completo de desenvolvimento e testes do sistema.  

Cada caso de teste implementado no **Postman** possui um item correspondente no **Azure Boards**, facilitando o acompanhamento do progresso e a cobertura de testes durante o projeto.  

---

## ⚙️ Testes Automatizados – *Postman*  
Foram criados e testados **quatro endpoints principais**, representando as principais funcionalidades do sistema:

- **Limite diário** – define o valor máximo de apostas por dia.  
- **Autoexclusão (30 dias)** – bloqueia o acesso temporariamente.  
- **Alerta de tempo** – envia notificações após uso prolongado.  
- **Histórico de uso** – retorna o tempo total e histórico de utilização.  

Os testes foram implementados com **scripts automatizados em JavaScript** na aba **Tests** do Postman e executados através de um **Mock Server**, validando:  
- o **status da resposta (200)**,  
- o **corpo da resposta (não vazio e válido)**,  
- e o **conteúdo retornado** conforme o comportamento esperado de cada funcionalidade.

---

## 🧠 Tecnologias Utilizadas
- **Postman** – criação e execução dos testes automatizados  
- **JavaScript** – linguagem usada nos scripts de validação  
- **Azure DevOps Boards** – planejamento e acompanhamento das tarefas e casos de teste  
