# Clínica Vida+ — Sistema Integrado de Gestão (Estudo de Caso de TGS)

Estudo de caso acadêmico de **Teoria Geral dos Sistemas (TGS)** do curso de Sistemas de Informação (UNIP, Campinas, 2026). O grupo analisou uma clínica popular com três unidades que cresceu sem gestão integrada e propôs um sistema de informação único para organizar o atendimento.

> **Projeto acadêmico.** O caso é fictício e os valores e metas citados são hipotéticos.

## O problema

Depois da expansão para três unidades, a clínica passou a sofrer com:

- agendamentos duplicados, porque cada unidade controla a agenda em planilhas independentes;
- informações divergentes entre as unidades;
- filas, atrasos e muitas reclamações;
- faltas de pacientes, sem confirmação prévia das consultas;
- dificuldade de acompanhar indicadores de desempenho.

![Fluxo anterior, com os pontos de ruído e entropia](img/fluxo-anterior.png)

## A solução proposta

- **Sistema de informação integrado**, com banco de dados centralizado e compartilhado em tempo real entre as três unidades.
- **Cadastro único** e prontuário acessível em qualquer unidade.
- **Agenda unificada**: o horário reservado em uma unidade é bloqueado nas outras.
- **Confirmação ativa em três tempos** (na marcação, 3 dias antes e na manhã da consulta), com liberação da vaga para encaixe em caso de cancelamento.
- **Pré-cadastro digital** pelo celular para agilizar a recepção.
- **Totem de autoatendimento** para pagamento, avaliação e reagendamento.
- **Painel de indicadores**: tempo de espera, taxa de faltas, ocupação dos médicos, satisfação, encaixes e duplicidades de agenda.

![Fluxograma de atendimento reestruturado](img/fluxograma-reestruturado.png)

## Conceitos aplicados

| Área | Aplicação no caso |
| --- | --- |
| Sistema aberto | Entradas, processamento e saídas da clínica, e sua relação com pacientes, planos de saúde e fornecedores |
| Feedback e homeostase | Totem de avaliação, alertas de espera e relatórios de faltas para autorregulação |
| Entropia e negentropia | Planilhas divergentes e duplicidades (entropia) contra o cadastro único e os lembretes (negentropia) |
| Sinergia, resiliência e morfogênese | Integração entre unidades, plano de contingência e mudança de estrutura isolada para rede integrada |
| Modelo sociotécnico | Subsistema técnico (hardware, software, banco de dados) e social (médicos, recepção, gestores, pacientes) |
| Processo decisório | Decisões operacionais, táticas e estratégicas e os tipos de problema de cada nível |
| Pesquisa Operacional | Teoria das filas e modelagem do fluxo do paciente como grafo orientado (V1 a V7) |

![Fluxo do paciente modelado como grafo orientado](img/grafo-fluxo-paciente.png)

## Riscos e mitigação

- **Migração das planilhas:** limpeza prévia dos dados, importação assistida e backup.
- **Adaptação da equipe:** treinamento prático, manuais simples e suporte na implantação.
- **Queda de internet:** módulo local de contingência com sincronização posterior e no-breaks.

## Conteúdo do repositório

- [`docs/estudo-de-caso-clinica-vida-mais.pdf`](docs/estudo-de-caso-clinica-vida-mais.pdf): relatório completo do grupo.
- [`img/`](img): fluxos e grafo usados neste README.

## Equipe

Carlos, Enzo, Kauan, Natália, Rafael e Vitória.
