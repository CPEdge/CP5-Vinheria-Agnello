# 🌡️💡 ESP32 + DHT11 + LDR + MQTT

# Vinheria Agnello – Edge Computing & Computer Systems (FIAP)

Projeto desenvolvido para o Checkpoint 05, com foco em IoT e Edge Computing.
O objetivo é implementar sensores no ESP32 e integrar os dados ao MyMQTT, simulando o monitoramento de uma adega inteligente — a Vinheria Agnello — com controle e visualização em tempo real.

## 🧠 Contexto do Projeto

A Vinheria Agnello busca garantir a qualidade de seus vinhos monitorando o ambiente da adega.
O sistema desenvolvido capta temperatura, umidade e luminosidade e envia esses dados via MQTT para visualização e controle remoto.
O projeto demonstra a aplicação de Edge Computing, onde o ESP32 atua como nó inteligente de captura e envio de dados para a nuvem.

## Funcionalidades

 Conexão automática à rede Wi-Fi
 Leitura da temperatura e umidade (DHT11)
 Monitoramento da luminosidade ambiente (LDR)
 Publicação de dados via MQTT (tópicos esp32/temp, esp32/umid, esp32/ldr)
 Recebimento de comandos MQTT (esp32/led) para controle do LED
 Envio contínuo de dados a cada 5 segundos
 Exibição das leituras no Monitor Serial


## 🧩 Componentes Utilizados

ESP32 DevKit V1 – microcontrolador com Wi-Fi e Bluetooth integrado
DHT11 – sensor de temperatura e umidade
LDR – sensor de luminosidade
LED – indicador visual (onboard ou externo)
Resistores de 10kΩ e 220Ω – usados para pull-down e limitação de corrente
Protoboard e jumpers – para montagem do circuito

## 🔌 Esquemático de Ligação

DHT11 → pino D4 (sinal)
LDR → pino A34 (entrada analógica)
LED → pino D2 (saída digital)
VCC / GND → 3.3V e GND (alimentação)

<img width="566" height="304" alt="Captura de tela 2025-10-23 074656" src="https://github.com/user-attachments/assets/5745acee-c640-48b8-be8b-0f1dac9de8e1" />

👥 Equipe

Luis Gustavo Vasconcelos Costa – RM: 566023.  
Anna Clara Ruggeri da Silva – RM: 565553.  
Matheus Cerciari Reis – RM: 565817.  
Henrique Vicente Vicenterm – RM: XXXX.  
Arthur Gaspare Gil – RM: XXXX.  

## 🏁 Conclusão

O projeto demonstra como a Internet das Coisas (IoT) pode preservar a arte tradicional da vinicultura.
Com sensores inteligentes, o sistema garante que cada garrafa da Vinheria Agnello amadureça sob as condições perfeitas — um brinde à tecnologia e à tradição.
