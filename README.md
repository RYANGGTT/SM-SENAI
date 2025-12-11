📘 SM-SENAI — Sistema de Monitoramento de Salas

Aplicativo desenvolvido como parte do TCC no SENAI, voltado para o monitoramento inteligente de salas, controle visual de ocupação, gerenciamento de horários e integração com sensores reais via ESP32.

📱 Sobre o Projeto

O SM-SENAI é um sistema completo composto por:

Aplicativo Android (.apk)

Dispositivo físico com ESP32

Sensores de presença / contador de pessoas

Comunicação MQTT

Iluminação indicativa (LED ou sinalizador externo)

O objetivo é criar uma solução funcional para monitoramento de salas em tempo real, ideal para instituições educacionais, laboratórios, empresas e ambientes compartilhados.

✨ Funcionalidades do Aplicativo
🟢 Monitoramento em Tempo Real

Exibe se a sala está:

Livre

Ocupada

Em uso moderado

Status enviado pelo ESP32 via MQTT.

💡 Demonstração de Luz

Mostra no app o mesmo estado visual que aparece no sinalizador físico.

Perfeito para demonstrações no TCC.

📅 Cronograma das Salas

Visualização organizada dos horários:

Aulas

Reservas

Ocupações

Interface amigável.

✏️ Edição e Gerenciamento

Possibilidade de alterar informações do cronograma e configurações gerais dentro do aplicativo.

🔗 Comunicação MQTT

Recebimento e envio de dados totalmente integrados ao hardware real.

🛠️ Tecnologias Utilizadas
Aplicativo

Flutter / Android (ou a tecnologia que você me informar)

MQTT Client

Interface intuitiva para apresentação

Hardware

ESP32 / ESP8266

Sensor de presença ou VL53L0X (se quiser, adiciono)

LEDs / sinalizador externo

Protocolo MQTT (Mosquitto utilizado nos testes)
