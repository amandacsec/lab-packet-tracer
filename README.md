Laboratório de Redes: Conectividade LAN e WLAN
Este projeto documenta a montagem de uma rede local simples utilizando o simulador Cisco Packet Tracer, integrando dispositivos cabeados e sem fio.

📱 Visão Geral da Topologia
A rede é composta por:
1 Switch (2960-24TT)
2 Computadores (PC-PT) conectados via cabo de cobre direto.
1 Access Point para sinal sem fio.
1 Laptop conectado via Wi-Fi.

![Capa do Projeto](./capa-projeto.jpg)

🛠️ O que foi desenvolvido
Montagem Física: Conexão dos dispositivos utilizando cabos Ethernet (Cobre Direto).
Configuração Lógica: Atribuição de endereços IP estáticos para cada máquina na mesma sub-rede (192.168.1.x).
Implementação de Wi-Fi: Substituição da placa de rede do Laptop por uma placa wireless para conexão via Access Point.

🔍 Resolução de Problemas (Troubleshooting)
Durante a prática, identifiquei um erro comum: o Laptop estava conectado fisicamente à antena, mas não conseguia se comunicar com os outros PCs (o comando ping falhava).

O problema: Ao trocar a placa de rede do Laptop, o endereço IP foi resetado para 0.0.0.0.
A solução: Reconfigurei manualmente o endereço IP estático para 192.168.1.3. Após isso, a comunicação foi estabelecida com sucesso.

🎓 Conclusão
Este laboratório reforçou conceitos fundamentais de endereçamento IP, tipos de cabos e a importância de validar a configuração lógica após alterações no hardware.
