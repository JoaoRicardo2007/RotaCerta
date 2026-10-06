# RotaCerta - Sistema Inteligente de Gestão de Frota e Logística

> **Atividade Prática de Engenharia de Requisitos**  
> Documentação técnica para concepção e levantamento de requisitos de uma plataforma de gestão de entregas e otimização de rotas.

---

## 📌 1. Visão Geral do Projeto

### Ramo de Atuação
Tecnologia da Informação aplicada à Logística e Mobilidade Urbana.

### Problema
Empresas de logística de médio porte enfrentam perdas operacionais significativas e altos custos com combustível decorrentes da ausência de roteirização dinâmica em tempo real. Além disso, a falta de integração imediata entre os motoristas em campo e o painel central de controle gera gargalos de comunicação e atrasos no atendimento ao cliente final.

### Solução Proposta
O **RotaCerta** é uma solução composta por um painel web administrativo e um aplicativo mobile para condutores. A plataforma automatiza a criação de rotas otimizadas considerando o tráfego atual, gerencia capacidades de carga, fornece acompanhamento em tempo real para o gestor e envia rastreamento atualizado para os clientes finais.

---

## 👥 2. Estrutura da Equipe de Engenharia de Requisitos

| Papel | Responsabilidades |
| :--- | :--- |
| **Analista de Requisitos** | Conduz o levantamento de necessidades com os *stakeholders*, facilita oficinas de elicitação e traduz objetivos de negócio em especificações técnicas. |
| **Tech Writer (Documentação)** | Mantém atualizada a Especificação de Requisitos do Sistema (ERS), o glossário do domínio, diagramas de arquitetura e casos de uso. |
| **Engenheiro de Processos (BPM)** | Mapeia os fluxos atuais (*As-Is*) e desenha o fluxo otimizado pelo novo software (*To-Be*). |
| **Engenheiro de Requisitos (Líder)** | Gerencia mudanças de escopo, define priorizações (método MoSCoW) e garante a rastreabilidade dos requisitos durante o ciclo de vida. |
| **Analista de QA** | Elabora critérios de aceite testáveis para cada requisito e valida se as entregas funcionais e não funcionais atendem às especificações. |

---

## 🏬 3. Cliente e Stakeholders

**Cliente Parceiro:** *ExpressLog Logística e Transportes* (Operadora logística com frota de 45 veículos urbanos).

### Mapeamento de Stakeholders

* **Diretor de Operações (Sponsor):** Foco em ROI, redução de custos operacionais e metas de eficiência de entregas.
* **Gestor de Frota (Usuário Chave - Web):** Responsável por atribuir rotas, monitorar motoristas via mapa e gerenciar imprevistos operacionais.
* **Motoristas (Usuário Chave - Mobile):** Executam as rotas, registram comprovantes de entrega e atualizam o status dos pedidos no aplicativo.
* **Cliente Final (Consumidor):** Acompanha o status e o link de rastreamento do pacote em tempo real.
* **Equipe de SAC / Atendimento:** Consulta rápida do histórico de entregas para resolução de dúvidas e incidentes.

---

## 📝 4. Roteiro de Entrevista para Elicitação de Requisitos

**Entrevistado:** Gestor de Frota  
**Objetivo:** Mapear o processo atual de planejamento de rotas e mapear os requisitos da interface administrativa.

1. **Contexto Operacional:** Pode detalhar o passo a passo de como é feita a montagem das rotas e a distribuição de pacotes entre os motoristas hoje?
2. **Identificação de Gargalos:** Quais são os principais motivos de atraso ou falhas no fluxo atual de entregas?
3. **Gestão de Contingências:** Como a equipe reage quando ocorrem imprevistos (ex: quebra de veículo ou ausência do destinatário)?
4. **Requisitos Funcionais da Tela Central:** Quais indicadores e informações precisam estar acessíveis na dashboard em tempo real?
5. **Relatórios e KPIs:** Quais relatórios analíticos são indispensáveis para avaliar a performance diária da operação?
6. **Desempenho e Carga (Não Funcional):** Qual a estimativa de usuários simultâneos no sistema durante os horários de pico?
7. **Integrações com Sistemas Legados:** Existe integração obrigatória com ERPs, emissores de nota fiscal ou outros softwares internos?
8. **Visão de Valor:** Qual funcionalidade traria o maior ganho direto na sua rotina diária?

---

## 🛠️ Tecnologias e Ferramentas Sugeridas
* **Documentação:** Markdown, Enterprise Architect / Visual Paradigm.
* **Modelagem de Processos:** Bizagi BPMN / Miro.
* **Gestão de Tarefas:** Jira Software / Trello.
