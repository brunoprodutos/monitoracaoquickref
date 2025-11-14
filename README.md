# Product Briefing: Monitoração 24x7

## 📋 Sumário Executivo

### O que é o produto?

**Monitoração 24x7** é uma solução gerenciada de observabilidade empresarial que combina tecnologia de ponta, processos padronizados e suporte especializado para garantir a disponibilidade e performance de infraestruturas críticas na nuvem AWS.

### Para quem é?

Empresas que operam infraestruturas críticas na AWS e necessitam de:

- Vigilância ininterrupta de seus ambientes
- Resposta rápida a incidentes
- Redução do MTTR (Mean Time To Repair)
- Expertise especializada sem manter equipe própria 24x7

### Proposta de Valor Principal

> **"Transformamos complexidade em tranquilidade operacional, garantindo que sua infraestrutura AWS esteja sempre disponível, performática e otimizada."**

---

## 🎯 Visão Geral do Produto

### Missão

Prover monitoramento proativo e resposta imediata a incidentes, reduzindo o tempo de indisponibilidade e garantindo a continuidade dos negócios de nossos clientes.

### Principais Benefícios

- ⏱️ **Redução no MTTR** através de ações automatizadas
- 🔍 **Visibilidade completa** da infraestrutura em tempo real
- 👥 **Economia** se comparado a equipe própria 24x7
- 📈 **Melhoria contínua** com gestão de conhecimento e procedimento
- 🛡️ **Garantia de SLA** com penalidades contratuais

---

## 🏆 Tiers de Serviço

### **Essential Tier**

*Para operações que precisam de monitoramento confiável com orçamento otimizado*

#### Características Principais:

- ✅ Monitoramento 24x7 com equipe N1
- ✅ Resolução imediata de problemas mapeados
- ✅ Triagem e escalonamento inteligente
- ✅ Dashboard personalizado no Zabbix
- ✅ Relatórios mensais de disponibilidade

#### Ideal para:

- Ambientes de produção com criticidade média ou alta
- Empresas em crescimento
- Orçamentos controlados

### **PRO Tier**

*Para operações complexas que exigem expertise avançada e foco em inovação*

#### Características Principais:

- ✅ **Tudo do Essential, mais:**
- ✅ Suporte N2 especializado 24x7
- ✅ 8-15 horas mensais de análise de causa raiz
- ✅ Automação de correções recorrentes
- ✅ Propostas contínuas de otimização
- ✅ Setup inicial incluso
- ✅ Gestão proativa de conhecimento

#### Ideal para:

- Infraestruturas mission-critical
- Operações complexas
- Empresas com foco em inovação

---

## 📊 SLAs e Compromissos de Serviço

### Tempos de Resposta (Primeira Ação)

| Criticidade         | Descrição                      | SLA Essential | SLA PRO    |
| ------------------- | -------------------------------- | ------------- | ---------- |
| **🔴 HIGH**   | Indisponibilidade total          | 15 minutos    | 15 minutos |
| **🟡 MEDIUM** | Degradação severa              | 15 minutos    | 15 minutos |
| **🟢 LOW**    | Impacto operacional gerenciável | 15 minutos    | 15 minutos |

### Tempos de Atualização

| Criticidade         | Essential | PRO     |
| ------------------- | --------- | ------- |
| 🔴 HIGH             | N/A       | 1 hora  |
| **🟡 MEDIUM** | N/A       | 2 horas |
| **🟢 LOW**    | N/A       | 4 horas |

### Penalidades por Descumprimento

- SLA de até 95% de cumprimento mensal. A partir daí, desconto proporcional ao tempo violado, com o limite de até **5% na fatura mensal.**
- Só apuramos quando solicitado pelo cliente. Os créditos são aplicados automaticamente na próxima fatura

---

## 💰 Modelo de Precificação

### Como funciona?

Precificação baseada em **Unidades Monitoráveis (U.M.)** - qualquer recurso de infraestrutura que precisa ser monitorado.

### O que é uma U.M.?

- ✓ **Identificável**: Possui identidade única na AWS
- ✓ **Configurável**: Permite aplicação de configurações de monitoramento
- ✓ **Observável**: Gera métricas, logs e eventos
- ✓ **Mensurável**: Base para cobrança do serviço

### Tabela de Preços

| Limite U.M. | Essential Recorrente | Essential Setup | Pro Mensal | Pro Setup | Pro horas inclusas |
| ----------- | -------------------- | --------------- | ---------- | --------- | ------------------ |
| 20          | 2.500                | 4.000           | 5.400      | Incluso   | 5h                 |
| 50          | 4.500                | 8.000           | 7.800      | Incluso   | 8h                 |
| 100         | 6.000                | 14.000          | 10.800     | Incluso   | 10h                |
| 200         | 10.000               | 22.000          | 15.500     | Incluso   | 10h                |
| 400         | 16.000               | 30.000          | 22.000     | Incluso   | 10h                |
| 600         | 24.000               | 42.000          | 33.000     | Incluso   | 15h                |

*Valores sujeitos a customização para volumes maiores*

Horas excedentes: **R$518**

## Utilização das horas

* Somente incidentes gerados por alertas
* Não incluem requisição de serviço
* Não incluem incidentes que não alarmaram
* Não acumulam e não transferem

---

## 🔧 Como Funciona

### 1️⃣ **Setup Inicial**

#### Essential:

- Configuração de U.M. no Zabbix/CloudWatch
- Mapeamento do ambiente
- Definição de alertas por criticidade
- Documentação de procedimentos básicos

#### PRO:

- **Tudo do Essential, mais:**
- Integrações com ferramentas APM existentes (Datadog, New Relic)
- Automações iniciais
- Workshop de alinhamento

### 2️⃣ **Operação 24x7**

#### Fluxo de Monitoramento:

```
[Coleta de Métricas] → [Análise de Thresholds] → [Geração de Alertas]
         ↓                                              ↓
[Dashboard em Tempo Real]                    [Sistema ITSM Darede]
         ↓                                              ↓
[Visibilidade Cliente]                        [Ação da Equipe NOC]
```

#### Processo de Resposta a Incidentes:

1. **Detecção**: Alerta automático via ferramentas
2. **Triagem**: Classificação por criticidade (HIGH/MEDIUM/LOW)
3. **Ação Inicial**:
   - Essential: Resolução de problemas mapeados (N1)
   - PRO: Investigação avançada e causa raiz (N2)
4. **Resolução ou Escalonamento**: Ação direta ou acionamento de especialistas
5. **Documentação**: Registro completo no ITSM
6. **Melhoria**: Análise pós-incidente e otimização de processos

### 3️⃣ **Entregáveis Contínuos**

#### Mensalmente:

- 📊 Relatório de disponibilidade e performance
- 📈 Análise de tendências e padrões
- 🎯 Recomendações de otimização (PRO)
- 📋 Review de incidentes críticos
- 💡 Propostas de melhorias (PRO)
- 📚 Atualização de documentação

---

## 📦 Catálogo de Unidades Monitoráveis

*[Lista completa disponível no catálogo técnico](https://brunoprodutos.github.io/catalogo-monitoracao/ "Catálogo")*

---

## 🚀 Diferenciais Competitivos

### Por que escolher nossa Monitoração 24x7?

1. **🏅 Parceiro AWS Premier Tier**

   - Expertise certificada e reconhecida pela AWS
   - Acesso a suporte prioritário e recursos exclusivos
2. **⚡ Automação Inteligente**

   - Scripts customizados para recuperação automática
   - Redução drástica do tempo de resolução
3. **📊 Plataforma Unificada**

   - Dashboard único no Zabbix
   - Visibilidade completa em tempo real
   - Histórico completo de métricas
4. **👥 Equipe Especializada**

   - Profissionais certificados AWS
   - Treinamento contínuo
   - Conhecimento acumulado de múltiplos clientes
5. **💡 Melhoria Contínua**

   - Processo estruturado de lessons learned
   - Incorporação de melhores práticas
   - Evolução constante dos procedimentos

---

## 📈 Casos de Uso Típicos

### Cenário 1: E-commerce de Alto Volume

**Problema**: Picos de tráfego causando indisponibilidades
**Solução**: Monitoramento proativo com auto-scaling automatizado
**Resultado**: Zero downtime em Black Friday

### Cenário 2: Fintech com Compliance Rígido

**Problema**: Necessidade de rastreabilidade total
**Solução**: PRO Tier com análise de causa raiz documentada
**Resultado**: Aprovação em auditoria SOC2

### Cenário 3: Startup em Crescimento

**Problema**: Recursos limitados para equipe 24x7
**Solução**: Essential Tier com escalonamento inteligente
**Resultado**: Economia de 60% vs equipe própria

---

**© 2025 Darede - Todos os direitos reservados**
