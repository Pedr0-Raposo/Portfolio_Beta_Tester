# 🎮 Avowed - Andando embaixo da água e explorando áreas fora da barreira limite

- **📅 Data do Relatório:** 20/02/2025
- **🖥️ Plataforma:** PC  
- **📍 Local do Bug:** No Cânion de Watcher's Mirror
- **📝 Descrição:** No jogo, há um sistema que causa dano ao atravessar a barreira limite. No entanto, nesse local específico, ao pular em direção à água, o sistema de dano é ativado, atordoando o personagem ainda no ar. Como essa água não possui física aplicada, o personagem simplesmente a atravessa. Além disso, ao usar as habilidades dos acompanhantes, é possível ser levantado de volta enquanto ainda está abaixo da água, permitindo acesso a áreas que antes eram inacessíveis.

## 🔄 Passos para Reproduzir
1. Passo 1: tenha uma acompanhante no seu grupo para desbloquear a habilidade de ressurreição.   
2. Passo 2: Se jogue do Cânion e espere seu personagem atravesar a água e tocar o chão. 
3. Passo 3: use a habilidade de ressurreição. 

## 🎯 Resultado Esperado
Seu personagem deveria morrer e reaparecer automaticamente no último ponto de crontole, sem te dar chance de usar a habilidade dos acompanhantes. 

## 🚨 Resultado Obtido
Por conta do seu companheiro estar proximo de você no momento em que foi atordoado, ele te permite levantar novamente graças a habilidade dele.

## ⚠ Impacto do Bug
🔴 Grave: Pode atrapalhar a jogabilidade, te fazendo perder algum tempo de jogo caso você não tenha feito um save antes desse bug, pois sem cuidado, pode cair no “limbo” infinitamente e o único jeito de voltar seria carregando o seu último ponto de salvamento. 
 
## 🛠 Possível Solução
Aumentar a área em que o personagem toma dano para baixo do nível da água possivelmente resolveria esse problema, já que assim que o jogador ressuscitasse, ele morreria instantaneamente e voltaria ao ponto de controle mais próximo   
   
## 🖼️ Captura de Tela / Vídeo  
 
![Bug do Avowed](https://github.com/Pedr0-Raposo/Portfolio_Beta_Tester/blob/main/Bugs%20Relatados/imagens/%5BAvowed%5D-Fora_do_%20mapa.png)
![Bug do Avowed](https://github.com/Pedr0-Raposo/Portfolio_Beta_Tester/blob/main/Bugs%20Relatados/imagens/%5BAvowed%5D-Limbo.png)

