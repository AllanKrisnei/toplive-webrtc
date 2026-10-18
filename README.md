# 🎥 TOPlive - Transmissão de Tela em Tempo Real

O **TOPlive** é uma aplicação web focada no compartilhamento rápido e prático de tela entre usuários diretamente pelo navegador, sem a necessidade de instalar nenhum software de terceiros. 

Este projeto foi construído como parte do meu portfólio de desenvolvimento Front-end, consolidando conhecimentos práticos em manipulação de DOM e conexões ponto a ponto (P2P).

## 🚀 Funcionalidades

- **Geração Automática de ID:** Cada usuário recebe um identificador único ao abrir a aplicação.
- **Transmissão de Tela (Host):** Captura a tela do usuário e a disponibiliza para conexão.
- **Recepção de Transmissão (Client):** Permite assistir à tela de outro usuário inserindo o ID correspondente.
- **Baixa Latência:** Utiliza a tecnologia WebRTC para conexão direta entre os computadores, garantindo velocidade na transmissão de vídeo.

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação semântica da interface.
- **CSS3:** Estilização, layout flexível (Flexbox) e design responsivo.
- **JavaScript (Vanilla):** Lógica de captura de mídia (MediaDevices API) e manipulação de eventos da interface.
- **PeerJS:** Biblioteca que abstrai a complexidade do WebRTC, facilitando a conexão de dados e mídia P2P.
