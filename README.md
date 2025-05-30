# SentinelLog

Projeto de simulação de um ambiente SOC (Security Operations Center) para estudo e prática de Segurança da Informação.

## Objetivos
- Coletar e monitorar logs de servidores Linux, Windows, AWS e GCP
- Detectar eventos de segurança com Wazuh
- Analisar e correlacionar dados com ELK Stack (Elasticsearch, Logstash, Kibana)
- Automatizar respostas com scripts Python
- Gerenciar incidentes via GLPI

## Tecnologias
- Wazuh
- ELK Stack
- AWS CloudTrail
- GCP Audit Logs
- Python 3
- GLPI
- Docker

## Estrutura
📁 SentinelLog
├── logs/ # Logs coletados
├── scripts/ # Scripts Python de automação
├── alerts/ # Regras, alertas e relatórios
├── configs/ # Configurações (Wazuh, Logstash, etc)
├── docs/ # Documentações e prints
├── docker-compose.yml
├── requirements.txt
├── README.md

---

### 🐳 Etapa 4: Configurar Docker Compose (Wazuh + ELK)

Você pode usar o repositório oficial do Wazuh:

```bash
git clone https://github.com/wazuh/wazuh-docker.git
cd wazuh-docker
