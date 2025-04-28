## 🎮 CIEE One Rio 

📅 Data do Relatório: 24/04/2025 

🖥️ Plataforma: mobile

📍 Local do Bug:  "Meus objetivos profissionais"
![Imagens](https://github.com/Pedr0-Raposo/Portfolio_QA/blob/main/Bugs%20Relatados/imagens/CIEELocal.jpg)

📝 Descrição: 
Dentro dessa etapa de "Diversidade", existe uma opção no final onde você precisa dizer se faz parte do perfil de pessoas que usam "nome social"(nome pelo qual pessoas transgêneros ou travestis preferem ser chamadas no dia a dia). O bug ocorre no caso de você dizer "Sim, escrever um nome e depois mudar para "Não". fazendo isso você não consegue finalizar a etapa, a menos que volte no "Sim" deixe o espaço em branco e finalmente aperte "Não".

## 🔄 Passos para Reproduzir 

Passo 1: Selecione "Sim" e escreva um nome.

Passo 2: Selecione "Não".

Passo 3: Tente avançar na etapa apertando em "Salvar".

## 🎯 Resultado Esperado 
Ao Selecionar "Não" deveria ignorar o nome digitado e continuar normalmente.


## 🚨 Resultado Obtido 
O sistema não está resetando os dados do campo "Nome Social" ao mudar a resposta de "Sim" para "Não".


## ⚠ Impacto do Bug 

🔸 Moderado: o bug impede a finalização de uma etapa do formulário, a não ser que a pessoa descubra a solução de contornar (voltando ao "Sim", limpando o campo, depois mudando para "Não").

## 🛠 Possível Solução 
Normalmente, quando o usuário muda para "Não", o código deveria.

Limpar automaticamente o campo "Nome Social" zerarando seu conteúdo

Remover qualquer validação relacionada a esse campo.

E atualizar o estado interno para refletir que o nome social não é mais relevante.

## 🖼️ Captura de Tela / Vídeo 

![Imagens](https://github.com/Pedr0-Raposo/Portfolio_QA/blob/main/Bugs%20Relatados/imagens/CIEE.jpg)




