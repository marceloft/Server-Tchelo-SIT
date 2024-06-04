# Server Tchelo SIT
Servidor em faze de testes e MUITOS problemas podem acontecer.

# IP para adicionar no SIT Manager
http://26.190.219.125:6969/

# Protocolos de HOST DE RAID
**Relay:** Toda a informação é passada para o servidor e devolvida para os clientes
- Pode causar desync (transmissão de dados pela internet/Radmin)
- Pode causar ping alto (se os clientes morarem muito longe do servidor (São Paulo))

**Peer-to-Peer:** Toda a informação é passada de cliente para cliente **(Sempre use AUTOMATIC)**
- Obrigatório colocar o SEU IP do Radmin em F12 -> StayInTarkov
- - UDPServerLocalIPv4
- - UDPServerPublicIP
- Pode causar queda de FPS (muita informação sendo processada no Host)
- Pode causa ping alto (se os clientes que conectarem no Host morarem muito longe)
