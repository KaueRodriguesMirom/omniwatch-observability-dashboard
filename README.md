# 🌐 OmniWatch - Observability & Infrastructure Dashboard

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Status](https://img.shields.io/badge/status-active-success.svg)

> Um dashboard moderno para monitoramento em tempo real da saúde, latência e disponibilidade de microsserviços e infraestrutura de rede.

🔗 **[Acesse o projeto rodando ao vivo aqui] (https://omniwatch-observability-dashboard.vercel.app/)**

## 🎯 Sobre o Projeto
No ecossistema de TI corporativo (especialmente em telecomunicações e grandes transações), a observabilidade não é um luxo, é uma necessidade. O **OmniWatch** foi desenvolvido para simular a visão de um NOC (Network Operations Center) ou time de SRE (Site Reliability Engineering). 

Ele monitora de forma simulada:
- Nós de Rede (Ex: Core 5G, Monitoramento de Fibra)
- APIs Gateways (Ex: Pagamentos, Provisionamento)
- Bancos de Dados e Servidores de Autenticação

## ✨ Funcionalidades
- **Real-Time Updates:** Simulação de *polling* contínuo com `useEffect` para atualizar latências e status dos nós.
- **Detecção de Anomalias:** Algoritmo que simula degradação de serviço (aumentando latência) e quedas (offline), alertando o operador visualmente.
- **Cálculo de SLA/Uptime:** Exibição da saúde global do sistema baseada na quantidade de serviços operacionais.
- **UI/UX Premium:** Interface limpa em Dark Mode, desenhada com Tailwind CSS para reduzir a fadiga visual de operadores.

## 🛠️ Tecnologias Utilizadas
- **Frontend:** React (Hooks: useState, useEffect)
- **Estilização:** Tailwind CSS (com foco em utilitários de estado visual e animações sutis como o *ping* de status).
- **Ícones:** SVG inline e componentes customizados para evitar dependências pesadas.

## 🚀 Como executar localmente

1. Clone o repositório:
\`\`\`bash
git clone https://github.com/SEU_USUARIO/omniwatch-dashboard.git
\`\`\`
2. Instale as dependências:
\`\`\`bash
npm install
\`\`\`
3. Inicie o servidor de desenvolvimento:
\`\`\`bash
npm run dev
\`\`\`

## 🧠 Próximos Passos (Roadmap)
Como analista de sistemas, enxergo as seguintes evoluções para este produto:
- [ ] Integração com uma API real (Prometheus/Grafana via REST).
- [ ] Adicionar gráficos de série temporal reais utilizando bibliotecas como Recharts.
- [ ] Implementar sistema de login e permissões (RBAC) para operadores e administradores.

---
*Desenvolvido com dedicação por [Seu Nome](LINK_DO_SEU_LINKEDIN)*
