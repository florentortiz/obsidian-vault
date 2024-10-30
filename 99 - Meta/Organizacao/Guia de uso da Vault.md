---
aliases:
  - Vault Guidelines
  - Diretivas da Vault
tags:
  - contexto/estudos
  - tipo/estudo
  - tema/organização
  - tema/produtividade
  - estado/concluido
data: 2024-10-20
data_atualizacao: 2024-10-29
---

## **Guia Prático de Uso**

### **1. Criando Novas Notas**

#### **Processo de Decisão**
1. Identifique o tipo principal da nota (tarefa, estudo, reflexão, etc.)
2. Escolha a pasta principal apropriada:
   - Conhecimento pessoal → 02 - Conhecimento
   - Reflexões/diário → 01 - Pessoal
   - Material fonte → 04 - Referências
   - Projetos ativos → 03 - Projetos

#### **Nomenclatura**
- Use nomes descritivos e concisos
- Evite caracteres especiais
- Exemplos:
  - `Introdução a Algoritmos`
  - `2024-01-01 Reflexão Diária`
  - `Projeto Game Engine`

### **2. Usando Tags Efetivamente**
Caso queira exemplos mais detalhados do uso de tags, verificar o [[Como classificar notas com tags|Sistema de Organização de tags]]

#### **Estrutura Recomendada de Tags**
Sempre incluir no mínimo:
1. Uma tag de tipo (`#tipo/...`)
2. Uma tag de contexto (`#contexto/...`)
3. Uma tag de tema (`#tema/...`)
4. Uma tag de estado/prioridade quando aplicável

Exemplo:
```markdown
tags:
  - tipo/estudo
  - contexto/academico
  - tema/algoritmos
  - estado/em-progresso
  - prioridade/alta
```

### **3. Criando Conexões**

#### **Links Efetivos**
- Use links bidirecionais (`[[]]`) para conectar conceitos relacionados
- Crie MOCs (Maps of Content) para temas principais
- Exemplo de MOC:
```markdown
# MOC - Algoritmos
## Fundamentos
- [[Complexidade de Algoritmos]]
- [[Estruturas de Dados Básicas]]

## Algoritmos Específicos
- [[Algoritmos de Ordenação]]
- [[Algoritmos de Busca]]
```

### **4. Fluxo de Trabalho Diário**

#### **Rotina Recomendada**
1. **Início do Dia**
   - Revisar notas com `#revisao/pendente`
   - Atualizar status de projetos
   - Criar nota diária se necessário

2. **Durante o Dia**
   - Usar notas fleeting para captura rápida
   - Processar notas fleeting regularmente
   - Atualizar status e tags conforme necessário

3. **Fim do Dia**
   - Revisar notas criadas
   - Verificar conexões necessárias
   - Planejar revisões futuras

### **5. Manutenção do Sistema**

#### **Revisão Semanal**
1. Processar todas as notas fleeting
2. Atualizar status de projetos
3. Verificar tags pendentes
4. Planejar revisões da próxima semana

#### **Revisão Mensal**
1. Arquivar projetos concluídos
2. Atualizar MOCs principais
3. Verificar consistência de tags
4. Identificar áreas para expansão/melhoria

### **6. Solução de Problemas Comuns**

#### **Quando Não Souber Onde Colocar uma Nota**
1. Considere o uso principal da nota
2. Use tags para múltiplas categorias
3. Crie links para contextos relacionados
4. Se ainda estiver em dúvida, use a pasta mais genérica e tags específicas

#### **Quando uma Nota Crescer Demais**
1. Divida em notas menores e mais específicas
2. Crie uma nota MOC para conectá-las
3. Mantenha apenas o resumo na nota original
4. Use links para as notas detalhadas

### **7. Dicas de Produtividade**

#### **Atalhos Recomendados**
- Configurar template hotkeys
- Criar atalhos para tags comuns
- Usar quick switcher para navegação

#### **Plugins Essenciais**
- Calendar para visão temporal
- Dataview para queries
- Kanban para projetos
- Graph View para visualizar conexões

### **8. Exemplos de Uso**

#### **Nota de Estudo**
```markdown
---
aliases: [Algoritmos de Ordenação]
tags:
  - tipo/estudo
  - contexto/academico
  - tema/algoritmos
  - estado/em-progresso
data: 2024-01-01
---

# Algoritmos de Ordenação

## Objetivo
Compreender principais algoritmos de ordenação e suas complexidades.

## Conteúdo
1. Bubble Sort
2. Quick Sort
3. Merge Sort

## Conexões
- [[Complexidade de Algoritmos]]
- [[Estruturas de Dados]]

## Notas
[Conteúdo...]
```

#### **Nota de Projeto**
```markdown
---
aliases: [Projeto: Game Engine]
tags:
  - tipo/projeto
  - contexto/trabalho
  - tema/dev
  - estado/planejamento
data: 2024-01-01
---

# Projeto: Game Engine

## Objetivo
Criar engine básica para jogos 2D.

## Etapas
1. [ ] Setup básico
2. [ ] Sistema de renderização
3. [ ] Sistema de física

## Recursos Necessários
- C++
- OpenGL

## Conexões
- [[Game Development]]
- [[OpenGL Basics]]
```

## **Conclusão**  

Este sistema é projetado para crescer organicamente com seu uso. A chave é manter a consistência na aplicação dos princípios básicos enquanto permite flexibilidade suficiente para adaptação às necessidades individuais. Comece com as estruturas básicas e expanda conforme necessário, sempre mantendo o foco na simplicidade e usabilidade.