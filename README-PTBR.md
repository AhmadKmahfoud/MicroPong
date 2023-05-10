# Pong em MicroPython

Este projeto consiste na criação de um jogo de Pong utilizando o MicroPython em uma placa de desenvolvimento com suporte a MicroPython e uma tela OLED. O jogo contará com botões para iniciar e reiniciar a partida, e dois potenciômetros que serão utilizados para controlar as paletas.

### 🚀 Esquema Eletrico
![image](https://user-images.githubusercontent.com/82835417/235048457-19122b90-e9ee-4508-bafc-31380a168091.png)

### 🧱 Diagrama de blocos
![image](https://user-images.githubusercontent.com/82835417/235049069-e432b852-4df9-42a7-923d-1500570943a5.png)


### 📋 Pré-requisitos
- Ser compacto
- Placa de desenvolvimento com suporte a MicroPython;
- Display grafico (Tela OLED);
- utilizar entradas analogicas (2 potenciometros)
- Botões para start e reset.

## ⚙️ Executando os testes
Para testar o funcionamento do Raspberry Pi Pico, podemos começar com um teste simples de piscar o LED integrado. Para isso, execute o seguinte código no Raspberry Pi Pico:

**********************************************************************************************************************************************************************
![image](https://user-images.githubusercontent.com/82835417/235049382-6a7e1c97-7ff9-48c1-a9c9-099474b79bff.png)

**********************************************************************************************************************************************************************
Esse código fará com que o LED integrado pisque em um intervalo de 0,5 segundos.

### 🛠️Analisando os testes de ponta a ponta
Os testes de ponta a ponta podem ser executados ao jogar o jogo do Pong completo e verificar se todos os componentes (botões, potenciômetros, tela OLED) estão funcionando corretamente e se o jogo está sendo executado sem erros.


### 🔧 Instalação
Para instalar e executar corretamente o projeto de Pong em Micropython com Raspberry Pi Pico, é importante ter conhecimento sobre o esquema de pinos para conectar cada componente.

Tela OLED: a tela OLED deve ser conectada nas GPIOs 0 e 1 (ou seja, a placa deve estar configurada para I2C).

Botões de Start e Reset: os botões devem ser conectados nas GPIOs 16 e 17, respectivamente.

Potenciômetros: os potenciômetros devem ser conectados nas GPIOs 26 e 27.

Certifique-se de que todas as conexões estejam corretas antes de prosseguir com a instalação das bibliotecas e do código do projeto.

(Cabe ressaltar que o codigo possui comentarios que torna intuitivo a mudança das pinagens)

### 📦implantação
Para implantar o projeto em um sistema ativo, basta copiar todos os arquivos do projeto para o Raspberry Pi Pico.


### 🎮Video funcional


https://github.com/AhmadKmahfoud/MicroPong/assets/82835417/b3d12c3b-8503-437b-9c47-501fbb684a49


## 🛠️ Construído com
- MicroPython - a linguagem de programação usada
- Raspberry Pi Pico - o microcontrolador utilizado
- Bibliotecas do python:
    - uTime
    - Ssd1306

## 📌 Versão

O projeto se encontra na Versão 1.0

## ✒️ Autores
- Caio Rabinovich
- Felippe Onishi
- Ahmad Mahfoud
- Lucas Romanato

## 🎁 Expressões de gratidão
Gostaríamos de agradecer aos nossos professores Sergio e Rodrigo pela orientação e suporte durante o desenvolvimento deste projeto.
