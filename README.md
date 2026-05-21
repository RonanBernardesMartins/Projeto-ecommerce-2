# ⚡ Vortex Engine — E-Commerce de Elite & Full Debug Workspace

> SPA de E-Commerce responsiva inspirada nos maiores varejistas de hardware do Brasil (KaBuM!, Pichau, Terabyte), integrada a um ecossistema completo de backoffice e monitoramento em tempo real operando 100% no Client-Side.

🔗 **[CLIQUE AQUI PARA TESTAR A APLICAÇÃO AO VIVO](https://github.com/RonanBernardesMartins/Projeto-ecommerce-2.git)**

---

## 🖥️ Sobre o Projeto

Este projeto simula uma arquitetura de e-commerce corporativa de ponta a ponta sem a necessidade de dependências de infraestrutura de servidores (Serverless/Full Front-End). Ele une a experiência de compra fluida do consumidor a ferramentas avançadas de administração e depuração de banco de dados.

A aplicação foi estruturada como uma **SPA (Single Page Application)**, garantindo transições instantâneas entre telas e renderização dinâmica baseada em estados.

---

## ✨ Funcionalidades Principais

### 🛒 Experiência do Consumidor (Storefront)
* **Interface Inspirada no Varejo de Hardware:** Layout focado em conversão, com Banner Hero promocional, faixas de benefícios e carrosséis horizontais de ofertas instantâneas (Flash Deals).
* **Ficha Técnica e Detalhes:** Páginas exclusivas para cada componente com árvore de navegação (Breadcrumbs), tópicos gerados dinamicamente e sistema de avaliação por estrelas.
* **Cálculo Reativo de Descontos:** Exibição dupla de preços (preço antigo riscado vs. preço final) aplicando dinamicamente as regras de desconto para fluxos à vista (PIX/Cartão 1x) ou parcelamento.
* **Módulos Integrados:** Simulador funcional de frete com prazos locais, central do cliente subdividida em abas (meus pedidos, segurança, dados cadastrais) e gateway de checkout seguro.

### ⚙️ Painel Administrativo & Engenharia de Debug (Backoffice)
* **Banco de Dados Chave-Valor Dinâmico:** Operações completas de `INSERT`, `UPDATE` e `DELETE` gerenciadas e persistidas localmente.
* **Upload Duplo de Mídia:** Suporte para injeção de imagens via upload de arquivos locais (convertidos em buffers Base64) ou por meio de URLs externas da web.
* **Gerenciador de Taxonomia:** CRUD completo de categorias com replicação e atualização de dados em cascata no inventário.
* **SQL Debug Logs:** Console central de auditoria que monitora e exibe em tempo real cada query, transação financeira, falhas de concorrência ou alterações de regras fiscais.
* **Mesa Financeira Amortizada:** Painel de controle capaz de ligar/desligar juros e alterar as taxas mensais de parcelamento, recalculando automaticamente os valores através de tabelas Price.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5** — Estruturação semântica e API de renderização.
* **Tailwind CSS** — Framework utilitário para design responsivo e estilização de alta fidelidade.
* **JavaScript (ES6+)** — Motor lógico de reatividade, manipulação do DOM e roteamento de views.
* **LocalStorage API** — Persistência de dados NoSQL local simulando queries de produção.
* **Lucide Icons** — Pacote de vetores modernos para consistência visual.
