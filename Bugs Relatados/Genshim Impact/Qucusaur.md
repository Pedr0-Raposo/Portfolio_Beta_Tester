# 🎮 Bug no Genshin Impact - Qucusaur caminhando no ar

- **📅 Data do Relatório:** 22/01/2025
- **🖥️ Plataforma:** PC
- **📍 Local do Bug:
![Local que foi feito](https://github.com/Pedr0-Raposo/Portfolio_Beta_Tester/blob/main/Bugs%20Relatados/imagens/%5BGI%5D-Qucusaur.png)

  Ele não precisa necessariamente de um local especifico, é apenas uma região alta que da uma experiência mais divertida.

- **📝 Descrição:** Na média de 1 minuto sem se mover o personagem inicia uma animação, mas se você pular no mesmo frame em que a animação se inicia, o Sauriano começa a faze-lá no ar, logo após a animação terminar, você continua flutuando e sobe possivelmente 1 centímetro por segundo. Esse bug limita a sua movimentação, te permitindo andar apenas para frente, outro ponto a ressaltar é que se você estiver em um lugar alto, vai poder caminhar no ar.  

## 🔄 Passos para Reproduzir
1. Se transforme no Qucusaur. 
2. Espere até que a animação se inicie e tenha sorte para pular no momento exato.  
3. Estar em um lugar alto é opcional
   
## 🎯 Resultado Esperado
Ao pular, deve cancelar/impedir a animação de continuar.  

## 🚨 Resultado Obtido
O Qucusaur faz a animação normalmente no ar subindo alguns centimetro por segundo

## ⚠ Impacto do Bug
🔹 Leve: Apenas um pequeno incômodo. Apesar de restringir seu movimento apenas auma linha reta, pular irá desbugar seu boneco.
   E por ser um bug extremamente difícil de se replicar, pois precisa de um timing perfeito e sorte, não deve impactar diretamente o jogo.

## 🛠 Possível Solução
Ajustar o tempo de ativação da animação

Se a animação começa após 1 minuto parado, pode ser interessante impedir que o jogador pule no momento em que ela se inicia. Um pequeno atraso ou bloqueio temporário da entrada de comandos nesse momento pode reduzir a chance do bug acontecer.


