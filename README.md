# Projeto DevOps Escritório Contábil

## Visão Geral
Este projeto cria um ambiente laboratorial simulando a infraestrutura básica de um escritório contábil, utilizando máquinas virtuais Windows Server gerenciadas pelo Vagrant e VirtualBox. Ele visa praticar conceitos de DevOps, Infra as Code e automação de provisionamento.

**Componentes:**
- **VM1 - AD Controller (Windows Server):** Controlador de Domínio com Active Directory.
- **VM2 - File Server (Windows Server):** Servidor de Arquivos integrado ao domínio.
- **VM3 - Banco de Dados & App (Windows Server):** MySQL + aplicação Python/Flask simulando um software contábil simples.

## Objetivos
- Aprender a criar e gerenciar múltiplas VMs com Vagrant.
- Provisionar serviços automaticamente via scripts Shell.
- Integrar AD, File Server e BD/Aplicação.
- Documentar e versionar toda a configuração.
- Praticar uma abordagem ágil na execução das tarefas usando Kanban.

## Ferramentas e Tecnologias
- **VirtualBox**
- **Vagrant**
- **Windows Server (licenças e ISOs do Azure Education)**
- **MySQL**
- **Python + Flask**
- **GitHub (para código e versionamento)**
- **VS Code (como IDE principal)**

## Requisitos
- Windows 11 (host)
- VirtualBox instalado
- Vagrant instalado
- Git instalado (para clonar o repositório)
- Acesso às ISOs do Windows Server e chaves de licença (caso necessário)
- Python (para o host ou a VM? A ser definido, mas o Flask rodará na VM3)

## Como Executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/rodrigoacelio/DEVOPS.git
   
