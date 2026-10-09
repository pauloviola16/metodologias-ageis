# Super Resumo para Prova — Metodologias Ágeis

> Revisão focada em Scrum, XP, Kanban, Manifesto Ágil e conceitos complementares.

## 1. Scrum — Prioridade Máxima

**Scrum:** framework ágil baseado em entregas incrementais, colaboração e ciclos curtos chamados Sprints.

### Três pilares

- **Transparência:** todos conhecem o andamento do trabalho.
- **Inspeção:** verificar resultados e identificar problemas.
- **Adaptação:** ajustar o processo conforme necessário.

### Cinco valores

**Compromisso, Foco, Abertura, Respeito e Coragem.**

> **Pegadinha:** Empatia não é um dos cinco valores oficiais do Scrum.

### Três responsabilidades do Scrum Team

| Papel | Função |
|---|---|
| **Product Owner (PO)** | Maximiza o valor do produto e ordena o Product Backlog |
| **Scrum Master** | Facilita a aplicação do Scrum e ajuda a eliminar impedimentos |
| **Developers** | Planejam e desenvolvem os incrementos do produto |

**Atenção:** Scrum Master não é chefe da equipe. O time é autogerenciável e multifuncional.

### Cinco eventos do Scrum

| Evento | Objetivo |
|---|---|
| **Sprint** | Ciclo de trabalho de até 1 mês |
| **Sprint Planning** | Planejar o que será realizado e por quê |
| **Daily Scrum** | Reunião diária de 15 minutos para inspecionar o progresso e adaptar o plano |
| **Sprint Review** | Avaliar o resultado com interessados e obter feedback |
| **Sprint Retrospective** | Identificar melhorias no trabalho da equipe |

> **Pegadinha:** Review avalia o produto e próximos passos; Retrospective avalia como a equipe trabalhou.

### Artefatos e compromissos

| Artefato | Compromisso |
|---|---|
| **Product Backlog:** lista ordenada do que o produto precisa | Product Goal |
| **Sprint Backlog:** plano de trabalho da Sprint | Sprint Goal |
| **Increment:** resultado utilizável produzido | Definition of Done |

**Definition of Done (DoD):** critérios que precisam ser cumpridos para considerar o trabalho concluído.

---

## 2. XP — Extreme Programming

**XP:** metodologia ágil focada em qualidade do código, boas práticas de programação, colaboração e feedback rápido.

### Cinco valores do XP

**Comunicação, Simplicidade, Feedback, Coragem e Respeito.**

### Principais práticas

- **Pair Programming:** dois desenvolvedores trabalham juntos no código.
- **TDD:** primeiro escreve o teste, depois implementa o código.
- **Refatoração:** melhora a estrutura interna sem alterar o comportamento esperado.
- **Integração contínua:** integrar e testar alterações frequentemente.
- **Pequenas entregas:** entregar funcionalidades em incrementos pequenos.
- **Cliente presente:** participação frequente do cliente para esclarecer requisitos e validar entregas.
- **Ritmo sustentável:** evitar sobrecarga constante.

### Papéis do XP

Nos exercícios estudados, também apareceram papéis como:

- Cliente
- Desenvolvedor
- Coach
- Testador
- Tracker
- Cleaner
- Gerente

> **Atenção:** XP possui práticas e papéis diferentes dos três do Scrum.

---

## 3. Kanban

**Kanban:** método visual para gerenciar e melhorar o fluxo de trabalho, identificando gargalos e limitando tarefas simultâneas.

### Exemplo de quadro Kanban

| A Fazer | Fazendo | Concluído |
|---|---|---|
| Tarefa A | Tarefa C | Tarefa D |
| Tarefa B | | Tarefa E |

### Conceitos essenciais

- **WIP (Work in Progress):** quantidade de tarefas em andamento. Limitar WIP evita sobrecarga.
- **Fluxo contínuo:** novas tarefas podem ser puxadas conforme existe capacidade.
- **Lead Time:** tempo total entre a entrada de uma demanda no fluxo e sua entrega.
- **Cycle Time:** tempo entre o início efetivo do trabalho e sua conclusão.
- **Gargalo:** etapa que atrasa o fluxo.

> **Pegadinha:** Kanban não exige Sprints nem papéis específicos como Product Owner e Scrum Master. Pode ser aplicado fora do desenvolvimento de software.

---

## 4. Manifesto Ágil

### Os quatro valores

1. **Pessoas e interações** acima de processos e ferramentas.
2. **Software funcionando** acima de documentação extensa.
3. **Colaboração com o cliente** acima de negociação contratual.
4. **Responder a mudanças** acima de seguir rigidamente um plano.

Isso não significa abandonar processos, documentação, contratos ou planejamento. Significa valorizar mais os elementos da esquerda.

### Principais pontos dos 12 princípios

- Satisfação do cliente.
- Entregas frequentes.
- Aceitar mudanças.
- Colaboração entre cliente e equipe.
- Simplicidade.
- Qualidade técnica.
- Ritmo sustentável.
- Melhoria contínua.

---

## 5. Comparação — Scrum, XP e Kanban

| Característica | Scrum | XP | Kanban |
|---|---|---|---|
| **Foco** | Gestão e entregas iterativas | Qualidade técnica | Fluxo de trabalho |
| **Organização** | Sprints | Iterações e práticas técnicas | Fluxo contínuo |
| **Papéis definidos** | Sim | Papéis e responsabilidades tradicionais de XP | Não obrigatórios |
| **Destaque** | PO, Scrum Master e eventos | TDD, programação em pares e refatoração | Quadro, WIP e gargalos |

### Para memorizar em 10 segundos

- **Scrum:** organizar o trabalho em Sprints.
- **XP:** desenvolver software com qualidade.
- **Kanban:** visualizar e controlar o fluxo.

---

## 6. Outros Conceitos que Podem Aparecer

| Conceito | O que lembrar |
|---|---|
| **Lean** | Eliminar desperdícios e maximizar valor |
| **Planning Poker** | Estimativa colaborativa de esforço |
| **Story Points** | Medida relativa de esforço, complexidade e incerteza |
| **User Story** | Necessidade descrita pela perspectiva do usuário |
| **MVP** | Versão mínima para validar uma ideia |
| **Burndown Chart** | Gráfico do trabalho restante ao longo do tempo |
| **PMBOK 7** | Guia de gerenciamento de projetos baseado em princípios, desempenho, valor e adaptação |
| **Modelo Cascata** | Etapas mais sequenciais, com menor flexibilidade para mudanças |
| **Empirismo** | Decidir com base em observação, experiência e evidências |

### Atenção às versões do Scrum

Materiais antigos podem mencionar equipes Scrum de **3 a 9 desenvolvedores**.

No Scrum Guide 2020, a referência passou a ser um Scrum Team com tipicamente **10 pessoas ou menos**, incluindo Product Owner e Scrum Master.


