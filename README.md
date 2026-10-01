# 🚛 Frota.AI - Dashboard de Diagnóstico e Telemetria

Um painel corporativo desenvolvido para suporte à decisão na gestão de frotas de veículos pesados. Esta aplicação web utiliza Inteligência Artificial generativa para analisar sintomas mecânicos, métricas de consumo de combustível e KPIs de logística, funcionando como um assistente de engenharia de frota em tempo real.

## 🚀 Funcionalidades Principais

* **Assistente Especializado em Frotas:** IA configurada com um *System Prompt* restrito ao domínio de mecânica pesada, logística e telemetria (ex: diagnóstico de falhas de injeção, análises comparativas de motores diesel).
* **Interface Corporativa (SPA):** Design limpo e moderno, inspirado nas principais plataformas de IA do mercado, com navegação fluida em ecrã único.
* **Gestão de Sessões em Memória:** Histórico lateral interativo que permite alternar entre diferentes diagnósticos sem perder o contexto da conversa.
* **Renderização Avançada de Dados:** Transformação em tempo real do Markdown gerado pela IA em HTML nativo (tabelas de dados, listas estruturadas e destaques técnicos).
* **Dark/Light Mode:** Alternância dinâmica de tema para conforto visual operacional.
* **Segurança de Credenciais:** Arquitetura robusta com separação de configurações e leitura segura de chaves de API através do `appsettings.json`.

## 🛠️ Tecnologias Utilizadas

* **C# 12 & .NET 8 (ou superior):** Core lógico e estrutural da aplicação.
* **ASP.NET Core Blazor (Interactive Server):** Framework para a construção da interface reativa de página única.
* **Groq API (`openai/gpt-oss-20b`):** Motor de inferência de Inteligência Artificial de altíssima velocidade.
* **Markdig:** Biblioteca de processamento para conversão de sintaxe Markdown em HTML seguro.
* **Integração de APIs REST:** Utilização de `HttpClient` e `JsonSerializer` para comunicação assíncrona.

## ⚙️ Como Executar o Projeto

1. Clone este repositório para a sua máquina local:
   ```bash
   git clone [https://github.com/SEU_USUARIO/DashboardFrota.git](https://github.com/SEU_USUARIO/DashboardFrota.git)