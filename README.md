# Projeto: Controle de LED com Sensor LDR
Projeto: Controle de LED com Sensor LDR e Arduino UNO
📌 Descrição
Este projeto tem como objetivo utilizar um Arduino UNO para controlar automaticamente um LED de acordo com a luminosidade do ambiente.

Para isso, utilizamos um sensor LDR, que identifica a quantidade de luz presente no ambiente. Quando o ambiente fica escuro, o Arduino acende o LED. Quando o ambiente fica claro, o LED é desligado.

🎯 Objetivo
Criar um sistema simples de iluminação automática utilizando:

Arduino UNO
Sensor LDR
LED
Resistores
Protoboard
Fios (jumpers)

## Materiais

## 🧰 Materiais

| Quantidade | Material |
|:----------:|----------|
| 1 | Arduino Uno |
| 1 | Sensor LDR |
| 1 | LED |
| 2 | Resistores |
| 1 | Protoboard |
| 4 | Jumpers |

<img src="https://github.com/AlannaAlves/projeto_LDR_Arduino/blob/67007ca12dd74c803d8a4e5c9d9a07501345971b/1000533605.jpg" alt="Descrição da imagem">
 <img src="https://github.com/AlannaAlves/projeto_LDR_Arduino/blob/b81006717c3025be204e40f10293acda66e2dfbb/1000533604.jpg" alt="Descrição da imagem">

## TRECHO DO CODIGO
```cpp
Trecho do código — Sensores → OUTPUT
// Sensores -> OUTPUT

const int LED = 9;

void setup() {
  pinMode(LED, OUTPUT);
}
