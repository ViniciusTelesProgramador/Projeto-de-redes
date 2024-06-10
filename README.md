# Projeto-de-redes
Como parte do nosso projeto final na disciplina de Redes, realizamos uma implementação completa de segmentação e comunicação de redes utilizando VLANs, DHCP e pfSense. Nosso objetivo foi criar uma infraestrutura de rede robusta, eficiente e segura para a Faculdade "TSEC".

🚀 Principais Componentes do Projeto
Firewall pfSense: Configuração de interfaces WAN e LAN, além de VLANs para segmentação de rede.
Switch Core: Configurado para suportar e distribuir VLANs para sub-redes distintas.
Sub-redes Segmentadas:
VLAN 100 (Professores): 192.168.100.0/25
VLAN 200 (Alunos): 192.168.300.0/19
VLAN 300 (Funcionários): 10.0.0.0/22
Servidores DHCP: Configurados no pfSense para atribuir endereços IP automaticamente em cada VLAN.

📈 Resultados Obtidos
Comunicação Eficiente e Segura: Segmentação de rede através de VLANs.
Gerenciamento de Rede: Simplificado com a configuração de servidores DHCP dedicados.
Eficiência e Escalabilidade: Implementação permite fácil administração e crescimento da rede sem recabeamento físico.

🔧 Ferramentas Utilizadas
VMware: Para simulação da infraestrutura de rede.
CLI: Para configuração dos switches.
pfSense: Como firewall e servidor DHCP.

💡 Aprendizados
Através deste projeto, adquirimos habilidades práticas em:
Configuração e gerenciamento de VLANs.
Implementação e administração de firewalls.
Utilização de ferramentas de virtualização para testes e validações de rede.

🔍 Verificação Prática
Realizamos testes práticos onde computadores em cada sub-rede receberam endereços IP corretos via DHCP, confirmando o funcionamento adequado da segmentação de rede e a eficiência da configuração dos servidores DHCP.

🎓 Conclusão
Este projeto nos proporcionou uma compreensão aprofundada de como segmentar e gerenciar redes de forma eficiente e segura, aplicando conceitos teóricos na prática.

Agradecemos ao Professor Rafael Cunha pela orientação e apoio, e a todos os colegas que contribuíram para o sucesso deste projeto.
