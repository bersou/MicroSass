# Velvet Studio

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white) ![License](https://img.shields.io/badge/License-Proprietary-gray)

> MicroSaaS de Agendamento Especializado em Protocolos de Depilação — A Arte da Suavidade Extrema.

## Sobre o Projeto

Velvet Studio é uma Single Page Application (SPA) focada em digitalizar o agendamento para estúdios de estética especializados em técnicas de depilação (Cera Quente e Roll-on).

Diferente de agendas genéricas, Velvet organiza serviços como "Protocolos" e prioriza a experiência do cliente com informação estratégica (tempo, conforto térmico, best-seller) para facilitar decisões rápidas.

## Demo / Imagens

> As imagens abaixo devem ser adicionadas ao repositório em `assets/` posteriormente. Solicite upload das imagens se desejar que eu as inclua.

![Aplicação - Protocolo de Depilação 1](assets/velvet-1.jpg)
*Exemplo de ambiente e protocolo*.

![Aplicação - Protocolo de Depilação 2](assets/velvet-2.jpg)
*Detalhe de produto/óleo utilizado nos protocolos*.

## Funcionalidades Principais

- Mobile-First: Interface responsiva otimizada para smartphones (WhatsApp/Instagram).
- Catálogo Inteligente: Serviços com metadados (Best-Seller, Nível de Conforto Térmico, Tempo de Procedimento).
- Agendamento em 3 passos: Seleção > Data/Hora > Confirmação.
- Persistência local: Histórico do cliente salvo em LocalStorage para uso sem login imediato.
- Arquitetura No-Build: React + Tailwind via CDN (sem Node.js/NPM obrigatório para visualização).

## Tecnologias

- Core: React.js 18 (UMD / Global)
- Estilização: Tailwind CSS (via CDN)
- Marcação: HTML5
- Ícones: SVG nativos

## Como Visualizar

O projeto é plug & play — não exige instalação local de Node/NPM para visualizar:

1. Baixe ou clone o repositório.
2. Abra `index.html` em um navegador moderno (Chrome, Safari, Edge).
3. Para experiência mobile real, faça deploy em Netlify/Vercel/GitHub Pages.

## Status & Licença

- Status: MVP (Produto Mínimo Viável) — pronto para uso.
- Licença: Proprietária.

Velvet Studio © 2025 — Todos os direitos reservados.

(Commit realizado: "docs: restructure README, add badges (images to be added later)")