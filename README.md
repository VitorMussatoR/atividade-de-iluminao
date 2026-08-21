Alunos responsáveis pelo projeto: Kelvin Pereira Lima e Vitor Mussato

# TIPOS DE LUZES NO UNITY

## 1. Directional Light

A Directional Light simula uma fonte de luz muito distante, como o Sol ou a Lua.

Ela não depende da posição do objeto na cena. O que importa é sua rotação, pois todos os objetos recebem a luz como se ela viesse da mesma direção. A intensidade também não diminui com a distância.

***

## **Exemplos:**

Nesta imagem usamos o Directional Light para simular a luz solar dentro da casa ao meio dia.

<img width="910" height="463" alt="da98ad3d-6a94-471f-a74f-51964474474b" src="https://github.com/user-attachments/assets/805b45f1-ea0c-44ec-a6d0-9ce608f67ae9" />

***

Nesta aqui é diferente, trocamos a cor da luz direcional para um vermelho mais escuro, para simular um fim de tarde dentro da casa, e rotacionamos a luz para entender como se comporta no ambiente em diferentes direções.

<img width="1101" height="500" alt="2eceb045-aaea-4057-a1c7-675dd38a3922" src="https://github.com/user-attachments/assets/d59c836d-59e0-42b0-80e3-df9a80782e5c" />

*** 

<img width="452" height="658" alt="WhatsApp Image 2026-08-21 at 08 09 31" src="https://github.com/user-attachments/assets/00a0555c-847d-492f-8497-2b20087bc54e" />

## 2. Point Light

A Point Light funciona como uma lâmpada ou uma pequena fonte de luz localizada em um ponto específico.

Ela emite luz em todas as direções a partir de sua posição. A intensidade diminui conforme a distância aumenta, seguindo uma aproximação da lei do inverso do quadrado.

***

## **Exemplos:**

Aqui usamos o Point Light para simular a luz do fogo da tocha e da lareira do cenário, aumentando a intensidade da luz para que encaixe no ambiente.

<img width="1427" height="881" alt="cef94f7b-1a29-4b85-9eec-d8890d6a3b6d" src="https://github.com/user-attachments/assets/1c08d150-11c4-4477-8739-5d1c00c92a60" />

***

<img width="450" height="592" alt="WhatsApp Image 2026-08-21 at 08 09 41" src="https://github.com/user-attachments/assets/49445895-55da-421b-b575-1a1c16a3bc66" />

***

E neste aqui usamos o Point Light para simular a luz da lâmpada do quarto deixando a cor mais clara.

<img width="1547" height="887" alt="1f27495a-ba2b-49f6-a91c-1caba65ff6af" src="https://github.com/user-attachments/assets/6d5c5423-e562-4356-9ba3-bd5eef34d30f" />

***

<img width="450" height="594" alt="WhatsApp Image 2026-08-21 at 08 10 13" src="https://github.com/user-attachments/assets/f6eb5a59-5156-4f31-8723-1cc081c79ce1" />


**Características**
* Emite luz em 360°.
* Possui uma posição definida.
* Possui uma propriedade Range, que determina até onde a luz alcança.
* A intensidade diminui com a distância.
* É excelente para fontes de luz pequenas e locais.

## 3. Spot Light

A Spot Light também possui uma posição específica, mas, ao contrário da Point Light, ela não ilumina em todas as direções.

A luz é projetada em formato de cone, seguindo a direção para a qual o objeto está apontado. Ela possui propriedades como Range e Spot Angle para controlar alcance e abertura do cone.

***
## **Exemplos**

Aqui simulamos a luz saindo das lâmpadas do cenário.

<img width="1550" height="885" alt="a5bc4bda-5ac6-43f2-9bf2-c105a03efb6f" src="https://github.com/user-attachments/assets/fe2eae89-1555-4940-bb9c-c7d7df7229c2" />

***

<img width="455" height="671" alt="WhatsApp Image 2026-08-21 at 08 10 05" src="https://github.com/user-attachments/assets/68dda48a-db65-4377-bd3a-8ef1453847ec" />

***

Aqui trocamos a cor da luz para roxo e sua intensidade

<img width="1543" height="869" alt="9c1c6b94-200e-4f38-8a07-089aa596bcf5" src="https://github.com/user-attachments/assets/0cd215b5-80a5-4eb9-a7c1-9d3e3ae7d514" />

***

<img width="449" height="601" alt="WhatsApp Image 2026-08-21 at 08 10 21" src="https://github.com/user-attachments/assets/70d6bfb4-0fe2-4bf0-95c3-e42694fbb495" />

***

## Características
* Emite luz em uma direção.
* Possui formato cônico.
* Possui alcance configurável.
* Permite controlar o ângulo do cone.
* É ótima para destacar áreas específicas.
