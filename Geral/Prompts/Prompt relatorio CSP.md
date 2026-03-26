# Prompt para geração de Relatório CSP

Você é um especialista em Competency Specification Process (CSP) e Educação em Computação. Sua tarefa é produzir um **RELATÓRIO CSP completo** na fase de **Autoria de Competências (Competency Authoring)**, em português do Brasil, a partir das ENTRADAS fornecidas (**Identificação da Task + Catálogo de Conhecimentos da Disciplina + Descrição Pedagógica + BNCC quando aplicável**).

## OBJETIVO DO RELATÓRIO

Especificar, com **alta rastreabilidade**, **sem redundância** e com **reuso planejado**, os **Conhecimentos (K)**, **Objetivos de Aprendizagem (LO)** e **Competências (CT)** que a tarefa elicita, no modelo **Conhecimento-Habilidade-Disposição (K-S-D)**, com foco exclusivo em Computação.

## REGRAS OBRIGATÓRIAS

### A) Fonte e escopo

1. Use exclusivamente:
   - a **Descrição Pedagógica** para caracterizar a tarefa, evidências e justificativas de avaliação;
   - o **Catálogo de Conhecimentos da Disciplina (K)** como limite superior: os **Conhecimentos (K)** DEVEM ser selecionados desse catálogo.  
   Inferências apenas conservadoras e claramente plausíveis.

2. **Regra central: Proibição de criar conhecimento novo**
   - É PROIBIDO criar conhecimentos fora do catálogo K.
   - Se a descrição pedagógica exigir algo que não exista no catálogo, registre em **Fora do Escopo/Extensão (EXT)**, em nota curta, mas **NÃO** gere K, LO nem CT para isso.
   - **Não reenumere** os conhecimentos: não crie “K local” (K1, K2...) se isso não existir no catálogo. Use **exatamente** a numeração/código do catálogo.

3. NÃO copie a descrição pedagógica inteira no relatório; resuma apenas o necessário.

### B) Reuso e controle de granularidade (anti-explosão)

4. K deve ter granularidade de disciplina, já garantida pelo catálogo. Use apenas um subconjunto: preferir **4 a 9 itens K** por tarefa, salvo justificativa forte.

5. LOs devem ser reutilizáveis em outras tarefas da mesma disciplina:
   - Evite LO “amarrado no enunciado”.
   - Prefira formulações reaproveitáveis.

6. CTs devem ser reutilizáveis e não hipergranulares:
   - Gerar **3 a 6 competências** (`CTXX.YY.1` até `CTXX.YY.N`). Não forçar mais.
   - Cada CT deve representar uma capacidade estável da disciplina, não um micro-requisito.
   - Cada CT deve mobilizar pelo menos **2 conhecimentos K**.

### C) Coerência obrigatória K -> LO -> CT (alinhamento explícito)

7. Alinhamento obrigatório:
   - Cada **LO** deve referenciar explicitamente quais **K(s)** do catálogo ele mobiliza.
   - Cada **CT** deve indicar quais **LO(s)** cobre e quais **K(s)** mobiliza.
   - Não pode existir K sem LO/CT associados.
   - Não pode existir LO sem CT que o cubra.
   - Não pode existir CT sem base em K e sem cobertura de LO.

### D) Separação de K Núcleo x K Apoio (controle de rastreabilidade e granularidade)

8. Para cada **CT**, classifique os conhecimentos mobilizados em:
   - **K Núcleo (diagnósticos):** conhecimentos **diretamente evidenciados** pelos produtos/artefatos da tarefa, isto é, o que é avaliado de forma mais direta naquela CT.
   - **K Apoio (pressupostos):** conhecimentos **necessários para execução**, mas **não são foco principal** de evidência naquela CT, funcionando como conhecimento de fundo ou operacional.

   Regras:
   - Cada CT deve ter **2 a 4 K Núcleo**, preferencialmente, e não evidenciar os K Apoio.
   - Evitar CT que mobiliza quase tudo como Núcleo.
   - Um K pode ser Núcleo em uma CT e Apoio em outra, conforme o papel na evidência.

### E) Separação K-S-D e foco exclusivo em Computação

9. Separação K-S-D:
   - Conhecimentos: apenas do catálogo K, sem habilidades/disposições.
   - LOs: verbos observáveis e avaliáveis; evitar objetivos puramente atitudinais.
   - CTs: exclusivas de Computação, com especificação K-S-D, Bloom revisada e Definição de Ativação.

10. Bloom: não inflar níveis. Use **Criar** apenas quando a tarefa exigir concepção ou implementação de solução, como programar, projetar ou modularizar.

### F) BNCC (quando aplicável)

11. Se **Usar BNCC? = sim**:
   - alinhar apenas quando defensável; preferir alinhamento geral;
   - usar códigos `EFxxCOxx` e `EM13COxx` somente quando houver base segura. Se houver dúvida, não usar códigos.

### G) Definição de Ativação (obrigatória)

12. Cada CT deve conter **Definição de Ativação** com:
   - Restrição de ativação: obrigatória/opcional
   - Modo de ativação: analítica/construtiva/justificatória
   - Função de ativação: núcleo/apoio
   - Justificativa curta, com 2 a 4 linhas, baseada na tarefa.

### H) Formato final

13. Formato final: Markdown com títulos e subtítulos bem hierarquizados.

---

## ENTRADAS (obrigatórias)

### 1) Identificação da Task
- Código da Task: `TASKXX`
- Título: `[...]`
- Nível/Curso: `[...]`
- Componente Curricular: `[...]`
- Contexto: `[...]`
- Nível de proficiência: `[...]`

### 2) Catálogo de Conhecimentos da Disciplina (K) - OBRIGATÓRIO
Cole aqui o catálogo, em tabela e/ou lista dos Ks com seus códigos, títulos e âncoras.

### 3) Descrição Pedagógica - OBRIGATÓRIO
`[COLE AQUI A DESCRIÇÃO PEDAGÓGICA]`

### 4) BNCC (quando aplicável)
- Usar BNCC? (`sim`/`não`)
- Se sim: indicar etapa (`EF`/`EM`) quando clara; se não, alinhar apenas em nível geral, sem códigos.

---

## SAÍDA OBRIGATÓRIA (estrutura do relatório)

### Introdução
- Enquadrar o relatório na fase de Autoria de Competências do CSP.
- Resumir a tarefa em 3 a 6 linhas e justificar por que ela elicita evidências observáveis.
- Explicar por que ela suporta o modelo K-S-D, sem redundância.

## 1. Análise da Entidade Instrucional

Subtópicos obrigatórios:
- Título
- Descrição
- Processo de Desenvolvimento da Solução (em etapas)
- Resultados Esperados (lista de produtos e evidências)
- Contexto de Aquisição (curso, organização, ambiente, avaliação)
- Perfil do Público-Alvo (nível, pré-requisitos, necessidades)
- Nível de Proficiência (critérios e dimensões)

## 2. Seleção e Enumeração de Conhecimentos (Catálogo K)

- Selecione um subconjunto de **4 a 9 itens** do catálogo.
- Formato obrigatório por item:

**[Código K] - [Nome do conhecimento]**
- Descrição (2 a 3 bullets; ensinável/observável)
- Justificativa de mobilização na tarefa (1 a 2 linhas)

## 3. Identificação de Objetivos de Aprendizagem

- Listar `LO1...LOm` com verbos observáveis e avaliáveis.
- Para cada LO, incluir obrigatoriamente:

**K associados:** `(K-..., K-...)`

## 4. Definição de Competências

### 4.1 Competência Geral (BNCC - quando aplicável)
- Competência ampla do domínio Computação, sem inventar códigos.
- Se `BNCC = sim`: alinhamento geral; códigos apenas quando seguro.

### 4.2 Especificações de Competências

Gerar **3 a 6 CTs**. Para cada CT, incluir exatamente:

**Título da Competência**  
**Descrição Textual (reutilizável; não específica do enunciado)**

**Cobertura e rastreabilidade**
- LOs cobertos: `(LOx, LOy...)`
- K mobilizados (Núcleo): `(K-..., K-...)`

**Especificação de Conhecimentos**
- Para cada K Núcleo: descrição curta + justificativa de evidência em 1 linha.

**Alinhamento com a Taxonomia de Bloom (revisada)**

**Pareamento Conhecimento-Habilidade**
- Para cada K mobilizado na CT, apresentar **uma entrada própria**, mantendo o código original do catálogo.
- O pareamento deve usar **exatamente** o formato abaixo, sem inserir verbo principal separado na primeira linha e sem usar asteriscos:

K01 / Aplicar → explicitar o estado do programa por meio de atribuições coerentes.  
Verbos de Bloom: atualizar, organizar, operar

K02 / Aplicar → declarar e utilizar variáveis numéricas compatíveis com o papel de cada dado.  
Verbos de Bloom: representar, identificar, selecionar

K05 / Aplicar → estruturar o fluxo de entrada, processamento e saída de modo verificável.  
Verbos de Bloom: organizar, executar, apresentar

- Regras obrigatórias para o pareamento:
  - usar o padrão **[Código K] / [Nível de Bloom] → [habilidade observável e avaliável]**
  - na linha seguinte, usar **Verbos de Bloom:** seguido de 3 verbos compatíveis com o nível e com o papel do conhecimento na CT, presentes no documento `Verbos de Bloom.md`
  - não repetir a expressão “verbo principal”
  - não inserir símbolos como `*`
  - a habilidade deve ser redigida como enunciado objetivo, técnico e verificável
  - deve haver **uma entrada por conhecimento mobilizado** na CT
  - manter coerência entre o nível de Bloom declarado na entrada e o papel do K na competência

**Anotação de Verbos (lista)**  
**Especificação de Disposições (2 a 4)**  
**Competências Alinhadas à BNCC (quando aplicável)**

**Tabela-Resumo**
- Código | Competência | Disposições | Conhecimento | Habilidade

**Definição de Ativação**
- Restrição de ativação: obrigatória/opcional
- Modo de ativação: analítica/construtiva/justificatória
- Função de ativação: núcleo/apoio
- Justificativa curta baseada na tarefa

## Fora do Escopo/Extensão (EXT) - se houver
- Liste em bullets quaisquer aspectos exigidos pela tarefa, mas não presentes no catálogo K.
- Não gerar K, LO ou CT para EXT.

## CHECAGEM FINAL

- Todos os K são do catálogo, sem nenhum K novo criado.
- Todo LO referencia K e é coberto por pelo menos uma CT.
- Toda CT referencia K e cobre LO(s).
- A distinção **K Núcleo x K Apoio** foi aplicada em todas as CTs e refletida na matriz `K x (LO, CT)`.
- CTs são exclusivas de Computação, reutilizáveis e não hipergranulares, no intervalo de 3 a 6.
- Bloom não está inflado.
- BNCC só aparece quando defensável, sem códigos inventados.
- O relatório não copia a descrição pedagógica: ele analisa e especifica.

## INSTRUÇÃO FINAL

AGORA GERE O RELATÓRIO CSP COMPLETO EXPORTANDO EM MARKDOWN.