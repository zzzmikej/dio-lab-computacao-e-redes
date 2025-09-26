# ☁️ Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure

Este repositório contém o resumo e as anotações práticas do desafio da DIO **“Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure”**, com foco no entendimento dos conceitos de **computação e rede no Azure** e na aplicação prática da configuração de **máquinas virtuais (VMs)**.

---

## Objetivos do Desafio

- Revisar os **tipos de computação** disponíveis no Azure (VMs, containers, funções, etc.);  
- Configurar **recursos e dimensionamentos em VMs**;  
- Entender como funcionam os **serviços de rede** no Azure (VNet, sub-redes, DNS, VPN Gateway e ExpressRoute);  
- Documentar o processo de forma clara, consolidando o aprendizado.  

---

## O que foi aprendido

### 🔹 Tipos de Computação no Azure
- **Máquinas Virtuais (VMs)**: emulação de computadores físicos, com controle total sobre SO, memória, CPU e disco.  
- **Conjuntos de Dimensionamento de VMs**: permitem escalar horizontalmente ou reduzir automaticamente conforme a demanda.  
- **Conjuntos de Disponibilidade**: garantem alta disponibilidade das VMs distribuindo recursos entre domínios de falha.  
- **Área de Trabalho Virtual**: solução de virtualização de desktops e aplicativos executada na nuvem.  
- **Contêineres**: ambiente leve e isolado para execução de microsserviços.  
- **Azure Functions**: computação *serverless*, executada sob demanda em resposta a eventos.  

### 🔹 Serviços de Aplicação
- **App Services**: plataforma totalmente gerenciada para criar e hospedar aplicações em diversas linguagens (.NET, Node.js, Java, Python, PHP).  

### 🔹 Redes no Azure
- **VNet (Rede Virtual)**: possibilita comunicação entre recursos no Azure e redes locais.  
- **Sub-redes**: segmentação de redes virtuais para organização e segurança.  
- **Emparelhamento de Redes**: conecta VNets privadas diretamente.  
- **VPN Gateway**: envia tráfego criptografado entre rede local e rede no Azure.  
- **ExpressRoute**: conexão privada dedicada entre rede local e Azure, sem passar pela internet pública.  
- **DNS do Azure**: gerenciamento de domínios com desempenho e segurança, suporte a domínios privados e registros de alias.  

---

## Links Úteis

- [Documentação Oficial: Azure Compute & Networking Services](https://learn.microsoft.com/training/modules/describe-azure-compute-networking-services)  
- [Quickstart: Criar uma VM no Azure](https://learn.microsoft.com/azure/virtual-machines/)  
- [ExpressRoute - Microsoft Docs](https://learn.microsoft.com/training/modules/describe-azure-compute-networking-services/11-expressroute)  
- [Azure DNS - Microsoft Docs](https://learn.microsoft.com/training/modules/describe-azure-compute-networking-services/12-domain-name-system)  
- [Fórum e Artigos na DIO](https://web.dio.me/articles)  