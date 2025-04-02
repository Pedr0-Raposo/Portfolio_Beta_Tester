## 🎮 Dragon ball Z: KAKAROT - Uma queda brusca no frame rate me fez atravessar a montanha.

📅 Data do Relatório: 15/04/2023  

🖥️ Plataforma: PC
📍 Local do Bug: Terra 

📝 Descrição: Estava voando com o Gohan no seu traje de grande sayaman, percorrendo o mapa rente ao chão, quando uma queda no frame rate ocorreu enquanto estava indo em direção a montanha próxima da casa dele. Essa queda de frame, no momento em que iria colidir com a montanha me fez atravessar o chão como se ele não existisse.


## 🎯 Resultado Esperado 

Sem a queda de frame, o personegem continuaria o percurso normal, subindo a montanha.

## 🚨 Resultado Obtido 

A queda de frame naquele momento deve ter criado uma falha na renderização do terreno, me fazendo atravessar o chão.  

## ⚠ Impacto do Bug 

🔹 Leve: Apenas um problema de desempenho. 


## 🛠 Possível Solução 

Resolução por Reset de Posição.

Caso o jogo detecte que o personagem entrou em uma área não permitida, um sistema de "fail-safe" pode reposicioná-lo automaticamente em uma área segura próxima.

## 🖼️ Captura de Tela / Vídeo 
![Gohan no Limbo](https://github.com/Pedr0-Raposo/Portfolio_Beta_Tester/blob/main/Bugs%20Relatados/imagens/%5BDBZ%20KAKAROT%5D-Dentro_da_terra.png)
