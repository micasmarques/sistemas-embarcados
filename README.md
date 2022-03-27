# Sistemas Embarcados - 2021.2

#### Robô Autoequilibrista

### 1 - Descrição do projeto:

##### Este projeto visa à construção de um robô pêndulo invertido, o qual consiste em uma estrutura de dois andares que sobre duas rodas se equilibra. O robô segue o princípio físico do pêndulo invertido, ou seja, os motores irão atuar em cada roda para corrigir a inclinação medida por sensores na parte superior do robô, tentando manter o centro de massa em zero grau em relação ao eixo do robô.

### 2 - Objetivos

##### O presente trabalho aborda a modelagem e controle e compreende a simulação em software e implementação física do robô, um modelo matemático em representação por espaço de estados foi levantado para descrever o comportamento do robô de eixo único em sistema de pêndulo invertido, e um controlador PID foi implementado em topologia de problema do regulador com objetivo de controlar a posição vertical do pêndulo invertido a fim de que este se mantenha estável. O robô foi projetado e construído tendo um motor atuando em cada roda, gerenciados por microcontroladores.
  
### 3 - Resumo das arquiteturas

  O projeto foi composto pelos seguintes itens:
  
  ##### 1.  Hardware utilizado
  ###### 1. Arduino UNO
  ###### 2. Servo Motor de Rotação Contínua
  ###### 3. Acelerômetro e Giroscopio MPU-6050
  ###### 4. Drive Motor Ponte H
  ###### 5. Peças de acrílico para montagem do Robô


  ##### 2.  Software
  ###### 1. Software do Arduino 

#### Diagrama de Blocos
![alt text](https://github.com/micasmarques/sistemas-embarcados-projeto/blob/main/diagrama-circuito/Equilibrist_Robot.png)
  
### 4 - Resumo dos Resultados

  ##### Por conta da dificuldade existente dentro desse projeto, como o calculo do acelerômetro e do giroscópio, além da dificuldade do robô conseguir ficar em pé com duas rodas, foi um pouco dificil a calibragem desses sensores. O robô conseguiu se equilibrar por uns segundos, e depois caia. Mas os resultados são promissores.

  ![alt text](https://github.com/micasmarques/sistemas-embarcados-projeto/blob/main/results/images/imagem1.jfif)
  ![alt text](https://github.com/micasmarques/sistemas-embarcados-projeto/blob/main/results/images/imagem2.jfif)

### 5 - Grupo

* Micael Marques Rodrigues Silva
* Rayanne Kelly Marcelino Barros Elias

### 6 - Instituição

* Instituto Federal da Paraíba - IFPB
* Campus Campina Grande

### Docente responsável
* Alexandre Sales Vasconcelos
