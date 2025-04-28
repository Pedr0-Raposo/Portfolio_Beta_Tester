## Relatório de Bug — CIEE One Rio

📅 Data do Relatório: 24/04/2025 

🖥️ Plataforma: mobile

📍 Local do Bug:  "Diversidade"
![Imagens](https://github.com/Pedr0-Raposo/Portfolio_QA/blob/main/Bugs%20Relatados/imagens/CIEELocal.jpg)

📝 Descrição: 
Quando o usuário seleciona "Sim" para a pergunta sobre utilização de "Nome Social" e insere um nome, em seguida muda a resposta para "Não" sem limpar manualmente o campo, o sistema impede o avanço para a próxima etapa.
O formulário mantém o nome anteriormente digitado, causando erro de validação, mesmo com a opção "Não" selecionada — o que deveria ignorar qualquer entrada.

## 🔄 Passos para Reproduzir 

Passo 1: Acesse a seção "Diversidade"

Passo 2: Selecione "Sim" e insira qualquer texto no campo "Nome Social."

Passo 3: Alterne a seleção para "Não" sem limpar o texto inserido.

Passo 4: Tente avançar clicando em "Salvar."

## 🎯 Resultado Esperado 
Ao selecionar "Não," o campo "Nome Social" deveria ser automaticamente limpo ou ignorado, permitindo o avanço sem problemas de validação.


## 🚨 Resultado Obtido 
O campo "Nome Social" mantém o texto digitado mesmo após mudar a seleção para "Não."

O sistema ainda exige que o campo esteja vazio ou válido, bloqueando o avanço.

## ⚠ Impacto do Bug 

🔸 Moderado: o bug impede a finalização de uma etapa do formulário, a não ser que a pessoa descubra a solução de contornar (voltando ao "Sim", limpando o campo, depois mudando para "Não").

## 🛠 Possível Solução 
Normalmente, quando o usuário muda para "Não", o código deveria:

Limpar automaticamente o campo "Nome Social" zerarando seu conteúdo

Remover qualquer validação relacionada a esse campo.

E atualizar o estado interno para refletir que o nome social não é mais relevante.

## 🖼️ Captura de Tela / Vídeo 

![Imagens](https://github.com/Pedr0-Raposo/Portfolio_QA/blob/main/Bugs%20Relatados/imagens/CIEE.jpg)




