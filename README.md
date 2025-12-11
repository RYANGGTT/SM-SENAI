O SM-SENAI é um projeto desenvolvido para o TCC do SENAI, com o objetivo de criar um sistema inteligente capaz de monitorar a ocupação de salas em tempo real.
A solução integra hardware (ESP32 + sensores), comunicação MQTT e um aplicativo Android, permitindo visualizar o status da sala e gerenciar informações de forma prática.

🎯 Objetivo do Projeto

- O sistema foi criado para facilitar o controle e a organização de salas, oferecendo:

- Monitoramento automático da ocupação

- Indicação visual do estado da sala

- Registro de uso e apoio à gestão

- Interface mobile para acompanhamento e edição

O foco principal é demonstrar como tecnologias acessíveis podem ser integradas para resolver problemas reais dentro do ambiente escolar.

🧩 Como o Sistema Funciona

1. Sensores instalados na sala (ex.: contagem de pessoas).

2. O ESP32 processa as informações e envia os dados via MQTT.

3. O servidor MQTT repassa essas informações ao aplicativo.

4. O app SM-SENAI exibe o estado atual da sala, cronograma e informações editáveis.

[Sensores/ESP32] → MQTT → [Aplicativo SM-SENAI]


📱 Sobre o Aplicativo

- O app foi desenvolvido para complementar o projeto, permitindo:

- Ver o estado da sala (livre / ocupada / uso moderado)

- Visualizar a simulação da luz indicativa

- Consultar o cronograma da sala

- Editar informações e acompanhar atualizações em tempo real

👉 Download: (adicione o link da Release aqui no GitHub)

🛠 Tecnologias Utilizadas

- ESP32

- Sensores de ocupação

- MQTT

- plicativo Android

- Plataforma de teste e demonstração para TCC

👨‍🏫 Projeto Acadêmico

Este projeto foi desenvolvido como parte do Trabalho de Conclusão de Curso (TCC) – SENAI, demostrando:

- Automação

- IoT

- Monitoramento inteligente

- Integração entre hardware e software
