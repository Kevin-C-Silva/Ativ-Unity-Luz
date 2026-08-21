# Ativ-Unity-Luz
Projeto do Unity com o propósito de testar diferentes tipos de luz sobre objetos com texturas distintas.

Feito por: 
<br> Guilherme Diogo de Moraes 
<br> Kevin Cavalcante Silva

## Directional Light

O "sol" criado junto do projeto do Unity é um directional light, e dessa forma o utilizamos como exemplo.
<img width="1099" height="504" alt="Captura de tela 2026-08-21 074710" src="https://github.com/user-attachments/assets/12d43f92-9251-4e6c-a880-143ecc7f7713" />

Alteramos a intensidade e temperatura da luz para que ela se pareça mais com o sol do entardecer.

Valores:
Temperatura: 5000 -> 1500
Intensidade: 2 -> 100

<img width="1101" height="504" alt="Captura de tela 2026-08-21 075016" src="https://github.com/user-attachments/assets/4d2fe95a-6ab6-47a7-b085-4ea7d7925106" />

## Spot Light

O spot light foi utilizado nos postes (um de cada lado do ponto de ônibus) em nosso projeto.
*Note que tiramos a luz do sol para facilitar a visualização das luzes*

<img width="1101" height="504" alt="Captura de tela 2026-08-21 080829" src="https://github.com/user-attachments/assets/c0c7f7cd-014a-4894-b5db-ccf90efbaa74" />

Alteramos a cor das luzes para lembrar as chamadas luzes amarelas, embora tenham uma coloração alaranjada, inclusive as luzes tendo uma cor laranja. Além disso, mudamos os valores do "ângulo do ponto interno e externo" da luz, ou seja, a diferença do ponto focal da luz até o ponto onde a luz deixa de ser visível para um valor maior (assim tendo um raio de atuação maior) e também mudamos os valores para que sejam iguais (desse modo, não existe "degradê" do ponto focal até o fim do raio de atuação).

Valores:
Cor - Hexadecimal: FFFFFF (Branco) -> FFA500 (Laranja)
Intensidade: 30 -> 999
Inner / Outer Spot Angle: 1 30 -> 80 80

<img width="1101" height="505" alt="Captura de tela 2026-08-21 080110" src="https://github.com/user-attachments/assets/d2a40ecd-1c31-4b45-9ea3-e55d3dbe41ad" />

## Point Light

O point light, em nosso projeto, foi aplicado na luz presente no ponto de ônibus.

<img width="1100" height="506" alt="Captura de tela 2026-08-21 080651" src="https://github.com/user-attachments/assets/94fd9496-82a8-4672-a6a3-0254658e56ed" />

Mudamos a cor da luz para vermelho, assim como aumentamos a intensidade e alcance da mesma, e por fim, decidimos mudar o tipo de sombra de "sem sombra" para "sombras suaves" e inserimos um valor para raio das sombras.

Valores:
Cor: FFFFFF (Branco) -> EC3636 (Vermelho)
Intensidade:  7 -> 37
Alcance: 10 -> 453
Shadow type: No shadows -> Soft shadows
Shape Radius: -- (nenhum) -> 0.3

## Area light

O area light era pra ter sido aplicado em um *outdoor*, porém o area light não estava funcionando no momento por conta de uma atualização no Unity.
