<div align="center">

<picture>
  <source media="(max-width: 900px)" srcset="./assets/profile-header-mobile.svg" />
  <img src="./assets/profile-header.svg" width="100%" alt="Breno Ludgerio — Desenvolvimento de Software, ITSM, Automação e Redes" />
</picture>

[Projetos](#projetos-em-destaque) · [Outros projetos](#outros-projetos) · [Competências](#competências-e-ferramentas) · [Como trabalho](#da-ideia-à-implementação)

[LinkedIn](https://www.linkedin.com/in/breno-ludgerio-450070369/) · [Zenix Digital](https://zenixworks.com/)

</div>

## Sobre mim

Sou **Breno Ludgerio**, estudante de **Análise e Desenvolvimento de Sistemas na FAESA**. Atuo em IT Service Management na **Vale S.A.**, tenho experiência em suporte de redes N1/N2 e conecto desenvolvimento de software, automação e infraestrutura.

Sou também **cofundador e responsável pelo desenvolvimento web da [Zenix Digital](https://zenixworks.com/)**, onde participo das decisões técnicas e transformo ideias em sites e aplicações funcionais.

---

## Projetos em destaque

### 01 — NexusOps

> **Projeto principal** · Engenharia full stack aplicada à gestão de serviços.

Plataforma de ITSM com incidentes, problemas e solicitações, SLAs, notificações, histórico e administração por perfil. O dashboard consulta registros persistidos em SQLite por uma API autenticada.

**Engenharia:** monólito modular, migrations SQL, autorização no backend, sessões com proteção CSRF e testes de API e navegador em CI para Windows e Ubuntu. Demonstração local com dados fictícios.

**Tecnologias:** React · TypeScript · Node.js · Fastify · SQLite · Vitest · Playwright<br>
[Repositório](https://github.com/ludgerios/nexusops) · [Arquitetura](https://github.com/ludgerios/nexusops/tree/main/docs/architecture) · [Executar demonstração local](https://github.com/ludgerios/nexusops#executar-no-windows)

---

### 02 — Distribuidora Preço Bom

Aplicação demonstrativa de delivery com catálogo, carrinho, checkout, acompanhamento de pedidos e painel administrativo. Produtos e pedidos são persistidos no D1 local.

**Engenharia:** API em Worker, validação com Zod, autenticação administrativa e testes com Vitest e Playwright. Dados fictícios e pagamentos simulados; a demonstração é independente da operação da loja.

**Tecnologias:** React · TypeScript · Vite · Hono · Cloudflare Workers · D1<br>
[Repositório](https://github.com/ludgerios/distribuidora-preco-bom) · [Arquitetura](https://github.com/ludgerios/distribuidora-preco-bom/blob/main/ARCHITECTURE.md) · [Executar demonstração local](https://github.com/ludgerios/distribuidora-preco-bom#executar-localmente)

---

### 03 — ServiceNow — notificações de Problem Tasks

Scheduled Job que consulta tarefas de problemas, acompanha prazos e dispara eventos para notificações por e-mail e Microsoft Teams.

**Engenharia:** consultas com GlideRecord e regras de data com GlideDateTime. O código público usa identificadores demonstrativos e requer configuração de tabelas, eventos e notificações em uma instância própria.

**Tecnologias:** JavaScript · ServiceNow · GlideRecord · GlideDateTime<br>
[Repositório](https://github.com/ludgerios/ServiceNow-Problem-Task-Notification-Job) · [Código e configuração](https://github.com/ludgerios/ServiceNow-Problem-Task-Notification-Job#readme)

<details>
<summary>Ver capturas reais do NexusOps e da Distribuidora</summary>

**NexusOps · Dashboard com dados demonstrativos persistidos**

<a href="https://github.com/ludgerios/nexusops">
  <img src="https://raw.githubusercontent.com/ludgerios/nexusops/main/docs/screenshots/dashboard.png" width="100%" alt="Dashboard real do NexusOps, com indicadores, gráficos e chamados recentes" />
</a>

**Distribuidora Preço Bom · Catálogo demonstrativo**

<a href="https://github.com/ludgerios/distribuidora-preco-bom">
  <img src="./assets/projects/preco-bom.jpg" width="100%" alt="Captura real da demonstração da Distribuidora Preço Bom, com catálogo e preços de teste" />
</a>

</details>

---

## Outros Projetos

- **[Patagônia — expedição ao fim do mundo](https://github.com/ludgerios/site-patagonia-turismo)** — Site editorial responsivo com destinos, galeria, vídeo local e formulário demonstrativo. Projeto acadêmico.<br>
  **Tecnologias:** HTML · CSS · JavaScript · [Demonstração online](https://ludgerios.github.io/site-patagonia-turismo/)

- **[Power Automate — notificações de compliance](https://github.com/ludgerios/power-automate-compliance-notifications-)** — Laboratório com fluxo pai importável, validações, Adaptive Cards e registro de envios. Dados fictícios; o fluxo filho está documentado como evolução.<br>
  **Tecnologias:** Power Automate · Excel Online · Microsoft Teams · Adaptive Cards

- **[Bot Discord](https://github.com/ludgerios/botdiscord)** — Bot de estudos com comandos utilitários, eventos de membros e calculadora aritmética limitada por AST.<br>
  **Tecnologias:** Python · discord.py

<details>
<summary>Ver captura do site Patagônia</summary>

**Patagônia · Site acadêmico publicado**

<a href="https://ludgerios.github.io/site-patagonia-turismo/">
  <img src="./assets/projects/patagonia.jpg" width="100%" alt="Captura real da página inicial do site Patagônia, com navegação e apresentação editorial" />
</a>

</details>

---

## Competências e ferramentas

- **Desenvolvimento:** HTML5, CSS3, JavaScript, Python, Java, interfaces responsivas e APIs REST. React, TypeScript, Node.js, Fastify, Vite e Hono nos projetos.
- **ITSM e automação:** Incident Management, Problem Management, Business Rules, Scheduled Script Executions, Flow Designer, UI Policies, Power Automate, Adaptive Cards, integrações e JSON.
- **Redes e infraestrutura:** suporte remoto N1/N2, configuração de roteadores, diagnóstico de conectividade, monitoramento com Zabbix e operação com IXC Soft.
- **Dados e qualidade:** SQL, T-SQL, SharePoint, SQLite, testes com Vitest e Playwright, validação de entradas e documentação técnica.
- **Entrega e ferramentas:** Git, GitHub, GitHub Actions, Visual Studio Code e Azure DevOps; publicação web, GitHub Pages e Cloudflare Workers, com D1 local no projeto demonstrativo.

<details>
<summary>Ferramentas por área</summary>

**Programação e desenvolvimento web**

<p>
  <img src="./assets/skills/javascript.svg" height="24" alt="JavaScript" />
  <img src="./assets/skills/python.svg" height="24" alt="Python" />
  <img src="./assets/skills/java.svg" height="24" alt="Java" />
  <img src="./assets/skills/react.svg" height="24" alt="React — utilizado em projetos" />
</p>

**ITSM e automação**

<p>
  <img src="./assets/skills/servicenow.svg" height="24" alt="ServiceNow" />
  <img src="./assets/skills/power-automate.svg" height="24" alt="Microsoft Power Automate" />
  <img src="./assets/skills/teams.svg" height="24" alt="Microsoft Teams" />
</p>

**Redes e infraestrutura**

<p>
  <img src="./assets/skills/zabbix.svg" height="24" alt="Zabbix" />
  <img src="./assets/skills/ixc-soft.svg" height="24" alt="IXC Soft" />
</p>

**Dados e ferramentas de desenvolvimento**

<p>
  <img src="./assets/skills/sql-server.svg" height="24" alt="SQL Server" />
  <img src="./assets/skills/git.svg" height="24" alt="Git" />
  <img src="./assets/skills/azure-devops.svg" height="24" alt="Azure DevOps" />
</p>

**Cloud e publicação**

<p>
  <img src="./assets/skills/cloudflare-workers.svg" height="24" alt="Cloudflare Workers" />
  <img src="./assets/skills/github-pages.svg" height="24" alt="GitHub Pages" />
</p>

</details>

---

## Da ideia à implementação

### <img src="./assets/approach/web.svg" width="28" height="28" alt="" /> Soluções web

Entender a necessidade, desenhar a interface e implementar funcionalidades com foco em quem vai usar.

### <img src="./assets/approach/automation.svg" width="28" height="28" alt="" /> Automação e integração

Conectar etapas e plataformas, reduzir tarefas repetitivas e validar o resultado de cada fluxo.

### <img src="./assets/approach/diagnostics.svg" width="28" height="28" alt="" /> Resolução de problemas

Investigar falhas com monitoramento e diagnóstico de redes, identificar a causa e verificar a solução.

---

## Atividade no GitHub

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=ludgerios&theme=tokyonight" width="100%" alt="Resumo de atividade pública do perfil GitHub" />
</p>

---

<div align="center">

**Breno Ludgerio** · [GitHub](https://github.com/ludgerios) · [LinkedIn](https://www.linkedin.com/in/breno-ludgerio-450070369/)<br>
Cofundador e responsável pelo desenvolvimento web · [Zenix Digital](https://zenixworks.com/)

</div>
