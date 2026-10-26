# 🤖 Desafio Criativo: Prompt de um Agente de Atendimento

Prompt que define o comportamento de um Agente de IA para a **Central de Orientação ao Cliente Interno de um banco**: o service desk que atende os próprios funcionários quando um sistema, acesso ou equipamento trava o trabalho.

Desafio de projeto da [DIO](https://www.dio.me/), construído em três etapas: papel e escopo do Agente → tom, regras e encaminhamento → testes em casos difíceis e refinamento.

## 📄 O que tem aqui

- **[desafio-agente-atendimento.md](./desafio-agente-atendimento.md)**: prompt final completo + roteiro de testes

## 🧠 Decisões principais do prompt

- **Escopo fechado:** o Agente resolve só os pedidos mais comuns (senha, erros de sistema, abertura e acompanhamento de chamados)
- **Proibido inventar:** número de chamado, status, prazo ou grupo responsável. Se não sabe, ele diz e indica onde encontrar
- **Proteção de dados:** nunca pede senha ou token e não repete dados de clientes enviados no chat
- **Encaminhamento humano definido:** incidentes de segurança, sistema fora do ar, pedidos que dependem de gestor e problemas que não se resolveram após duas tentativas
- **Passagem sem retrabalho:** ao encaminhar, o Agente resume o que já foi relatado, para o atendente humano não perguntar tudo de novo

## 🧪 Como testar

1. Copie o prompt do arquivo e cole em uma IA de sua preferência (ChatGPT, Claude, Gemini...)
2. Converse como se fosse um funcionário, usando as mensagens da tabela de testes
3. Compare a resposta com o comportamento esperado. Se algo escapar, ajuste a regra correspondente e teste de novo

> 💡 Resposta fora do esperado quase sempre é instrução faltando, não limitação do modelo.

---


