# Automação de Cluster RKE2 com Ansible

Este repositório fornece playbooks Ansible para automatizar a instalação e configuração de um cluster Kubernetes RKE2. Simplifique o processo de implantação do seu cluster com esses playbooks pré-configurados, projetados para otimizar a configuração, garantir consistência e reduzir o esforço manual.

## Funcionalidades

- Instalação automatizada de cluster RKE2
- Gerenciamento de configuração
- Configuração de nós e atribuição de funções
- Fácil personalização e escalabilidade

## Requisitos

- Ansible 2.9+
- Acesso SSH aos nós alvo
- Sistemas Operacionais suportados: Distribuições Linux (Ubuntu, CentOS, etc.)

## Primeiros Passos

1. Clone o repositório
2. Atualize o arquivo de inventário com os detalhes dos seus nodes
3. Personalize as variáveis em `group_vars` conforme necessário
4. Instale a role do RKE2 em sua máquina ```bash ansible-galaxy role install lablabs.rke2```
5. Execute o playbook: `ansible-playbook site.yml`