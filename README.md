ESP32 + DHT11 + LDR + MQTT

##Vinheria Agnello – Edge Computing & Computer Systems (FIAP)

Projeto desenvolvido para o Checkpoint 05, com foco em IoT e Edge Computing.
O objetivo é implementar sensores no ESP32 e integrar os dados ao MyMQTT, simulando o monitoramento de uma adega inteligente — a Vinheria Agnello — com controle e visualização em tempo real.

#Contexto do Projeto

A Vinheria Agnello busca garantir a qualidade de seus vinhos monitorando o ambiente da adega.
O sistema desenvolvido capta temperatura, umidade e luminosidade e envia esses dados via MQTT para visualização e controle remoto.
O projeto demonstra a aplicação de Edge Computing, onde o ESP32 atua como nó inteligente de captura e envio de dados para a nuvem.

#Funcionalidades

📶 Conexão automática à rede Wi-Fi
🌡️ Leitura da temperatura e umidade (DHT11)
💡 Monitoramento da luminosidade ambiente (LDR)
☁️ Publicação de dados via MQTT (tópicos esp32/temp, esp32/umid, esp32/ldr)
💬 Recebimento de comandos MQTT (esp32/led) para controle do LED

🔄 Envio contínuo de dados a cada 5 segundos

🖥️ Exibição das leituras no Monitor Serial
