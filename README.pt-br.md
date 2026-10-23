# Henrique Cardamone

**SAP Software Developer II** · SAP ABAP · .NET 8 (C# 12) · Agentes de IA (MCP)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/henriquecardamone/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:henrique.cardamonetec@gmail.com)
[![Currículo PT](https://img.shields.io/badge/Currículo-PT--BR-1a1a1a?style=for-the-badge)](./resume/pt-br%20-%20Henrique%20Cesar%20Cardamone%20dos%20Santos.pdf)

🇺🇸 [Read in English](./README.md)

---

## Sobre

Com mais de 12 anos em TI, atuo como **SAP Software Developer II** no R&D da Sovos, desenvolvendo soluções globais de **Tax Compliance** — produtos customizados no SAP ECC e S/4HANA para **Outbound, Inbound e Tax Reporting**, incluindo a adequação de sistemas legados à **Reforma Tributária Brasileira (IBS/CBS)**.

A vivência em AMS me deu visão crítica para diagnosticar gargalos complexos; a trajetória como SDET me ensinou a tratar automação e testes como parte do produto desde o dia zero.

## Meu diferencial: Engenharia de Software com Agentes de IA no ecossistema SAP

Arquitetei e desenvolvi do zero um **MCP Server proprietário em .NET 8** que conecta agentes de IA (Claude, Cursor, Devin) ao SAP:

- **Do ECC 6.0 ao S/4HANA Cloud (Basis 7.00+)** — MCPs públicos para SAP exigem ADT REST (Basis 740+); este cobre também o legado, que ainda roda em boa parte das empresas.
- **Roteamento multicanal** — Alternância automática entre RFC (SAP NCo), ADT REST e WebGUI (Playwright) para ler qualquer objeto do repositório ABAP (classes, FMs, DDIC) e analisar impacto (where-used, transports) em tempo real.
- **Segurança e performance** — Somente leitura por design: operações de escrita viram playbooks em `.md` (Suggestion Mode) para o desenvolvedor executar. Cache isolado por SID/usuário.
- **Impacto no time** — Repositório centralizado de skills e playbooks que guiam a IA na análise de código, documentação e roteiros de teste, acelerando a adoção por desenvolvedores seniores e reduzindo os ciclos de entrega.

📄 [Leia o post no LinkedIn](https://lnkd.in/p/eKjySUdr)

## Outras entregas

- **Ferramentas ABAP de alta performance** — Extração, processamento massivo e análise de payloads fiscais complexos (XML/JSON), reduzindo drasticamente o tempo de troubleshooting.
- **Automação de testes SAP** — Liderança técnica numa esteira CI/CD de testes regressivos para SAP ECC com Robot Framework, Python e Azure Pipelines.
- **API Mocking** — Serviço em FastAPI (Python) distribuído como executável standalone, simulando fluxos completos de conformidade fiscal para as equipes SAP testarem sem depender de sistemas externos.

## Tecnologias

**SAP:** ABAP · S/4HANA · SAP ECC · SAP NCo 3.1 · ADT REST · abapGit
**Back-end:** .NET 8 (C# 12) · Python · SQL
**IA:** Model Context Protocol (MCP) · Integração LLM (Claude, Cursor, Devin)
**DevOps & QA:** Azure DevOps · CI/CD pipelines · Docker · Robot Framework · Playwright

![SAP](https://img.shields.io/badge/SAP_ABAP-0FAAFF?style=flat-square&logo=sap&logoColor=white)
![.NET](https://img.shields.io/badge/.NET_8-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23_12-239120?style=flat-square&logo=csharp&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Robot Framework](https://img.shields.io/badge/Robot_Framework-000000?style=flat-square&logo=robotframework&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

## Projetos públicos

- **[comparejsoncustom](https://github.com/hcardamone/comparejsoncustom)** — Pacote Python (MIT) que verifica se um objeto JSON é subconjunto de outro, ignorando atributos específicos na comparação.
- **[sap-automation-poc](https://github.com/hcardamone/sap-automation-poc)** — Prova de conceito de automação de processos SAP com Robot Framework.
- **[robotframework-roboCopChatBot-Telegram](https://github.com/hcardamone/robotframework-roboCopChatBot-Telegram)** — Bot para Telegram com Robot Framework.

## Artigos e posts

- **[Career milestone: I built an MCP Server for SAP](https://lnkd.in/p/eKjySUdr)** — Por que MCPs públicos para SAP param no Basis 740+, e como um servidor em .NET 8 cobre do Basis 700 ao S/4HANA Cloud.
- **[[2023] Azure Pipeline Efficiency: Stages in Azure Pipelines concepts about it](https://www.linkedin.com/pulse/2023-azure-pipeline-efficiency-stages-pipelines-henrique-cardamone)**
- **[[2023] Azure Pipeline Efficiency: Streamlining Your Azure Pipeline with Reusable Modules/Stages](https://www.linkedin.com/pulse/2023-azure-pipeline-efficiency-streamlining-your-henrique-cardamone)**
- **[[2023] Git: Using Git Submodules for effective collaboration in Project development](https://www.linkedin.com/pulse/2023git-using-git-submodules-effective-collaboration-cardamone)**

➡️ [Todos os artigos no LinkedIn](https://www.linkedin.com/today/author/henriquecardamone)

## Formação

- **Pós-graduação em Engenharia de Software** — Universidade Estácio (Jul 2023 – Jul 2024)
- **Bacharelado em Ciência da Computação** — Universidade Anhembi Morumbi (Jun 2019 – Ago 2023)

---

💬 **Aberto a conversas sobre:** AI-Assisted Development, Protocolo MCP, Integração de LLMs em sistemas legados e desenvolvimento SAP para Tax Compliance.
