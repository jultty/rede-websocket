# rede-websocket

## Descrição da Atividade

> A dupla deverá desenvolver uma aplicação web de chat que permita a comunicação em tempo real entre diferentes usuários conectados à mesma rede local.

## Requisitos

- [x] Solicitar ao usuário que informe seu nome antes de iniciar o envio de mensagens
- [x] Exibir mensagens imediatamente para todos os usuários conectados, sem recarregar a página
- [x] Exibir as mensagens do próprio usuário alinhadas à direita, com destaque visual (ex: fundo azul)
- [x] Exibir as mensagens dos demais usuários alinhados à esquerda, com o nome do remetente visível
- [x] Ter uma interface responsiva, adaptando-se bem a telas de dispositivos móveis (smartphones e tablets)
- [x] Ser acessível por meio do endereço IP local da máquina onde o servidor estiver rodando
- [x] Permitir que o professor acesse e utilize o chat a partir do próprio smartphone

### Requisitos Técnicos

- [ ] Uso de Flask com Flask-SocketIO e Eventlet
- [x] Estrutura de diretórios conforme boas práticas do Flask (app.py, templates/ e opcionalmente static/)
- [x] Conexão WebSocket utilizando socketio.run(app, host="0.0.0.0", port=8000) para permitir acesso externo
- [x] HTML com campos para nome do usuário, entrada de mensagens e exibição das mensagens em tempo real
- [x] Utilização de JavaScript para integrar com o WebSocket e atualizar dinamicamente a interface

