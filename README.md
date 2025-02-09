## Autor: Cleber Santos Pinto Júnior - https://github.com/cleberspjr

## Introdução às Interfaces de Comunicação Serial com RP2040 UART, SPI e I2C
Este projeto foi desenvolvido para a placa BitDogLab, utilizando o microcontrolador RP2040. 
Objetivos: 
• Compreender o funcionamento e a aplicação de comunicação serial em microcontroladores.

• Aplicar os conhecimentos adquiridos sobre UART e I2C na prática.

• Manipular e controlar LEDs comuns e LEDs endereçáveis WS2812.

• Fixar o estudo do uso botões de acionamento, interrupções e Debounce.

• Desenvolver um projeto funcional que combine hardware e software.

## Descrição do Projeto
O projeto utiliza os seguintes componentes:

• Matriz 5x5 de LEDs (endereçáveis) WS2812, conectada à GPIO 7.

• LED RGB, com os pinos conectados às GPIOs (11, 12 e 13).

• Botão A conectado à GPIO 5.

• Botão B conectado à GPIO 6.

• Display SSD1306 conectado via I2C (GPIO 14 e GPIO15).

## Funcionalidades do Projeto

1. Foi adicionado caracteres minúsculos a Biblioteca font.h

2. Entrada de caracteres via PC
   
• Foi utilizado o serial monitor via terminal para a entrada de caracteres

• Cada caractere digitado no Serial Monitor foi exibido no display SSD1306.

• Símbolo correspondente ao número foi exibido, também, na matriz 5x5 WS2812.

3. Interação com o Botão A - alterna o estado do LED RGB VERDE(on / off) tanto no no display
   SSD1306 quanto no monitor serial

4. Interação com o Botão B
Interação com o Botão B - alterna o estado do LED RGB AZUL(on / off) tanto no no display
   SSD1306 quanto no monitor serial

## MODO DE EXECUÇÃO

1. Clonar o Repositório:

```bash
git clone https://github.com/cleberspjr/inter_rp_2040.git
```

2. Configure o ambiente de desenvolvimento seguindo as instruções do Pico SDK

3. Abra o projeto no VS Code

4. Importe o projeto através da extensão Raspberry Pi 

5. Execute a simulação na placa Bitdoglab


## LINK PARA O VÍDEO DA TAREFA: 
EM BREVE
