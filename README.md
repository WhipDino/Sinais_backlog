# App Sinais - 3ESR

### João Victor --> RM550453
### Pedro Henrique Farath --> RM98608
### Lucca Vilaça --> RM551538
### Luana Cabezaollias --> RM99320
### Juliana Maita --> RM99224

## Link Azure DevOps -> https://dev.azure.com/RM550453/SINAIS_SPRINT4/_boards/board/t/SINAIS_SPRINT4%20Team/Issues
## Link vídeo -> https://youtu.be/GkQqUdnKQhw

## Sobre o projeto

### Toda a parte de planejamento e gerenciamento das tarefas foi feita no Azure Boards, onde foram criados os casos de teste, tarefas e histórias de usuário para representar o ciclo de desenvolvimento e testes do sistema.
Cada caso de teste no Postman tem um item correspondente no Azure Boards, facilitando o acompanhamento do progresso e da cobertura de testes.

### Projeto desenvolvido para a disciplina de Qualidade e Testes de Software, com foco em automação de testes de API usando o Postman.

O sistema simula uma plataforma chamada SINAIS, voltada para controle e prevenção de vício em apostas online.
Foram criados e testados quatro endpoints principais:
	•	Limite diário – define o valor máximo de apostas por dia.
	•	Autoexclusão (30 dias) – bloqueia o acesso temporariamente.
	•	Alerta de tempo – envia notificações após uso prolongado.
	•	Histórico de uso – retorna o tempo total e histórico de utilização.

Os testes foram implementados com scripts automatizados em JavaScript na aba Tests do Postman e executados através de um Mock Server, validando status, corpo da resposta e conteúdo retornado.
