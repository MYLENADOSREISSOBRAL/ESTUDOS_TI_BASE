<a id="topo"></a>

**CADERNO DE ESTUDO · IFPA**

# Raciocínio Lógico-Matemático (RLM)

Os itens do edital de RLM, explicados em texto corrido, com fórmulas, exemplos resolvidos e as pegadinhas mais cobradas. Cada tópico termina com uma **revisão rápida** no estilo de prova: clique na afirmação para ver a resposta.

**Legenda:** ⚠️ **Pegadinha de prova** · 💡 **Para memorizar** · 📘 **Exemplo**

> **Como localizar um assunto:** use o botão **[🔎 Localizar assunto](#localizar-assunto)** (ele aparece no início e no fim de cada tópico), o **[índice remissivo A–Z](#indice-remissivo)** ou o atalho **Ctrl + F** do seu leitor de Markdown.

---

<a id="localizar-assunto"></a>

## 🔎 Localizar assunto

Marque a caixa quando terminar o tópico (funciona no VS Code, Obsidian e GitHub).

- [ ] **[01 · Lógica proposicional: proposições e conectivos](#t01)**
  - [O que é (e o que não é) proposição](#t01-proposicoes) · [Conectivos](#t01-conectivos) · [Tabela-verdade](#t01-tabela) · [Tautologia, contradição e contingência](#t01-tautologia) · [Condição necessária e suficiente](#t01-necessaria)
- [ ] **[02 · Equivalências lógicas e negações](#t02)**
  - [Equivalências fundamentais](#t02-equivalencias) · [Leis de De Morgan](#t02-demorgan) · [Negação de cada conectivo](#t02-negacoes) · [Linguagem natural](#t02-linguagem)
- [ ] **[03 · Quantificadores, predicados e argumentos](#t03)**
  - [Sentenças abertas e predicados](#t03-predicados) · [Quantificadores e suas negações](#t03-quantificadores) · [Diagramas lógicos](#t03-diagramas) · [Argumentos válidos e falácias](#t03-argumentos)
- [ ] **[04 · Conjuntos, operações e diagramas](#t04)**
  - [Noções e representação](#t04-nocoes) · [Operações](#t04-operacoes) · [Contagem com diagramas de Venn](#t04-venn) · [Conjuntos numéricos](#t04-numericos)
- [ ] **[05 · Números inteiros, racionais e reais](#t05)**
  - [Operações e ordem](#t05-operacoes) · [Divisibilidade, MMC e MDC](#t05-divisibilidade) · [Frações e dízimas](#t05-fracoes) · [Potências e raízes](#t05-potencias)
- [ ] **[06 · Porcentagem e juros](#t06)**
  - [Porcentagem e fator multiplicativo](#t06-porcentagem) · [Aumentos e descontos sucessivos](#t06-sucessivos) · [Juros simples](#t06-simples) · [Juros compostos](#t06-compostos) · [Taxas](#t06-taxas)
- [ ] **[07 · Proporcionalidade direta e inversa](#t07)**
  - [Razão e proporção](#t07-razao) · [Grandezas direta e inversamente proporcionais](#t07-grandezas) · [Regra de três simples e composta](#t07-regra) · [Divisão proporcional](#t07-divisao)
- [ ] **[08 · Medidas: comprimento, área, volume, massa e tempo](#t08)**
  - [Sistema métrico decimal](#t08-sistema) · [Área e volume](#t08-area-volume) · [Capacidade e massa](#t08-capacidade) · [Tempo](#t08-tempo) · [Velocidade e escala](#t08-velocidade)
- [ ] **[09 · Estrutura lógica de relações (associação e verdades/mentiras)](#t09)**
  - [Lógica de associação](#t09-associacao) · [Ordenação e posições](#t09-ordenacao) · [Verdades e mentiras](#t09-verdades) · [Avaliar as condições](#t09-condicoes)
- [ ] **[10 · Funções intelectuais: raciocínio verbal, sequencial, espacial e temporal](#t10)**
  - [Raciocínio verbal](#t10-verbal) · [Raciocínio sequencial](#t10-sequencial) · [Orientação espacial](#t10-espacial) · [Orientação temporal](#t10-temporal) · [Formação de conceitos e discriminação](#t10-conceitos)
- [ ] **[11 · Gráficos e tabelas](#t11)**
  - [Tipos de gráfico](#t11-tipos) · [Medidas de tendência central](#t11-medidas) · [Leitura crítica](#t11-leitura)
- [ ] **[12 · Problemas aritméticos, geométricos e matriciais](#t12)**
  - [Problemas aritméticos (equações)](#t12-aritmeticos) · [Problemas geométricos (contagem de figuras)](#t12-geometricos) · [Matrizes](#t12-matrizes) · [Quadros e matrizes de símbolos](#t12-quadros)
- [ ] **[13 · Contagem e probabilidade](#t13)**
  - [Princípio fundamental da contagem](#t13-pfc) · [Permutações, arranjos e combinações](#t13-agrupamentos) · [Casa dos pombos](#t13-pombos) · [Probabilidade](#t13-probabilidade) · [Probabilidade condicional e eventos independentes](#t13-condicional)
- [ ] **[14 · Geometria básica](#t14)**
  - [Ângulos](#t14-angulos) · [Triângulos](#t14-triangulos) · [Polígonos](#t14-poligonos) · [Perímetro e área](#t14-areas) · [Semelhança e Tales](#t14-semelhanca)
- [ ] **[15 · Plano cartesiano](#t15)**
  - [Sistema de coordenadas](#t15-coordenadas) · [Distância e ponto médio](#t15-distancia) · [Retas, alinhamento e área](#t15-retas)
- [ ] **[16 · Problemas de lógica e raciocínio](#t16)**
  - [Roteiro de resolução](#t16-roteiro) · [Estratégias clássicas](#t16-estrategias) · [Pior caso e garantias](#t16-pior-caso)
- [ ] **[Formulário final](#formulario)** · **[Índice remissivo A–Z](#indice-remissivo)**

---

<a id="t01"></a>

## `01` Lógica proposicional: proposições e conectivos

> **Edital:** Lógica: proposições, conectivos (…).

<a id="t01-proposicoes"></a>

### O que é (e o que não é) proposição

**Proposição** é toda sentença declarativa à qual se pode atribuir **um, e somente um**, valor lógico: **verdadeiro (V)** ou **falso (F)**. Ela obedece a três princípios clássicos:

- **Identidade:** uma proposição verdadeira é verdadeira; uma falsa é falsa.
- **Não contradição:** nenhuma proposição é V e F ao mesmo tempo.
- **Terceiro excluído:** toda proposição é V ou F; não existe terceira opção.

**Não são proposições:**

| Tipo de sentença | Exemplo | Por quê |
|---|---|---|
| Interrogativa | "Que horas são?" | Não afirma nada |
| Exclamativa | "Que dia lindo!" | Expressa emoção |
| Imperativa (ordem) | "Estude lógica." | Não é V nem F |
| Sentença aberta | "x + 2 = 5"; "Ele é professor." | Depende de quem é x / "ele" |
| Paradoxo | "Esta frase é falsa." | Se for V é F, se for F é V |
| Frase sem verbo | "Bom dia." | Não declara |

> ⚠️ **Pegadinha:** "Belém é a capital do Amazonas" **é** proposição (falsa). Ser falsa não a desqualifica. Já "x é maior que 3" **não é**, porque o valor depende de x. E "Ele foi aprovado" também é sentença aberta: "ele" é variável.

**Proposição simples** tem uma única ideia (p: "Ana estuda"). **Proposição composta** junta duas ou mais simples por **conectivos** (p ∧ q: "Ana estuda e Bruno trabalha").

<a id="t01-conectivos"></a>

### Conectivos

| Conectivo | Símbolo | Leitura | É **verdadeiro** quando… | É **falso** quando… |
|---|---|---|---|---|
| Negação | ~p (ou ¬p) | não p | p é F | p é V |
| Conjunção | p ∧ q | p **e** q | **ambas** V | pelo menos uma F |
| Disjunção inclusiva | p ∨ q | p **ou** q | pelo menos uma V | **ambas** F |
| Disjunção exclusiva | p ⊻ q | **ou** p **ou** q | valores **diferentes** | valores iguais |
| Condicional | p → q | **se** p, **então** q | todos os outros casos | **V → F** (só esse) |
| Bicondicional | p ↔ q | p **se e somente se** q | valores **iguais** | valores diferentes |

No condicional p → q, **p** é o **antecedente** e **q** o **consequente**. Outras formas de escrever p → q na língua portuguesa: "Quando p, q", "Sempre que p, q", "p implica q", "q, se p", "Como p, q", "p somente se q", "Todo p é q".

> 💡 **Para memorizar:** o condicional é a **"Vera Fischer"**: só é **F** quando é **V → F**. Antecedente falso torna o condicional automaticamente verdadeiro ("Se 2 + 2 = 5, então eu sou o rei" é V).

> ⚠️ **Pegadinha:** "p, mas q" e "p, embora q" são **conjunções** (∧). E "**p somente se q**" é p → q, e não q → p.

<a id="t01-tabela"></a>

### Tabela-verdade

Com **n** proposições simples, a tabela-verdade tem **2ⁿ linhas**. Com 2 proposições, 4 linhas; com 3, 8; com 4, 16.

| p | q | ~p | p ∧ q | p ∨ q | p ⊻ q | p → q | p ↔ q |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| V | V | F | V | V | F | V | V |
| V | F | F | F | V | V | **F** | F |
| F | V | V | F | V | V | V | F |
| F | F | V | F | F | F | V | V |

**Ordem de precedência** (quando não há parênteses): **~** → **∧** → **∨** → **→** → **↔**.

> 📘 **Exemplo:** se p é V, q é F e r é V, qual o valor de (p ∧ q) → ~r?
> p ∧ q = V ∧ F = **F**. ~r = **F**. Logo F → F = **V**.

<a id="t01-tautologia"></a>

### Tautologia, contradição e contingência

- **Tautologia:** a última coluna da tabela é **sempre V**. Ex.: p ∨ ~p; p → p; (p ∧ q) → p.
- **Contradição:** **sempre F**. Ex.: p ∧ ~p; p ↔ ~p.
- **Contingência:** tem V e F. Ex.: p → q.

> 💡 **Para memorizar:** a negação de uma tautologia é uma contradição, e vice-versa.

<a id="t01-necessaria"></a>

### Condição necessária e condição suficiente

Em **p → q**:

- **p é condição suficiente para q** (basta p acontecer para q acontecer).
- **q é condição necessária para p** (sem q, não há p).

Em **p ↔ q**, p é condição **necessária e suficiente** para q.

> 📘 **Exemplo:** "Se nasceu em Belém, então é paraense." Nascer em Belém é **suficiente** para ser paraense; ser paraense é **necessário** para ter nascido em Belém. Mas ser paraense **não é suficiente** para ter nascido em Belém.

### Revisão rápida

<details><summary>Certo ou errado: "Feche a porta!" é uma proposição falsa.</summary>

Errado. Sentença imperativa não é proposição; não tem valor lógico.
</details>

<details><summary>Certo ou errado: uma proposição composta por 5 proposições simples tem tabela-verdade com 32 linhas.</summary>

Certo. 2⁵ = 32.
</details>

<details><summary>Certo ou errado: o condicional p → q é falso quando p é falso e q é verdadeiro.</summary>

Errado. Só é falso no caso V → F. Com antecedente falso, o condicional é sempre verdadeiro.
</details>

<details><summary>Certo ou errado: a disjunção exclusiva é verdadeira quando as duas proposições são verdadeiras.</summary>

Errado. "Ou p ou q" exige valores diferentes; com ambas V, é falsa. Quem é V com ambas V é a disjunção inclusiva.
</details>

<details><summary>Certo ou errado: "João é alto, mas não é forte" é uma conjunção.</summary>

Certo. "Mas" tem valor lógico de "e": p ∧ ~q.
</details>

<details><summary>Certo ou errado: p ∧ ~p é uma tautologia.</summary>

Errado. É uma contradição (sempre F). Tautologia é p ∨ ~p.
</details>

<details><summary>Em "Se chover, a rua molha", o que é condição necessária?</summary>

"A rua molhar" (o consequente) é condição necessária; "chover" (o antecedente) é condição suficiente.
</details>

<p align="right"><a href="#localizar-assunto">🔎 Localizar assunto</a> · <a href="#topo">⬆ Topo</a></p>

---

<a id="t02"></a>

## `02` Equivalências lógicas e negações

> **Edital:** (…) equivalências lógicas (…).

Duas proposições são **logicamente equivalentes** (≡) quando têm **a mesma tabela-verdade**. É o tema mais cobrado de lógica: a banca dá uma frase e pede a equivalente ou a negação.

<a id="t02-equivalencias"></a>

### Equivalências fundamentais

| Nome | Equivalência |
|---|---|
| Dupla negação | ~(~p) ≡ p |
| Contrapositiva | **p → q ≡ ~q → ~p** |
| Condicional em disjunção ("NeyMar") | **p → q ≡ ~p ∨ q** |
| Bicondicional | p ↔ q ≡ (p → q) ∧ (q → p) |
| Comutativa | p ∧ q ≡ q ∧ p; p ∨ q ≡ q ∨ p |
| Distributiva | p ∧ (q ∨ r) ≡ (p ∧ q) ∨ (p ∧ r) |
| Absorção | p ∨ (p ∧ q) ≡ p; p ∧ (p ∨ q) ≡ p |
| Disjunção exclusiva | p ⊻ q ≡ ~(p ↔ q) ≡ p ↔ ~q |

> 💡 **Para memorizar:**
> - **Contrapositiva:** **inverte e nega** as duas. "Se estudo, passo" ≡ "Se não passo, não estudo".
> - **NeyMar:** **Ne**ga a primeira, **Ma**ntém a segunda e troca → por **ou**. "Se estudo, passo" ≡ "Não estudo ou passo".

> ⚠️ **Pegadinha:** **q → p** (recíproca) e **~p → ~q** (inversa) **não** são equivalentes a p → q. "Se estudo, passo" **não** equivale a "Se passo, estudo" nem a "Se não estudo, não passo".

<a id="t02-demorgan"></a>

### Leis de De Morgan

- **~(p ∧ q) ≡ ~p ∨ ~q** — nega as duas e troca **e** por **ou**.
- **~(p ∨ q) ≡ ~p ∧ ~q** — nega as duas e troca **ou** por **e**.

> 📘 **Exemplo:** negação de "Ana é médica e Bruno é engenheiro" → "Ana **não** é médica **ou** Bruno **não** é engenheiro".

<a id="t02-negacoes"></a>

### Negação de cada conectivo

| Proposição | Negação | Regra prática |
|---|---|---|
| p ∧ q | ~p ∨ ~q | De Morgan |
| p ∨ q | ~p ∧ ~q | De Morgan |
| **p → q** | **p ∧ ~q** | **"MaNe": Mantém a 1ª, e, Nega a 2ª** |
| p ↔ q | p ⊻ q (ou: p ↔ ~q) | Valores passam a ser diferentes |
| p ⊻ q | p ↔ q | Valores passam a ser iguais |

> ⚠️ **Pegadinha:** a negação de um condicional **não é outro condicional**. Negar "Se chove, levo guarda-chuva" é "**Chove e não levo** guarda-chuva", e não "Se não chove, não levo guarda-chuva".

> 📘 **Exemplo:** negação de "Se o servidor faltar, então será advertido ou perderá o ponto".
> Estrutura: p → (q ∨ r). Negação: p ∧ ~(q ∨ r) ≡ p ∧ (~q ∧ ~r).
> Resposta: "O servidor faltou **e** não será advertido **e** não perderá o ponto."

<a id="t02-linguagem"></a>

### Linguagem natural: armadilhas de tradução

| Expressão | Tradução lógica |
|---|---|
| "Nem p nem q" | ~p ∧ ~q |
| "p, a menos que q" / "p, salvo se q" | ~q → p (≡ p ∨ q) |
| "p somente se q" | p → q |
| "p se q" | q → p |
| "p é necessário para q" | q → p |
| "p é suficiente para q" | p → q |
| "Não é verdade que…" | negação de toda a sentença seguinte |

### Revisão rápida

<details><summary>Certo ou errado: "Se Ana estuda, então passa" equivale a "Se Ana passa, então estuda".</summary>

Errado. Essa é a recíproca, que não é equivalente. A equivalente é a contrapositiva: "Se Ana não passa, então não estuda".
</details>

<details><summary>Certo ou errado: "Se chove, a rua molha" equivale a "Não chove ou a rua molha".</summary>

Certo. p → q ≡ ~p ∨ q.
</details>

<details><summary>Qual a negação de "Pedro é alto ou Maria é baixa"?</summary>

"Pedro não é alto e Maria não é baixa" (De Morgan: ~p ∧ ~q).
</details>

<details><summary>Qual a negação de "Se o sistema cai, o técnico é chamado"?</summary>

"O sistema cai e o técnico não é chamado" (p ∧ ~q).
</details>

<details><summary>Certo ou errado: "Nem Ana nem Bia viajaram" equivale a "Não é verdade que Ana ou Bia viajaram".</summary>

Certo. ~p ∧ ~q ≡ ~(p ∨ q).
</details>

<details><summary>Certo ou errado: a negação de p ↔ q é p ⊻ q.</summary>

Certo. O bicondicional é V com valores iguais; a disjunção exclusiva, com valores diferentes.
</details>

<p align="right"><a href="#localizar-assunto">🔎 Localizar assunto</a> · <a href="#topo">⬆ Topo</a></p>

---

<a id="t03"></a>

## `03` Quantificadores, predicados e argumentos

> **Edital:** (…) quantificadores e predicados.

<a id="t03-predicados"></a>

### Sentenças abertas e predicados

Uma **sentença aberta** (ou **predicado**) contém variável: P(x): "x é par". Ela vira proposição de dois jeitos: **substituindo** a variável por um valor (P(4): "4 é par", V) ou **quantificando** ("Todo número natural é par", F).

O **conjunto universo** (U) é de onde x pode vir; o **conjunto verdade** (V) é o subconjunto de U que torna o predicado verdadeiro. Ex.: U = {1, 2, 3, 4, 5}, P(x): "x > 3" → V = {4, 5}.

<a id="t03-quantificadores"></a>

### Quantificadores e suas negações

- **Universal (∀):** "para todo", "qualquer que seja", "todo", "cada".
- **Existencial (∃):** "existe", "algum", "pelo menos um".
- **Existencial de unicidade (∃!):** "existe um único".

| Proposição | Negação |
|---|---|
| **Todo** A é B | **Algum** A **não** é B (Existe A que não é B) |
| **Algum** A é B | **Nenhum** A é B |
| **Nenhum** A é B | **Algum** A é B |
| **Algum** A **não** é B | **Todo** A é B |

Em símbolos: ~(∀x, P(x)) ≡ ∃x, ~P(x) e ~(∃x, P(x)) ≡ ∀x, ~P(x).

> ⚠️ **Pegadinha:** a negação de "Todo servidor é pontual" **não** é "Nenhum servidor é pontual". Basta **um** contraexemplo: "Algum servidor não é pontual" ou "Pelo menos um servidor não é pontual". A frase "Nenhum servidor é pontual" é a **contrária**, não a negação.

> 💡 **Para memorizar:** **"PEA + NÃO"** — a negação de **P**elo menos um / **E**xiste / **A**lgum é "**Nenhum**", e vice-versa. Todo ↔ Algum…não.

<a id="t03-diagramas"></a>

### Diagramas lógicos

- **Todo A é B:** o círculo A está **dentro** de B (A ⊂ B).
- **Nenhum A é B:** círculos **separados** (A ∩ B = ∅).
- **Algum A é B:** os círculos se **interceptam** (A ∩ B ≠ ∅) — não se sabe se há sobra.
- **Algum A não é B:** existe parte de A **fora** de B.

> 📘 **Exemplo:** "Todo analista é graduado. Algum graduado é atleta." Conclusão: "Algum analista é atleta"? **Não necessariamente.** O círculo dos atletas pode cruzar só a parte dos graduados que não são analistas. Desenhe o caso que **derruba** a conclusão: se ele existir, a conclusão não é obrigatória.

<a id="t03-argumentos"></a>

### Argumentos válidos e falácias

Um **argumento** é um conjunto de premissas que leva a uma conclusão. Ele é **válido** quando, **se todas as premissas forem verdadeiras, a conclusão é obrigatoriamente verdadeira**. Validade é forma, não conteúdo: um argumento pode ser válido com premissas falsas.

**Formas válidas clássicas**

| Nome | Forma |
|---|---|
| Modus ponens | p → q; p; ∴ q |
| Modus tollens | p → q; ~q; ∴ ~p |
| Silogismo hipotético | p → q; q → r; ∴ p → r |
| Silogismo disjuntivo | p ∨ q; ~p; ∴ q |
| Dilema construtivo | p → q; r → s; p ∨ r; ∴ q ∨ s |

**Falácias (formas inválidas)**

| Nome | Forma inválida |
|---|---|
| Afirmação do consequente | p → q; q; ∴ p |
| Negação do antecedente | p → q; ~p; ∴ ~q |

**Método prático para testar validade:** suponha a **conclusão falsa** e tente deixar **todas as premissas verdadeiras**. Se conseguir, o argumento é **inválido**; se der contradição, é **válido**.

> 📘 **Exemplo (método das premissas verdadeiras):** "Se Ana viaja, Bia fica. Se Bia fica, Caio trabalha. Caio não trabalha." O que se conclui?
> Comece pela proposição simples: ~Caio trabalha (V). Na 2ª premissa, "Bia fica → Caio trabalha" com consequente F exige antecedente F: **Bia não fica**. Na 1ª, "Ana viaja → Bia fica" com consequente F exige **Ana não viaja**.

### Revisão rápida

<details><summary>Certo ou errado: a negação de "Todo número primo é ímpar" é "Nenhum número primo é ímpar".</summary>

Errado. A negação é "Algum número primo não é ímpar" (e é verdadeira: o 2).
</details>

<details><summary>Certo ou errado: a negação de "Algum aluno faltou" é "Nenhum aluno faltou".</summary>

Certo.
</details>

<details><summary>Certo ou errado: "Se é gato, é mamífero. Totó é mamífero. Logo, Totó é gato" é argumento válido.</summary>

Errado. É a falácia da afirmação do consequente.
</details>

<details><summary>Certo ou errado: um argumento pode ser válido mesmo tendo premissas falsas.</summary>

Certo. Validade depende só da forma: premissas V garantiriam conclusão V.
</details>

<details><summary>Com U = {1, 2, 3, 4} e P(x): "x² < 5", qual o conjunto verdade?</summary>

{1, 2}. (1 < 5 e 4 < 5; 9 e 16 não.)
</details>

<p align="right"><a href="#localizar-assunto">🔎 Localizar assunto</a> · <a href="#topo">⬆ Topo</a></p>

---

<a id="t04"></a>

## `04` Conjuntos, operações e diagramas

> **Edital:** Conjuntos e suas operações, diagramas.

<a id="t04-nocoes"></a>

### Noções e representação

Um **conjunto** é uma coleção de elementos. Pode ser descrito por **enumeração** (A = {2, 4, 6}), por **propriedade** (A = {x | x é par e 0 < x < 8}) ou por **diagrama de Venn**.

- **Pertinência** (elemento ↔ conjunto): 2 ∈ A; 3 ∉ A.
- **Inclusão** (conjunto ↔ conjunto): {2, 4} ⊂ A; A ⊃ {2}.
- **Conjunto vazio:** ∅ ou { }. É subconjunto de **qualquer** conjunto.
- **Conjunto das partes** P(A): todos os subconjuntos de A. Se A tem **n** elementos, P(A) tem **2ⁿ** elementos.

> ⚠️ **Pegadinha:** ∈ liga **elemento** a conjunto; ⊂ liga **conjunto** a conjunto. Em A = {1, {2}}, temos {2} ∈ A (é elemento) e {1} ⊂ A, mas 2 ∉ A. Além disso, {∅} **não é vazio**: tem um elemento.

<a id="t04-operacoes"></a>

### Operações

| Operação | Símbolo | Definição |
|---|---|---|
| União | A ∪ B | elementos de A **ou** de B |
| Interseção | A ∩ B | elementos de A **e** de B |
| Diferença | A − B | elementos de A que **não** estão em B |
| Complementar | Aᶜ (ou A') | elementos do universo que não estão em A |
| Diferença simétrica | A Δ B | (A − B) ∪ (B − A): está em um só |

Conjuntos **disjuntos** têm interseção vazia. Leis de De Morgan para conjuntos: (A ∪ B)ᶜ = Aᶜ ∩ Bᶜ e (A ∩ B)ᶜ = Aᶜ ∪ Bᶜ — as mesmas da lógica.

<a id="t04-venn"></a>

### Contagem com diagramas de Venn

- **Dois conjuntos:** n(A ∪ B) = n(A) + n(B) − n(A ∩ B)
- **Três conjuntos:** n(A ∪ B ∪ C) = n(A) + n(B) + n(C) − n(A ∩ B) − n(A ∩ C) − n(B ∩ C) + n(A ∩ B ∩ C)

> 💡 **Para memorizar:** **preencha o diagrama de dentro para fora** — primeiro a interseção tripla, depois as duplas (descontando a tripla), depois o "só A", "só B", "só C", e por fim quem está fora de todos.

> 📘 **Exemplo:** 200 servidores pesquisados. 100 usam Linux (A), 80 usam Windows (B), 70 usam macOS (C); 30 usam A e B; 25 usam A e C; 20 usam B e C; 10 usam os três.
> - Só A e B: 30 − 10 = 20 · Só A e C: 25 − 10 = 15 · Só B e C: 20 − 10 = 10
> - Só A: 100 − 20 − 15 − 10 = **55** · Só B: 80 − 20 − 10 − 10 = **40** · Só C: 70 − 15 − 10 − 10 = **35**
> - União: 55 + 40 + 35 + 20 + 15 + 10 + 10 = **185** → **15** não usam nenhum.

<a id="t04-numericos"></a>

### Conjuntos numéricos

ℕ ⊂ ℤ ⊂ ℚ ⊂ ℝ, e ℝ = ℚ ∪ 𝕀 (racionais e irracionais são disjuntos).

| Conjunto | Elementos |
|---|---|
| ℕ (naturais) | {0, 1, 2, 3, …} |
| ℤ (inteiros) | {…, −2, −1, 0, 1, 2, …} |
| ℚ (racionais) | frações a/b com a, b inteiros e b ≠ 0 (inclui decimais exatos e dízimas periódicas) |
| 𝕀 (irracionais) | decimais infinitos **não** periódicos: √2, √3, π, e |
| ℝ (reais) | todos os anteriores |

Símbolos: **\*** exclui o zero (ℕ\*), **+** só não negativos, **−** só não positivos.

### Revisão rápida

<details><summary>Certo ou errado: um conjunto com 4 elementos tem 16 subconjuntos.</summary>

Certo. 2⁴ = 16 (incluindo ∅ e o próprio conjunto).
</details>

<details><summary>Certo ou errado: ∅ ∈ {1, 2}.</summary>

Errado. O vazio é subconjunto (∅ ⊂ {1, 2}), mas não é elemento.
</details>

<details><summary>Numa turma, 25 gostam de Matemática, 18 de Português e 7 de ambas. Todos gostam de pelo menos uma. Quantos alunos há?</summary>

25 + 18 − 7 = 36.
</details>

<details><summary>Certo ou errado: 0,333… é um número irracional.</summary>

Errado. Dízima periódica é racional: 0,333… = 1/3.
</details>

<details><summary>Se A = {1, 2, 3, 4} e B = {3, 4, 5}, quanto é A − B?</summary>

{1, 2}.
</details>

<p align="right"><a href="#localizar-assunto">🔎 Localizar assunto</a> · <a href="#topo">⬆ Topo</a></p>

---

<a id="t05"></a>

## `05` Números inteiros, racionais e reais e suas operações

> **Edital:** Números inteiros, racionais e reais e suas operações (…).

<a id="t05-operacoes"></a>

### Operações e ordem

**Regra de sinais** (multiplicação e divisão): sinais **iguais** dão **+**; sinais **diferentes** dão **−**.

**Ordem das operações:** 1) parênteses ( ), colchetes [ ], chaves { }; 2) potências e raízes; 3) multiplicações e divisões, na ordem em que aparecem; 4) adições e subtrações, na ordem em que aparecem.

> 📘 **Exemplo:** 20 − 3 × 2² + 8 ÷ 4 = 20 − 3 × 4 + 2 = 20 − 12 + 2 = **10**.

> ⚠️ **Pegadinha:** (−2)² = **4**, mas −2² = **−4** (a potência vem antes do sinal). E a divisão por zero não é definida.

<a id="t05-divisibilidade"></a>

### Divisibilidade, MMC e MDC

**Critérios de divisibilidade**

| Por | Regra |
|---|---|
| 2 | termina em número par |
| 3 | soma dos algarismos divisível por 3 |
| 4 | dois últimos algarismos formam número divisível por 4 (ou 00) |
| 5 | termina em 0 ou 5 |
| 6 | divisível por 2 **e** por 3 |
| 8 | três últimos algarismos divisíveis por 8 |
| 9 | soma dos algarismos divisível por 9 |
| 10 | termina em 0 |
| 11 | (soma dos algarismos de ordem ímpar) − (soma dos de ordem par) é múltiplo de 11 |

**Número primo** tem exatamente dois divisores (1 e ele mesmo): 2, 3, 5, 7, 11, 13, 17, 19, 23, 29… O **2** é o único primo par; o **1** não é primo.

**Quantidade de divisores:** fatore, some 1 a cada expoente e multiplique. 72 = 2³ × 3² → (3 + 1)(2 + 1) = **12 divisores**.

- **MDC** (máximo divisor comum): fatores **comuns** com **menor** expoente. Problemas de "**dividir em partes iguais, o maior possível**".
- **MMC** (mínimo múltiplo comum): **todos** os fatores com **maior** expoente. Problemas de "**coincidência, encontro de novo, ciclos**".
- Para dois números: **MDC(a, b) × MMC(a, b) = a × b**.

> 📘 **Exemplo:** dois ônibus saem juntos do terminal às 8h; um sai a cada 12 min, o outro a cada 18 min. Quando saem juntos de novo?
> 12 = 2² × 3; 18 = 2 × 3². MMC = 2² × 3² = 36 → **8h36**. (MDC = 6; 6 × 36 = 216 = 12 × 18.)

<a id="t05-fracoes"></a>

### Frações e dízimas

- **Somar/subtrair:** reduza ao mesmo denominador (MMC). 1/4 + 1/6 = 3/12 + 2/12 = 5/12.
- **Multiplicar:** numerador × numerador e denominador × denominador.
- **Dividir:** multiplica a primeira pelo **inverso** da segunda. (3/4) ÷ (1/2) = 3/4 × 2 = 3/2.
- **"Fração de fração":** "2/3 de 3/5 de 100" = 2/3 × 3/5 × 100 = 40.

**Fração geratriz das dízimas periódicas**

- **Simples** (período logo após a vírgula): o período sobre tantos 9 quantos forem os algarismos do período. 0,777… = 7/9; 0,1212… = 12/99 = 4/33.
- **Composta** (há parte não periódica): (antiperíodo e período − antiperíodo) sobre tantos 9 quanto o período, seguidos de tantos 0 quanto o antiperíodo. 0,1666… = (16 − 1)/90 = 15/90 = **1/6**.

> ⚠️ **Pegadinha:** 0,999… = **1** (9/9). Não é "quase 1".

<a id="t05-potencias"></a>

### Potências e raízes

| Propriedade | Exemplo |
|---|---|
| aᵐ × aⁿ = aᵐ⁺ⁿ | 2³ × 2² = 2⁵ = 32 |
| aᵐ ÷ aⁿ = aᵐ⁻ⁿ | 5⁴ ÷ 5² = 25 |
| (aᵐ)ⁿ = aᵐˣⁿ | (3²)³ = 3⁶ = 729 |
| a⁰ = 1 (a ≠ 0) | 7⁰ = 1 |
| a⁻ⁿ = 1/aⁿ | 2⁻³ = 1/8 |
| a^(m/n) = ⁿ√(aᵐ) | 8^(2/3) = (∛8)² = 4 |
| √(a × b) = √a × √b | √50 = √25 × √2 = 5√2 |

> ⚠️ **Pegadinha:** √(a + b) ≠ √a + √b. √(9 + 16) = √25 = 5, e não 3 + 4 = 7. E (2³)² = 2⁶ = 64, enquanto 2^(3²) = 2⁹ = 512.

**Notação científica:** a × 10ⁿ com 1 ≤ a < 10. 0,00045 = 4,5 × 10⁻⁴.

### Revisão rápida

<details><summary>Certo ou errado: o número 1 é primo.</summary>

Errado. Primo tem exatamente dois divisores; 1 tem apenas um.
</details>

<details><summary>Certo ou errado: 3.582 é divisível por 9.</summary>

Certo. 3 + 5 + 8 + 2 = 18, que é divisível por 9.
</details>

<details><summary>Uma loja tem 48 canetas azuis e 72 pretas. Quer montar kits iguais, com o maior número de kits, sem misturar sobras. Quantos kits?</summary>

MDC(48, 72) = 24 kits, cada um com 2 azuis e 3 pretas.
</details>

<details><summary>Qual a fração geratriz de 0,4545…?</summary>

45/99 = 5/11.
</details>

<details><summary>Certo ou errado: −3² = 9.</summary>

Errado. −3² = −9; (−3)² = 9.
</details>

<p align="right"><a href="#localizar-assunto">🔎 Localizar assunto</a> · <a href="#topo">⬆ Topo</a></p>

---

<a id="t06"></a>

## `06` Porcentagem e juros

> **Edital:** (…) porcentagem e juros.

<a id="t06-porcentagem"></a>

### Porcentagem e fator multiplicativo

**x%** = x/100. "30% de 250" = 0,30 × 250 = 75.

O atalho que resolve quase tudo é o **fator multiplicativo**:

- **Aumento de i%:** multiplica por **(1 + i)**. Aumento de 15% → × 1,15.
- **Desconto de i%:** multiplica por **(1 − i)**. Desconto de 15% → × 0,85.

**Variação percentual:** (valor final − valor inicial) ÷ valor inicial × 100.

> 📘 **Exemplo:** um produto passou de R$ 80 para R$ 100. Aumento = 20/80 = **25%**. Se voltar de R$ 100 para R$ 80, o desconto é 20/100 = **20%**. A base muda!

> 📘 **Exemplo (valor original):** após desconto de 20%, um item custa R$ 360. Preço original = 360 ÷ 0,8 = **R$ 450**.

<a id="t06-sucessivos"></a>

### Aumentos e descontos sucessivos

Multiplique os fatores; **nunca some** as porcentagens.

> 📘 **Exemplo:** aumento de 20% seguido de desconto de 20%: 1,20 × 0,80 = 0,96 → **perda de 4%**, e não 0%.
> Dois aumentos de 10%: 1,10 × 1,10 = 1,21 → aumento de **21%**.

> ⚠️ **Pegadinha:** "aumento de 100%" dobra o valor (× 2); "aumento de 200%" triplica (× 3). E diferença de "pontos percentuais": uma taxa que vai de 10% para 12% subiu **2 pontos percentuais**, ou **20%**.

<a id="t06-simples"></a>

### Juros simples

O juro incide **sempre sobre o capital inicial**: cresce em **progressão aritmética** (linearmente).

- **J = C × i × t**
- **M = C + J = C × (1 + i × t)**

C = capital; i = taxa (decimal); t = tempo; M = montante. **Taxa e tempo na mesma unidade.**

> 📘 **Exemplo:** R$ 1.000 a 2% ao mês por 6 meses. J = 1.000 × 0,02 × 6 = **R$ 120**; M = **R$ 1.120**.

<a id="t06-compostos"></a>

### Juros compostos

O juro de cada período incorpora-se ao capital ("juros sobre juros"): cresce em **progressão geométrica** (exponencialmente).

- **M = C × (1 + i)ᵗ**
- **J = M − C**

> 📘 **Exemplo:** R$ 1.000 a 10% ao mês por 2 meses. M = 1.000 × 1,1² = 1.000 × 1,21 = **R$ 1.210**; J = R$ 210 (no regime simples seriam R$ 200).

> 💡 **Para memorizar:** para **t = 1**, simples e compostos dão o mesmo montante. Para **t > 1**, compostos rendem mais; para **0 < t < 1**, simples rendem mais.

<a id="t06-taxas"></a>

### Taxas proporcionais, equivalentes, nominal e efetiva

- **Proporcionais** (juros simples): basta dividir/multiplicar. 1% a.m. = 12% a.a.
- **Equivalentes** (juros compostos): (1 + i_ano) = (1 + i_mês)¹². 1% a.m. → 1,01¹² − 1 ≈ **12,68% a.a.**
- **Taxa nominal:** unidade diferente do período de capitalização (ex.: "12% a.a. capitalizados mensalmente"). A **efetiva** é a que realmente incide: 1% a.m. → ≈ 12,68% a.a.

### Revisão rápida

<details><summary>Certo ou errado: dois descontos sucessivos de 10% equivalem a um desconto de 20%.</summary>

Errado. 0,9 × 0,9 = 0,81 → desconto de 19%.
</details>

<details><summary>Certo ou errado: no regime de juros simples, o montante cresce em progressão geométrica.</summary>

Errado. Cresce em progressão aritmética (linear). PG é o regime composto.
</details>

<details><summary>Qual capital, a juros simples de 5% a.m., rende R$ 300 em 4 meses?</summary>

300 = C × 0,05 × 4 → C = 300/0,2 = R$ 1.500.
</details>

<details><summary>A taxa de desemprego passou de 8% para 10%. Qual o aumento percentual?</summary>

25% (2/8). O aumento foi de 2 pontos percentuais.
</details>

<details><summary>Quanto rende R$ 2.000 a juros compostos de 10% a.a. em 3 anos?</summary>

M = 2.000 × 1,331 = R$ 2.662; juros = R$ 662.
</details>

<p align="right"><a href="#localizar-assunto">🔎 Localizar assunto</a> · <a href="#topo">⬆ Topo</a></p>

---

<a id="t07"></a>

## `07` Proporcionalidade direta e inversa

> **Edital:** Proporcionalidade direta e inversa.

<a id="t07-razao"></a>

### Razão e proporção

**Razão** entre a e b é a/b (b ≠ 0). **Proporção** é a igualdade de duas razões: a/b = c/d.

- **Propriedade fundamental:** o produto dos meios é igual ao dos extremos: **a × d = b × c**.
- **Soma das razões:** se a/b = c/d = k, então (a + c)/(b + d) = k. Útil para dividir quantias.

Razões especiais: **escala** (desenho/real), **velocidade** (distância/tempo), **densidade** (massa/volume), **densidade demográfica** (habitantes/área).

<a id="t07-grandezas"></a>

### Grandezas direta e inversamente proporcionais

| | Diretamente proporcionais | Inversamente proporcionais |
|---|---|---|
| Comportamento | uma dobra, a outra dobra | uma dobra, a outra cai pela metade |
| Constante | **razão** x/y = k | **produto** x × y = k |
| Exemplos | quantidade × preço; tempo × distância (velocidade fixa) | velocidade × tempo; nº de operários × dias |

<a id="t07-regra"></a>

### Regra de três simples e composta

**Simples:** monte a tabela, marque com setas se as grandezas são diretas (mesmo sentido) ou inversas (sentido contrário), inverta a coluna inversa e resolva.

> 📘 **Exemplo (inversa):** 6 pedreiros fazem um muro em 10 dias. Em quantos dias 4 pedreiros fazem o mesmo muro? Menos pedreiros → **mais** dias (inversa). 6 × 10 = 4 × x → x = **15 dias**.

**Composta:** compare **cada** grandeza com a incógnita, mantendo as demais fixas.

> 📘 **Exemplo (composta):** 5 máquinas, trabalhando 8 h/dia, produzem 400 peças em 4 dias. Quantas peças 8 máquinas produzem trabalhando 6 h/dia durante 5 dias?
> Peças são diretamente proporcionais a máquinas, horas e dias:
> x = 400 × (8/5) × (6/8) × (5/4) = 400 × 240/160 = **600 peças**.

> 💡 **Para memorizar:** em regra de três composta pergunte sempre "**se eu aumentar esta grandeza, a incógnita aumenta ou diminui?**", olhando uma de cada vez.

<a id="t07-divisao"></a>

### Divisão proporcional

- **Diretamente proporcional:** dividir N em partes proporcionais a a, b, c → cada parte = k × peso, com k = N/(a + b + c).
- **Inversamente proporcional:** use os **inversos** dos pesos (1/a, 1/b, 1/c), reduza a inteiros pelo MMC e divida diretamente.

> 📘 **Exemplo:** dividir R$ 600 em partes **diretamente** proporcionais a 2, 3 e 5: k = 600/10 = 60 → **120, 180 e 300**.
> Dividir R$ 600 em partes **inversamente** proporcionais a 2, 3 e 6: inversos 1/2, 1/3, 1/6 → × 6 → 3, 2, 1 → k = 600/6 = 100 → **300, 200 e 100**.

> ⚠️ **Pegadinha:** na divisão inversa, quem tem **maior** peso recebe **menos**. Isso aparece em prêmios divididos "inversamente ao número de faltas".

### Revisão rápida

<details><summary>Certo ou errado: velocidade e tempo de percurso (mesma distância) são grandezas diretamente proporcionais.</summary>

Errado. São inversamente proporcionais: dobrar a velocidade reduz o tempo pela metade.
</details>

<details><summary>Se 3 kg de café custam R$ 54, quanto custam 5 kg?</summary>

R$ 90 (R$ 18/kg).
</details>

<details><summary>Uma torneira enche um tanque em 12 h com vazão de 10 L/min. Com 15 L/min, em quanto tempo?</summary>

12 × 10/15 = 8 h (inversa).
</details>

<details><summary>Certo ou errado: se x/y = 3/5 e x + y = 40, então x = 15.</summary>

Certo. k = 40/8 = 5; x = 3 × 5 = 15 e y = 25.
</details>

<p align="right"><a href="#localizar-assunto">🔎 Localizar assunto</a> · <a href="#topo">⬆ Topo</a></p>

---

<a id="t08"></a>

## `08` Medidas: comprimento, área, volume, massa e tempo

> **Edital:** Medidas de comprimento, área, volume, massa e tempo.

<a id="t08-sistema"></a>

### Sistema métrico decimal

**km · hm · dam · m · dm · cm · mm** — a cada casa, **× 10** para a direita (unidade menor) e **÷ 10** para a esquerda.

| Grandeza | Fator entre casas vizinhas | Exemplo |
|---|---|---|
| Comprimento (m) | **10** | 1 km = 1.000 m |
| Área (m²) | **100** | 1 m² = 10.000 cm² |
| Volume (m³) | **1.000** | 1 m³ = 1.000.000 cm³ |

> 💡 **Para memorizar:** o expoente da unidade diz quantos zeros "andam" por casa: m → 1 zero, m² → 2 zeros, m³ → 3 zeros.

<a id="t08-area-volume"></a>

### Área e volume

**Unidades agrárias:** 1 **are** (a) = 100 m²; 1 **hectare** (ha) = 10.000 m² = 1 hm²; 1 km² = **100 ha**.

**Volumes de sólidos frequentes**

| Sólido | Volume |
|---|---|
| Cubo de aresta a | a³ |
| Paralelepípedo | comprimento × largura × altura |
| Prisma qualquer | área da base × altura |
| Cilindro | π r² × h |
| Pirâmide / cone | (área da base × altura) / 3 |
| Esfera | (4/3) π r³ |

<a id="t08-capacidade"></a>

### Capacidade e massa

- **1 dm³ = 1 L** · **1 m³ = 1.000 L** · **1 cm³ = 1 mL**
- Capacidade: kL · hL · daL · **L** · dL · cL · mL (fator 10).
- Massa: kg · hg · dag · **g** · dg · cg · mg (fator 10). **1 t = 1.000 kg**; 1 arroba ≈ 15 kg.
- Para a água (aprox.): 1 L ↔ 1 kg.

> 📘 **Exemplo:** uma caixa-d'água de 2 m × 1,5 m × 1 m comporta 3 m³ = **3.000 L**.

> ⚠️ **Pegadinha:** ao dobrar as arestas de um cubo, a área dobra? Não: área × 4 (2²) e volume × 8 (2³).

<a id="t08-tempo"></a>

### Tempo

O sistema é **sexagesimal**, não decimal: 1 h = 60 min = 3.600 s; 1 dia = 24 h = 1.440 min = 86.400 s.

| Decimal | Horas e minutos |
|---|---|
| 0,1 h | 6 min |
| 0,25 h | 15 min |
| 0,5 h | 30 min |
| 1,75 h | 1 h 45 min |
| 2,3 h | 2 h 18 min |

> ⚠️ **Pegadinha:** **1,5 h é 1 h 30 min**, e não 1 h 50 min. E subtrair horários exige "pedir emprestado" 60: 10h15 − 7h40 = 9h75 − 7h40 = **2h35**.

Outras: 1 semana = 7 dias; ano comercial = 360 dias (mês de 30 dias); ano civil = 365 ou 366 dias; década = 10 anos; século = 100; milênio = 1.000.

<a id="t08-velocidade"></a>

### Velocidade e escala

- **v = d / t**. Conversão: **km/h ÷ 3,6 = m/s** (e m/s × 3,6 = km/h). 72 km/h = 20 m/s.
- **Escala = medida no desenho / medida real**, com as mesmas unidades. Escala 1 : 50.000 → 1 cm no mapa = 50.000 cm = **500 m** reais.
- Em escala, **áreas** ficam multiplicadas pelo **quadrado** da escala.

### Revisão rápida

<details><summary>Quantos litros cabem em 0,75 m³?</summary>

750 L.
</details>

<details><summary>Certo ou errado: 1 m² = 100 cm².</summary>

Errado. 1 m² = 10.000 cm² (100 × 100).
</details>

<details><summary>Certo ou errado: 3,2 horas equivalem a 3 h 20 min.</summary>

Errado. 0,2 h = 12 min → 3 h 12 min.
</details>

<details><summary>Um terreno de 250 m × 200 m tem quantos hectares?</summary>

50.000 m² = 5 ha.
</details>

<details><summary>Num mapa de escala 1 : 200.000, duas cidades estão a 7 cm. Qual a distância real?</summary>

1.400.000 cm = 14 km.
</details>

<p align="right"><a href="#localizar-assunto">🔎 Localizar assunto</a> · <a href="#topo">⬆ Topo</a></p>

---

<a id="t09"></a>

## `09` Estrutura lógica de relações arbitrárias

> **Edital:** Estrutura lógica de relações arbitrárias entre pessoas, lugares, objetos ou eventos fictícios; dedução de novas informações das relações fornecidas e avaliação das condições usadas para estabelecer a estrutura daquelas relações.

São os problemas "de quebra-cabeça": a banca descreve pessoas, lugares, objetos ou eventos inventados, dá pistas e pergunta o que pode ser **deduzido**. O texto do edital tem três verbos que viram três tipos de questão: **montar a estrutura**, **deduzir** informação nova e **avaliar as condições** (qual pista é desnecessária, qual seria suficiente, qual torna o problema impossível).

<a id="t09-associacao"></a>

### Lógica de associação (tabela de dupla entrada)

Monte uma tabela cruzando as categorias. Marque **✗** para o que é impossível e **●** para o que é certo. Cada linha e cada coluna tem **um único ●**; quando você marca ●, preencha ✗ no resto da linha e da coluna.

> 📘 **Exemplo:** Ana, Bruno e Carla são médico, engenheiro e professor (não necessariamente nessa ordem) e moram em Belém, Marabá e Santarém.
> 1. Ana não é médica e não mora em Belém.
> 2. Quem é engenheiro mora em Marabá.
> 3. Carla mora em Santarém.
> 4. Bruno não é engenheiro.
> 5. Quem mora em Santarém não é médico.
>
> **Solução:** (3) Carla → Santarém. (1) Ana não mora em Belém → Ana → **Marabá**; sobra Bruno → **Belém**. (2) O engenheiro mora em Marabá → **Ana é engenheira**. (5) Carla (Santarém) não é médica → **Carla é professora** → **Bruno é médico**.
>
> | | Médico | Engenheiro | Professor | Cidade |
> |---|:-:|:-:|:-:|---|
> | Ana | ✗ | ● | ✗ | Marabá |
> | Bruno | ● | ✗ | ✗ | Belém |
> | Carla | ✗ | ✗ | ● | Santarém |

> 💡 **Para memorizar:** comece pela pista **mais restritiva** (uma afirmação positiva, "Carla mora em Santarém") e só depois use as negativas.

<a id="t09-ordenacao"></a>

### Ordenação e posições

Para filas, prédios, corridas e mesas: desenhe os lugares (**_ _ _ _ _**) e posicione os blocos fixos primeiro.

- "A está **imediatamente** à frente de B" → bloco **AB** (adjacentes).
- "A está à frente de B" → apenas A antes de B (pode haver gente no meio).
- **Mesa circular:** fixe uma pessoa e posicione as demais em relação a ela; "à direita de quem está sentado" depende de a pessoa estar de frente para a mesa.

<a id="t09-verdades"></a>

### Verdades e mentiras

Teste **hipóteses**: suponha que alguém diz a verdade (ou é o culpado) e veja se o resto fica coerente. Se surgir contradição, descarte a hipótese.

> 📘 **Exemplo (um só fala a verdade):** um dos três é o culpado. A: "B é o culpado." B: "Eu não sou o culpado." C: "Eu não sou o culpado." Só um diz a verdade.
> - Se o culpado é A: A mente, B e C falam a verdade → 2 verdades ✗
> - Se é B: A e C falam a verdade → 2 verdades ✗
> - Se é C: A mente, B fala a verdade, C mente → **1 verdade ✓** → **C é o culpado**.

> 📘 **Exemplo (cavaleiros e valetes):** cavaleiros sempre dizem a verdade, valetes sempre mentem. A diz: "Nós dois somos valetes." Se A fosse cavaleiro, a frase seria verdadeira e ele seria valete — contradição. Então **A é valete** e a frase é falsa: não são os dois valetes → **B é cavaleiro**.

> ⚠️ **Pegadinha:** ninguém, nem cavaleiro nem valete, pode dizer "**Eu sou valete**": o cavaleiro estaria mentindo e o valete estaria dizendo a verdade.

<a id="t09-condicoes"></a>

### Avaliar as condições (o que pode e o que deve ser)

- **"Necessariamente / certamente"**: verdadeiro em **todas** as soluções possíveis.
- **"Pode ser / é possível"**: verdadeiro em **pelo menos uma** solução.
- **Pista redundante**: retire-a; se a solução continuar única, ela era desnecessária. No exemplo de associação, sem a pista 5 haveria duas soluções (Bruno e Carla trocariam médico/professor), logo a 5 é **necessária**; já a pista 4 é **redundante** (Ana já era a engenheira por 1–3).

### Revisão rápida

<details><summary>Certo ou errado: "Necessariamente" exige que a afirmação valha em todas as configurações compatíveis com as pistas.</summary>

Certo. Basta um contraexemplo para derrubar uma afirmação "necessária".
</details>

<details><summary>Certo ou errado: em uma tabela de associação, ao marcar um "●", todas as outras células da mesma linha e coluna recebem "✗".</summary>

Certo (quando a associação é um a um).
</details>

<details><summary>A diz: "B é valete." B diz: "A e eu somos do mesmo tipo." O que são A e B?</summary>

Se A é cavaleiro, B é valete; então a fala de B ("mesmo tipo") é falsa — coerente. Se A é valete, B é cavaleiro; então "mesmo tipo" deveria ser verdadeira, mas não é — contradição. Logo A é cavaleiro e B é valete.
</details>

<p align="right"><a href="#localizar-assunto">🔎 Localizar assunto</a> · <a href="#topo">⬆ Topo</a></p>

---

<a id="t10"></a>

## `10` Funções intelectuais: raciocínio verbal, sequencial, espacial e temporal

> **Edital:** Compreensão e análise da lógica de uma situação, utilizando as funções intelectuais: raciocínio verbal, raciocínio matemático, raciocínio sequencial, orientação espacial e temporal, formação de conceitos, discriminação de elementos.

<a id="t10-verbal"></a>

### Raciocínio verbal

Interpretar com precisão o que o texto **diz** (e o que **não diz**).

- **Analogias:** "Médico está para hospital assim como professor está para… escola." Identifique a relação (profissional → local de trabalho) e aplique-a.
- **Inferência:** conclua **apenas** o que decorre do texto. "Alguns servidores do IFPA são professores" **não** permite concluir que "alguns servidores não são professores".
- **Conectivos ocultos:** "Só entra quem tem crachá" = "Se entra, então tem crachá" (ter crachá é **necessário**, não suficiente).

> ⚠️ **Pegadinha:** "Todo A é B" **não** significa "Todo B é A". "Todo paraense é brasileiro" não autoriza "Todo brasileiro é paraense".

<a id="t10-sequencial"></a>

### Raciocínio sequencial

Procure o padrão nesta ordem: **diferenças** entre termos → **razões** (multiplicações) → **diferenças das diferenças** → **duas sequências intercaladas** → **soma dos anteriores** (Fibonacci) → **posição no alfabeto**.

| Sequência | Lei | Próximo |
|---|---|---|
| 3, 7, 11, 15, … | PA de razão 4 | 19 |
| 2, 6, 18, 54, … | PG de razão 3 | 162 |
| 2, 6, 12, 20, 30, … | diferenças 4, 6, 8, 10 → +12 | 42 |
| 1, 1, 2, 3, 5, 8, … | Fibonacci (soma dos dois anteriores) | 13 |
| 1, 10, 2, 20, 3, 30, … | duas intercaladas | 4 |
| A, C, F, J, O, … | posições 1, 3, 6, 10, 15 (+2, +3, +4, +5) | U (21) |

**Fórmulas de progressões**

- **PA:** aₙ = a₁ + (n − 1) r · Soma Sₙ = (a₁ + aₙ) × n / 2
- **PG:** aₙ = a₁ × qⁿ⁻¹ · Soma Sₙ = a₁ (qⁿ − 1)/(q − 1)

**Sequências cíclicas:** se o padrão se repete a cada **k** termos, o termo **n** é o mesmo da posição **resto de n ÷ k** (resto 0 = último do ciclo).

> 📘 **Exemplo:** na sequência IFPAIFPAIFPA…, qual a 2026ª letra? Ciclo de 4; 2026 ÷ 4 = 506, resto **2** → segunda letra: **F**.

> 💡 **Para memorizar:** alfabeto com 26 letras (K, W, Y incluídas). Âncoras: **E = 5, J = 10, O = 15, T = 20, Y = 25**.

<a id="t10-espacial"></a>

### Orientação espacial

- **Pontos cardeais:** N, S, L (E), O (W); colaterais NE, NO, SE, SO. Girar 90° à direita a partir do Norte leva ao Leste.
- **Dado comum:** faces opostas somam **7** (1–6, 2–5, 3–4).
- **Planificações do cubo:** há 11 planificações; numa planificação em "cruz", faces separadas por **uma** face no meio, na mesma linha, ficam **opostas**.
- **Rotação e reflexão (espelho):** rotacionar preserva a "mão" da figura; espelhar a inverte.
- **Direita/esquerda relativas:** a direita de quem está de frente para você é a sua esquerda.

> 📘 **Exemplo:** uma pessoa anda 4 km para o norte, 3 km para o leste e 4 km para o sul. A que distância está do ponto de partida? Norte e sul se anulam → **3 km** (a leste).

<a id="t10-temporal"></a>

### Orientação temporal

- **Dias da semana repetem a cada 7 dias.** Para avançar n dias, avance o **resto de n ÷ 7**.
- **Ano comum** (365 = 52 × 7 + 1): o mesmo dia do ano seguinte cai **1 dia da semana à frente**. **Ano bissexto** (366): **2 dias à frente**.
- **Bissexto:** divisível por 4; os terminados em 00 só se forem divisíveis por 400 (2000 foi; 1900 não; **2028** será).
- **Relógio:** o ângulo entre os ponteiros às **H** horas e **M** minutos é **|30H − 5,5M|** (se passar de 180°, use 360° menos o valor).

> 📘 **Exemplo:** às 2h20 → |30 × 2 − 5,5 × 20| = |60 − 110| = **50°**.

> 📘 **Exemplo:** se hoje é quarta-feira, que dia será daqui a 100 dias? 100 ÷ 7 = 14, resto 2 → quarta + 2 = **sexta-feira**.

> ⚠️ **Pegadinha:** "Anteontem de amanhã" = **ontem** (amanhã = +1; anteontem = −2; total −1). Faça a conta com números.

<a id="t10-conceitos"></a>

### Formação de conceitos e discriminação de elementos

- **Formação de conceitos:** descobrir o **critério comum** a um grupo (todos são mamíferos, todos são números primos, todas as palavras têm 5 letras…).
- **Discriminação de elementos:** achar **o diferente** ("qual não pertence ao grupo?") ou comparar figuras quase iguais.
- Teste vários critérios: forma, cor, quantidade, posição, número de letras, vogais/consoantes, paridade, se é primo.

> 📘 **Exemplo:** qual não pertence: 2, 3, 5, 9, 11? Todos são primos, menos o **9** (3 × 3).

### Revisão rápida

<details><summary>Qual o próximo termo de 1, 4, 9, 16, 25, …?</summary>

36 (quadrados perfeitos: 6²).
</details>

<details><summary>Certo ou errado: em um dado comum, a face oposta ao 2 é o 5.</summary>

Certo. Faces opostas somam 7.
</details>

<details><summary>Se 1º de janeiro de um ano não bissexto foi uma segunda-feira, em que dia caiu 31 de dezembro?</summary>

Segunda-feira. 31/12 é o dia 365 = 1 + 364 (52 semanas exatas).
</details>

<details><summary>Qual o ângulo entre os ponteiros às 3h00?</summary>

90° (|30 × 3 − 0|).
</details>

<details><summary>Qual o 10º termo da PA 5, 8, 11, …?</summary>

a₁₀ = 5 + 9 × 3 = 32.
</details>

<p align="right"><a href="#localizar-assunto">🔎 Localizar assunto</a> · <a href="#topo">⬆ Topo</a></p>

---

<a id="t11"></a>

## `11` Compreensão de dados em gráficos e tabelas

> **Edital:** Compreensão de dados apresentados em gráficos e tabelas.

<a id="t11-tipos"></a>

### Tipos de gráfico e quando aparecem

| Tipo | Serve para | Atenção |
|---|---|---|
| **Colunas / barras** | comparar categorias | comece o eixo em zero |
| **Linhas** | evolução no tempo | inclinação = ritmo de variação |
| **Setores (pizza)** | partes de um todo (100%) | **ângulo = % × 3,6°** |
| **Histograma** | distribuição de dados em classes contínuas | barras encostadas; área ∝ frequência |
| **Pictograma** | ícones proporcionais à quantidade | verifique o valor de cada ícone |
| **Tabela** | valores exatos, cruzamento de categorias | leia título, unidade e fonte |

> 📘 **Exemplo (setores):** 25% → 90°; 10% → 36°; 1/3 → 120°. Um setor de 54° representa 54/360 = **15%**.

**Frequências:** **absoluta** (contagem), **relativa** (contagem ÷ total), **acumulada** (soma até a classe).

<a id="t11-medidas"></a>

### Medidas de tendência central

- **Média aritmética:** soma ÷ quantidade. **Ponderada:** Σ(valor × peso) ÷ Σ pesos.
- **Mediana:** valor central dos dados **ordenados**. Com quantidade par, média dos dois centrais.
- **Moda:** valor mais frequente (pode haver mais de uma, ou nenhuma).

> 📘 **Exemplo:** dados 3, 7, 8, 10, 15. Média = 43/5 = **8,6**; mediana = **8**. Se o 15 virar 150, a média salta para 35,6, mas a mediana continua **8** — a mediana é resistente a valores extremos.

> 📘 **Exemplo (ponderada):** notas 6 (peso 2), 8 (peso 3) → (12 + 24)/5 = **7,2**.

> 💡 **Para memorizar:** somar uma constante a todos os dados soma essa constante à média, à moda e à mediana; multiplicar todos por k multiplica as três por k.

<a id="t11-leitura"></a>

### Leitura crítica

- Leia **título, eixos, unidades e legenda** antes dos dados ("em milhares", "em %").
- **Eixo truncado** exagera diferenças visuais.
- Diferencie **variação absoluta** (de 200 para 250: +50) de **variação percentual** (+25%).
- Em tabelas de dupla entrada, confira se a pergunta é sobre a **linha**, a **coluna** ou o **total geral**.

> ⚠️ **Pegadinha:** a maior **variação percentual** nem sempre é a maior **variação absoluta**. De 10 para 20 é +100%; de 500 para 600 é só +20%, embora absoluto seja +100.

### Revisão rápida

<details><summary>Num gráfico de setores, quantos graus correspondem a 40%?</summary>

144° (40 × 3,6).
</details>

<details><summary>Qual a mediana de 4, 1, 9, 6?</summary>

Ordenando: 1, 4, 6, 9 → (4 + 6)/2 = 5.
</details>

<details><summary>Certo ou errado: a média é menos afetada por valores extremos do que a mediana.</summary>

Errado. É o contrário: a mediana é mais resistente.
</details>

<details><summary>Certo ou errado: o histograma é indicado para dados contínuos agrupados em classes.</summary>

Certo.
</details>

<p align="right"><a href="#localizar-assunto">🔎 Localizar assunto</a> · <a href="#topo">⬆ Topo</a></p>

---

<a id="t12"></a>

## `12` Problemas aritméticos, geométricos e matriciais

> **Edital:** Raciocínio lógico envolvendo problemas aritméticos, geométricos e matriciais.

<a id="t12-aritmeticos"></a>

### Problemas aritméticos (equações)

Roteiro: **nomeie a incógnita**, **traduza** cada frase em equação, **resolva** e **confira** no enunciado.

| Frase | Equação |
|---|---|
| "o dobro de um número mais 5" | 2x + 5 |
| "a terça parte de um número" | x/3 |
| "dois números consecutivos" | x e x + 1 |
| "a soma é 50 e a diferença é 10" | x + y = 50; x − y = 10 → x = 30, y = 20 |
| "A tem 3 a mais que B" | A = B + 3 |

> 📘 **Exemplo (idades):** um pai tem o triplo da idade do filho. Daqui a 10 anos terá o dobro. Idades?
> P = 3F e P + 10 = 2(F + 10) → 3F + 10 = 2F + 20 → **F = 10, P = 30**.

> 📘 **Exemplo (torneiras / trabalho conjunto):** uma torneira enche um tanque em 3 h e outra em 6 h. Juntas: 1/3 + 1/6 = 1/2 do tanque por hora → **2 h**. (Ralo que esvazia entra com sinal **−**.)

> 📘 **Exemplo (galinhas e coelhos):** 20 cabeças e 56 pés. G + C = 20; 2G + 4C = 56 → 2C = 16 → **C = 8, G = 12**.

<a id="t12-geometricos"></a>

### Problemas geométricos (contagem de figuras)

- **Quadrados numa grade n × n:** 1² + 2² + … + n². Grade 3 × 3 → 9 + 4 + 1 = **14 quadrados**.
- **Retângulos numa grade m × n:** C(m + 1, 2) × C(n + 1, 2). Grade 2 × 3 → 3 × 6 = **18**.
- **Segmentos com n pontos alinhados:** C(n, 2). **Triângulos com n pontos (3 a 3 não alinhados):** C(n, 3).
- **Palitos/fósforos:** conte por linhas e colunas; um quadrado de lado n em grade usa 2n(n + 1) palitos.

<a id="t12-matrizes"></a>

### Matrizes

Uma matriz **m × n** tem m linhas e n colunas; **aᵢⱼ** é o elemento da linha i, coluna j.

> 📘 **Exemplo:** A = (aᵢⱼ)₂ₓ₂ com aᵢⱼ = 2i − j → a₁₁ = 1, a₁₂ = 0, a₂₁ = 3, a₂₂ = 2.
> A = [ 1 0 ; 3 2 ] · det A = 1 × 2 − 0 × 3 = **2**.

- **Tipos:** quadrada (m = n), identidade (1 na diagonal principal, 0 fora), nula, diagonal, **transposta** Aᵗ (troca linhas por colunas), simétrica (A = Aᵗ).
- **Soma:** só entre matrizes de **mesma ordem**, elemento a elemento.
- **Produto A × B:** existe se **nº de colunas de A = nº de linhas de B**; o resultado tem ordem (linhas de A) × (colunas de B). Cada elemento = linha de A "vezes" coluna de B. **Não é comutativo** (em geral AB ≠ BA).
- **Determinante 2 × 2:** ad − bc. **3 × 3:** regra de **Sarrus** (repete as duas primeiras colunas; soma os produtos das diagonais principais e subtrai os das secundárias).

**Propriedades do determinante (n = ordem)**

- det(Aᵗ) = det A · det(A × B) = det A × det B · **det(k × A) = kⁿ × det A**
- Linha/coluna de zeros, ou duas linhas iguais/proporcionais → det = 0.
- Trocar duas linhas de lugar → troca o sinal.
- A é **inversível** ⇔ det A ≠ 0; det(A⁻¹) = 1/det A.

> ⚠️ **Pegadinha:** se A é 3 × 3 e det A = 2, então det(2A) = 2³ × 2 = **16**, e não 4.

<a id="t12-quadros"></a>

### Quadros e matrizes de símbolos

São tabelas com números ou figuras em que **cada linha (ou coluna) segue a mesma regra** e falta um elemento. Teste: soma da linha constante, terceiro = primeiro op segundo, rotação da figura de célula em célula, quantidade de elementos aumentando, cada símbolo aparecendo uma vez por linha (tipo sudoku).

> 📘 **Exemplo:** linhas (2, 5, 7), (4, 3, 7), (6, 1, ?). Regra: 3º = 1º + 2º → **7**.

### Revisão rápida

<details><summary>Quantos quadrados há num tabuleiro 4 × 4?</summary>

16 + 9 + 4 + 1 = 30.
</details>

<details><summary>Certo ou errado: o produto de uma matriz 2 × 3 por uma 3 × 4 resulta numa matriz 2 × 4.</summary>

Certo.
</details>

<details><summary>Certo ou errado: o produto de matrizes é comutativo.</summary>

Errado. Em geral AB ≠ BA (às vezes BA nem existe).
</details>

<details><summary>Se A é 2 × 2 e det A = 5, quanto é det(3A)?</summary>

3² × 5 = 45.
</details>

<details><summary>A soma de dois números é 40 e um é o triplo do outro. Quais são?</summary>

x + 3x = 40 → x = 10 e 30.
</details>

<p align="right"><a href="#localizar-assunto">🔎 Localizar assunto</a> · <a href="#topo">⬆ Topo</a></p>

---

<a id="t13"></a>

## `13` Problemas de contagem e noções de probabilidade

> **Edital:** Problemas de contagem e noções de probabilidade.

<a id="t13-pfc"></a>

### Princípio fundamental da contagem (PFC)

Se uma decisão tem **a** opções e outra, independente, tem **b**, as duas juntas têm **a × b** possibilidades. Use **"e" → multiplica** e **"ou" (casos separados) → soma**.

> 📘 **Exemplo:** senhas de 4 dígitos **distintos**: 10 × 9 × 8 × 7 = **5.040**. Com repetição permitida: 10⁴ = 10.000.

> 💡 **Para memorizar:** **comece pela restrição**. Números pares de 3 algarismos distintos? Decida primeiro o último algarismo (par) e o primeiro (≠ 0), separando o caso em que o último é 0.

<a id="t13-agrupamentos"></a>

### Permutações, arranjos e combinações

| Tipo | A ordem importa? | Fórmula | Exemplo |
|---|---|---|---|
| Permutação simples | sim (usa todos) | **Pₙ = n!** | 5 pessoas em fila: 120 |
| Permutação com repetição | sim | **n! / (a! b! …)** | anagramas de BANANA: 6!/(3! 2!) = **60** |
| Permutação circular | sim (em roda) | **(n − 1)!** | 5 pessoas em mesa redonda: 4! = **24** |
| Arranjo | **sim** | **Aₙ,ₚ = n! / (n − p)!** | presidente e vice entre 10: 10 × 9 = 90 |
| Combinação | **não** | **Cₙ,ₚ = n! / [p! (n − p)!]** | comissão de 3 entre 5: **10** |

Fatoriais: 0! = 1, 1! = 1, 3! = 6, 4! = 24, 5! = 120, 6! = 720, 7! = 5.040.

> 💡 **Para memorizar:** **troque a ordem dos escolhidos**. Se mudou o resultado (cargos, posições, senha), é **arranjo**; se não mudou (comissão, grupo, salada de frutas), é **combinação**. E Cₙ,ₚ = Cₙ,ₙ₋ₚ.

> ⚠️ **Pegadinha:** "comissão de 3 com presidente, secretário e tesoureiro" é **arranjo** (cargos diferentes); "comissão de 3 membros" é **combinação**.

<a id="t13-pombos"></a>

### Princípio da casa dos pombos

Se **n + 1** objetos são distribuídos em **n** gavetas, alguma gaveta recebe **pelo menos 2**. Generalizando: com N objetos em n gavetas, alguma tem pelo menos ⌈N/n⌉.

> 📘 **Exemplo:** num grupo de 13 pessoas, ao menos 2 fazem aniversário no mesmo mês (13 pessoas, 12 meses).

<a id="t13-probabilidade"></a>

### Probabilidade

**P(A) = casos favoráveis / casos possíveis**, com resultados igualmente prováveis. Sempre **0 ≤ P(A) ≤ 1**.

- **Espaço amostral (Ω):** todos os resultados. Um dado: 6; dois dados: 36; três moedas: 8.
- **Complementar:** **P(não A) = 1 − P(A)**. Use quando a pergunta tem "**pelo menos um**".
- **União:** P(A ∪ B) = P(A) + P(B) − P(A ∩ B). Se **mutuamente exclusivos**, P(A ∩ B) = 0.

> 📘 **Exemplo:** dois dados, soma 7: (1,6), (2,5), (3,4), (4,3), (5,2), (6,1) → 6/36 = **1/6**.

> 📘 **Exemplo:** três moedas, pelo menos uma cara: 1 − P(nenhuma) = 1 − 1/8 = **7/8**.

<a id="t13-condicional"></a>

### Probabilidade condicional e eventos independentes

- **Condicional:** **P(A | B) = P(A ∩ B) / P(B)** — o espaço amostral **encolhe** para B.
- **Independentes:** P(A ∩ B) = P(A) × P(B). Ex.: lançamentos de moeda.
- **Sucessivos sem reposição:** multiplique, ajustando o total a cada retirada.
- **Binomial** (k sucessos em n tentativas independentes, cada uma com probabilidade p): C(n, k) × pᵏ × (1 − p)ⁿ⁻ᵏ.

> 📘 **Exemplo (sem reposição):** urna com 3 bolas vermelhas e 2 azuis; retiram-se 2 sem reposição. P(duas vermelhas) = 3/5 × 2/4 = **3/10**.

> 📘 **Exemplo (condicional):** lança-se um dado e sabe-se que saiu par. Probabilidade de ser maior que 3? Pares {2, 4, 6}; maiores que 3 entre eles {4, 6} → **2/3**.

> 📘 **Exemplo (binomial):** três moedas, exatamente 2 caras: C(3, 2) × (1/2)³ = **3/8**.

> ⚠️ **Pegadinha:** "mutuamente exclusivos" (não ocorrem juntos) ≠ "independentes" (um não afeta o outro). Dois eventos com probabilidade positiva que são mutuamente exclusivos **não** são independentes.

### Revisão rápida

<details><summary>Quantos anagramas tem a palavra AMOR?</summary>

4! = 24.
</details>

<details><summary>Certo ou errado: escolher 2 representantes de turma (sem cargos) entre 6 alunos é um arranjo.</summary>

Errado. Sem cargos, a ordem não importa: C(6, 2) = 15.
</details>

<details><summary>De quantas formas 6 pessoas sentam numa mesa circular?</summary>

5! = 120.
</details>

<details><summary>Qual a probabilidade de sair pelo menos um 6 em dois lançamentos de um dado?</summary>

1 − (5/6)² = 1 − 25/36 = 11/36.
</details>

<details><summary>Certo ou errado: P(A) + P(não A) = 1.</summary>

Certo.
</details>

<p align="right"><a href="#localizar-assunto">🔎 Localizar assunto</a> · <a href="#topo">⬆ Topo</a></p>

---

<a id="t14"></a>

## `14` Geometria básica

> **Edital:** Geometria básica: ângulos, triângulos, polígonos, distâncias, proporcionalidade, perímetro e área.

<a id="t14-angulos"></a>

### Ângulos

- **Classificação:** agudo (< 90°), reto (= 90°), obtuso (entre 90° e 180°), raso (180°).
- **Complementares:** somam **90°** · **Suplementares:** somam **180°** · **Replementares:** 360°.
- **Opostos pelo vértice:** são **iguais**.
- **Paralelas cortadas por uma transversal:** **correspondentes** e **alternos** (internos ou externos) são **iguais**; **colaterais** são **suplementares**.
- 1° = 60′ (minutos); 1′ = 60″ (segundos).

> 📘 **Exemplo:** o complemento de um ângulo é o triplo dele. x + 3x = 90° → **x = 22,5°** (22°30′).

<a id="t14-triangulos"></a>

### Triângulos

- **Soma dos ângulos internos: 180°.** Ângulo **externo** = soma dos dois internos **não adjacentes**.
- **Desigualdade triangular:** cada lado é **menor** que a soma dos outros dois. 3, 4 e 8 **não** formam triângulo.
- **Quanto aos lados:** equilátero (3 iguais, ângulos de 60°), isósceles (2 iguais; ângulos da base iguais), escaleno (todos diferentes).
- **Quanto aos ângulos:** acutângulo, retângulo, obtusângulo.
- **Pitágoras (triângulo retângulo):** **a² = b² + c²** (a = hipotenusa). Ternas: **3-4-5**, **5-12-13**, **8-15-17**, e os múltiplos (6-8-10, 9-12-15).
- **Equilátero de lado l:** altura **l√3/2**; área **l²√3/4**.
- **Ângulos notáveis (retângulo):** 30°–60°–90° têm lados na razão 1 : √3 : 2; 45°–45°–90°, 1 : 1 : √2.

> ⚠️ **Pegadinha:** o lado maior fica **oposto** ao maior ângulo. E Pitágoras só vale para triângulo **retângulo**.

<a id="t14-poligonos"></a>

### Polígonos

| Fórmula | Expressão |
|---|---|
| Soma dos ângulos internos | **Sᵢ = (n − 2) × 180°** |
| Soma dos ângulos externos | **360°** (qualquer polígono convexo) |
| Ângulo interno do regular | Sᵢ / n |
| Ângulo externo do regular | 360° / n |
| Número de diagonais | **d = n (n − 3) / 2** |

| Polígono | n | Sᵢ | Ângulo interno (regular) | Diagonais |
|---|:-:|:-:|:-:|:-:|
| Triângulo | 3 | 180° | 60° | 0 |
| Quadrilátero | 4 | 360° | 90° | 2 |
| Pentágono | 5 | 540° | 108° | 5 |
| Hexágono | 6 | 720° | 120° | 9 |
| Octógono | 8 | 1.080° | 135° | 20 |
| Decágono | 10 | 1.440° | 144° | 35 |

> 💡 **Para memorizar:** o **hexágono regular** é formado por **6 triângulos equiláteros**; seu lado é igual ao raio da circunferência circunscrita.

<a id="t14-areas"></a>

### Perímetro e área

**Perímetro** é a soma dos lados (o "contorno"). **Área** é a medida da superfície.

| Figura | Área | Perímetro |
|---|---|---|
| Quadrado (lado l) | l² | 4l |
| Retângulo | b × h | 2(b + h) |
| Triângulo | b × h / 2 | soma dos lados |
| Paralelogramo | b × h | soma dos lados |
| Trapézio | (B + b) × h / 2 | soma dos lados |
| Losango | D × d / 2 | 4l |
| Círculo (raio r) | **π r²** | **2 π r** (comprimento) |
| Setor circular (ângulo θ) | (θ/360°) × π r² | — |

Outras: diagonal do quadrado **l√2**; diagonal do retângulo √(b² + h²); triângulo com os três lados (Heron): √[p(p − a)(p − b)(p − c)], com p = semiperímetro.

> 📘 **Exemplo:** retângulo 8 × 6: área 48; perímetro 28; diagonal √(64 + 36) = **10**.

> ⚠️ **Pegadinha:** figuras com a **mesma área** podem ter **perímetros diferentes**, e vice-versa. Entre retângulos de mesmo perímetro, o de **maior área** é o **quadrado**.

<a id="t14-semelhanca"></a>

### Semelhança, Tales e proporcionalidade

- **Figuras semelhantes:** ângulos iguais e lados proporcionais. Razão de semelhança **k** → perímetros × k, **áreas × k²**, **volumes × k³**.
- **Teorema de Tales:** um feixe de **retas paralelas** cortado por duas transversais determina segmentos **proporcionais**.
- **Sombra:** objeto e sombra formam triângulos semelhantes → altura₁/sombra₁ = altura₂/sombra₂.

> 📘 **Exemplo:** um poste projeta sombra de 6 m quando uma pessoa de 1,80 m projeta 1,20 m. Altura do poste = 6 × 1,80/1,20 = **9 m**.

### Revisão rápida

<details><summary>Quanto mede cada ângulo interno de um pentágono regular?</summary>

540°/5 = 108°.
</details>

<details><summary>Certo ou errado: os lados 5, 7 e 13 formam um triângulo.</summary>

Errado. 5 + 7 = 12 < 13.
</details>

<details><summary>Quantas diagonais tem um polígono de 12 lados?</summary>

12 × 9/2 = 54.
</details>

<details><summary>Se o raio de um círculo dobra, o que acontece com a área?</summary>

Quadruplica (k² = 4).
</details>

<details><summary>Num triângulo retângulo, os catetos medem 9 e 12. Qual a hipotenusa?</summary>

15 (múltiplo da terna 3-4-5).
</details>

<p align="right"><a href="#localizar-assunto">🔎 Localizar assunto</a> · <a href="#topo">⬆ Topo</a></p>

---

<a id="t15"></a>

## `15` Plano cartesiano

> **Edital:** Plano cartesiano: sistema de coordenadas, distância.

<a id="t15-coordenadas"></a>

### Sistema de coordenadas

Dois eixos perpendiculares: **x (abscissas)**, horizontal, e **y (ordenadas)**, vertical, que se cruzam na **origem O (0, 0)**. Um ponto é o **par ordenado (x, y)** — a ordem importa: (2, 3) ≠ (3, 2).

| Quadrante | Sinais | Exemplo |
|---|---|---|
| 1º | (+, +) | (3, 2) |
| 2º | (−, +) | (−3, 2) |
| 3º | (−, −) | (−3, −2) |
| 4º | (+, −) | (3, −2) |

- Ponto no **eixo x** tem **y = 0**; no **eixo y** tem **x = 0**. Pontos sobre os eixos **não** pertencem a nenhum quadrante.
- **Bissetriz dos quadrantes ímpares (1º e 3º):** y = x. **Dos pares (2º e 4º):** y = −x.
- **Simetrias de P(a, b):** em relação ao eixo x → (a, −b); ao eixo y → (−a, b); à origem → (−a, −b).

> 💡 **Para memorizar:** os quadrantes são numerados no **sentido anti-horário**, começando pelo canto superior direito.

<a id="t15-distancia"></a>

### Distância e ponto médio

- **Distância entre A(x₁, y₁) e B(x₂, y₂):** **d = √[(x₂ − x₁)² + (y₂ − y₁)²]** — é Pitágoras com catetos Δx e Δy.
- **Distância à origem:** √(x² + y²).
- **Ponto médio:** M = ((x₁ + x₂)/2, (y₁ + y₂)/2).
- **Distância "em quadras" (táxi):** |Δx| + |Δy| — aparece em problemas de ruas em grade.

> 📘 **Exemplo:** A(1, 2) e B(4, 6): d = √(3² + 4²) = √25 = **5**; ponto médio = **(2,5; 4)**. Andando só pelas ruas da grade, seriam 3 + 4 = **7** quadras.

<a id="t15-retas"></a>

### Retas, alinhamento e área

- **Coeficiente angular (inclinação):** **m = Δy / Δx = (y₂ − y₁)/(x₂ − x₁)**. m > 0: crescente; m < 0: decrescente; m = 0: horizontal.
- **Equação reduzida:** **y = m x + n** (n = onde a reta corta o eixo y).
- **Paralelas:** mesmo m. **Perpendiculares:** m₁ × m₂ = −1.
- **Três pontos alinhados** ⇔ o determinante formado por (x, y, 1) de cada ponto é **zero**.
- **Área do triângulo** de vértices conhecidos = |D| / 2, sendo D esse determinante.

> 📘 **Exemplo:** triângulo de vértices (0, 0), (4, 0) e (0, 3): é retângulo, catetos 4 e 3 → área **6**; hipotenusa (distância entre (4, 0) e (0, 3)) = **5**.

### Revisão rápida

<details><summary>Em que quadrante está o ponto (−5, 3)?</summary>

2º quadrante (x negativo, y positivo).
</details>

<details><summary>Certo ou errado: o ponto (0, −4) pertence ao 4º quadrante.</summary>

Errado. Está sobre o eixo y, que não pertence a quadrante algum.
</details>

<details><summary>Qual a distância entre (−1, 1) e (5, 9)?</summary>

√(6² + 8²) = √100 = 10.
</details>

<details><summary>Qual o simétrico de (2, −7) em relação à origem?</summary>

(−2, 7).
</details>

<details><summary>Qual o coeficiente angular da reta que passa por (1, 2) e (3, 8)?</summary>

(8 − 2)/(3 − 1) = 3.
</details>

<p align="right"><a href="#localizar-assunto">🔎 Localizar assunto</a> · <a href="#topo">⬆ Topo</a></p>

---

<a id="t16"></a>

## `16` Problemas de lógica e raciocínio

> **Edital:** Problemas de lógica e raciocínio.

Item "guarda-chuva": junta tudo dos tópicos anteriores. O que mais ajuda aqui é ter um **método**.

<a id="t16-roteiro"></a>

### Roteiro de resolução

1. **Leia a pergunta primeiro** — saiba o que procurar.
2. **Separe dados e condições** (anote, desenhe, tabele).
3. **Identifique o tipo:** proposições? conjuntos? associação? contagem? sequência?
4. **Escolha a ferramenta:** tabela-verdade, diagrama, tabela de associação, PFC, equação.
5. **Teste as alternativas** quando o cálculo direto for longo — muitas vezes é mais rápido.
6. **Confira** a resposta no enunciado.

<a id="t16-estrategias"></a>

### Estratégias clássicas

- **Trabalhar de trás para frente:** quando se conhece o resultado final, desfaça as operações (inverta: + vira −, × vira ÷, "gastou metade" vira "× 2").
- **Supor e testar (hipótese):** ideal para verdades/mentiras e para "qual alternativa é possível".
- **Caso particular:** em questões com "qualquer número", teste um número simples (ex.: 100 em porcentagem).
- **Desenhar:** trajetos, posições, fila, diagrama.
- **Procurar invariantes e padrões:** o que não muda? o que se repete?

> 📘 **Exemplo (de trás para frente):** gastei metade do que tinha e mais R$ 10, e fiquei com R$ 30. Quanto tinha? Desfazendo: 30 + 10 = 40; 40 × 2 = **R$ 80**. (Conferindo: metade de 80 = 40, mais 10 = 50 gastos; sobram 30 ✓.)

> 📘 **Exemplo (caso particular):** um preço sobe 25%. Quanto deve cair para voltar ao original? Use 100 → 125. Para voltar a 100, cair 25 em 125 = **20%**.

<a id="t16-pior-caso"></a>

### Pior caso e garantias

Perguntas com "**para ter certeza**", "**no mínimo, para garantir**": imagine o **azar máximo** e some 1.

> 📘 **Exemplo:** uma gaveta tem 10 meias pretas e 10 brancas, no escuro. Quantas tirar para **garantir** um par da mesma cor? Pior caso: 1 preta + 1 branca → a 3ª forma par: **3 meias**.
> Para garantir **2 pretas**: pior caso tira todas as 10 brancas antes → 10 + 2 = **12 meias**.

> ⚠️ **Pegadinha:** "**garantir**" pede o pior caso; "**é possível**" pede o melhor caso. Na mesma gaveta, é **possível** conseguir 2 pretas tirando apenas 2 meias, mas só se **garante** com 12.

### Revisão rápida

<details><summary>Uma caixa tem bolas de 4 cores. Quantas tirar para garantir 2 da mesma cor?</summary>

5 (uma de cada cor + 1).
</details>

<details><summary>Pensei num número, multipliquei por 3, somei 7 e obtive 40. Qual era?</summary>

(40 − 7)/3 = 11.
</details>

<details><summary>Certo ou errado: para resolver um problema de "pelo menos um" em probabilidade, costuma ser mais rápido usar o complementar.</summary>

Certo. P(pelo menos um) = 1 − P(nenhum).
</details>

<p align="right"><a href="#localizar-assunto">🔎 Localizar assunto</a> · <a href="#topo">⬆ Topo</a></p>

---

<a id="formulario"></a>

## 📋 Formulário final

| Assunto | Fórmula / regra |
|---|---|
| Tabela-verdade | 2ⁿ linhas |
| Contrapositiva | p → q ≡ ~q → ~p |
| NeyMar | p → q ≡ ~p ∨ q |
| Negação do condicional | ~(p → q) ≡ p ∧ ~q |
| De Morgan | ~(p ∧ q) ≡ ~p ∨ ~q; ~(p ∨ q) ≡ ~p ∧ ~q |
| Negação de "Todo A é B" | Algum A não é B |
| Subconjuntos | 2ⁿ |
| União de 2 conjuntos | n(A) + n(B) − n(A ∩ B) |
| MDC × MMC | = a × b |
| Juros simples | J = C i t; M = C (1 + i t) |
| Juros compostos | M = C (1 + i)ᵗ |
| Aumento / desconto | × (1 + i) / × (1 − i) |
| Proporção | a × d = b × c |
| Volume ↔ capacidade | 1 dm³ = 1 L; 1 m³ = 1.000 L |
| Velocidade | km/h ÷ 3,6 = m/s |
| PA | aₙ = a₁ + (n − 1) r; Sₙ = (a₁ + aₙ) n / 2 |
| PG | aₙ = a₁ qⁿ⁻¹ |
| Relógio | ângulo = \|30H − 5,5M\| |
| Permutação / circular | n! / (n − 1)! |
| Arranjo | n! / (n − p)! |
| Combinação | n! / [p! (n − p)!] |
| Probabilidade | favoráveis / possíveis; P(não A) = 1 − P(A) |
| Condicional | P(A \| B) = P(A ∩ B) / P(B) |
| Ângulos internos | (n − 2) × 180° |
| Diagonais | n (n − 3) / 2 |
| Pitágoras | a² = b² + c² |
| Círculo | A = π r²; C = 2 π r |
| Trapézio / losango | (B + b) h / 2 / D d / 2 |
| Semelhança | áreas × k²; volumes × k³ |
| Distância entre pontos | √[(Δx)² + (Δy)²] |
| Coeficiente angular | m = Δy / Δx |
| Determinante 2 × 2 | ad − bc; det(kA) = kⁿ det A |

<p align="right"><a href="#localizar-assunto">🔎 Localizar assunto</a> · <a href="#topo">⬆ Topo</a></p>

---

<a id="indice-remissivo"></a>

## 🔤 Índice remissivo A–Z

**A** — [Afirmação do consequente](#t03-argumentos) · [Ângulos](#t14-angulos) · [Ângulo do relógio](#t10-temporal) · [Analogias](#t10-verbal) · [Ano bissexto](#t10-temporal) · [Are e hectare](#t08-area-volume) · [Argumento válido](#t03-argumentos) · [Arranjo](#t13-agrupamentos) · [Associação lógica](#t09-associacao) · [Aumentos sucessivos](#t06-sucessivos)

**B** — [Bicondicional](#t01-conectivos) · [Binomial](#t13-condicional) · [Bissetriz dos quadrantes](#t15-coordenadas)

**C** — [Casa dos pombos](#t13-pombos) · [Cavaleiros e valetes](#t09-verdades) · [Coeficiente angular](#t15-retas) · [Combinação](#t13-agrupamentos) · [Complementar (conjuntos)](#t04-operacoes) · [Condição necessária e suficiente](#t01-necessaria) · [Condicional](#t01-conectivos) · [Conectivos](#t01-conectivos) · [Conjunto das partes](#t04-nocoes) · [Conjuntos numéricos](#t04-numericos) · [Contingência](#t01-tautologia) · [Contradição](#t01-tautologia) · [Contrapositiva](#t02-equivalencias) · [Critérios de divisibilidade](#t05-divisibilidade)

**D** — [Dado (faces opostas)](#t10-espacial) · [De Morgan](#t02-demorgan) · [Determinante](#t12-matrizes) · [Diagonais de polígono](#t14-poligonos) · [Diagramas de Venn](#t04-venn) · [Diagramas lógicos](#t03-diagramas) · [Dias da semana](#t10-temporal) · [Disjunção exclusiva](#t01-conectivos) · [Distância entre pontos](#t15-distancia) · [Divisão proporcional](#t07-divisao) · [Dízimas periódicas](#t05-fracoes)

**E** — [Equivalências lógicas](#t02-equivalencias) · [Escala](#t08-velocidade) · [Espaço amostral](#t13-probabilidade) · [Eventos independentes](#t13-condicional)

**F** — [Falácias](#t03-argumentos) · [Fator multiplicativo](#t06-porcentagem) · [Fatorial](#t13-agrupamentos) · [Fibonacci](#t10-sequencial) · [Formação de conceitos](#t10-conceitos) · [Fração geratriz](#t05-fracoes) · [Frações](#t05-fracoes)

**G** — [Gráfico de setores](#t11-tipos) · [Gráficos e tabelas](#t11-tipos) · [Grandezas proporcionais](#t07-grandezas)

**H** — [Hexágono regular](#t14-poligonos) · [Histograma](#t11-tipos)

**I** — [Idades (problemas)](#t12-aritmeticos) · [Irracionais](#t04-numericos)

**J** — [Juros compostos](#t06-compostos) · [Juros simples](#t06-simples)

**L** — [Linguagem natural → lógica](#t02-linguagem)

**M** — [Matrizes](#t12-matrizes) · [Média, moda e mediana](#t11-medidas) · [MMC e MDC](#t05-divisibilidade) · [Modus ponens / tollens](#t03-argumentos)

**N** — [Negação do condicional](#t02-negacoes) · [Negação de quantificadores](#t03-quantificadores) · [NeyMar](#t02-equivalencias) · [Números primos](#t05-divisibilidade)

**O** — [Ordem das operações](#t05-operacoes) · [Ordenação / filas](#t09-ordenacao) · [Orientação espacial](#t10-espacial)

**P** — [PA e PG](#t10-sequencial) · [Perímetro e área](#t14-areas) · [Permutação](#t13-agrupamentos) · [Permutação circular](#t13-agrupamentos) · [Pior caso](#t16-pior-caso) · [Pitágoras](#t14-triangulos) · [Plano cartesiano](#t15-coordenadas) · [Polígonos](#t14-poligonos) · [Ponto médio](#t15-distancia) · [Pontos percentuais](#t06-sucessivos) · [Porcentagem](#t06-porcentagem) · [Potências](#t05-potencias) · [Predicados](#t03-predicados) · [Princípio fundamental da contagem](#t13-pfc) · [Probabilidade](#t13-probabilidade) · [Probabilidade condicional](#t13-condicional) · [Proposição](#t01-proposicoes)

**Q** — [Quadrantes](#t15-coordenadas) · [Quadrados numa grade](#t12-geometricos) · [Quadros de símbolos](#t12-quadros) · [Quantificadores](#t03-quantificadores)

**R** — [Raciocínio sequencial](#t10-sequencial) · [Raciocínio verbal](#t10-verbal) · [Razão e proporção](#t07-razao) · [Regra de três](#t07-regra) · [Retas](#t15-retas)

**S** — [Semelhança](#t14-semelhanca) · [Sequências cíclicas](#t10-sequencial) · [Silogismos](#t03-argumentos) · [Simetria de pontos](#t15-coordenadas) · [Sistema métrico](#t08-sistema)

**T** — [Tabela-verdade](#t01-tabela) · [Tales](#t14-semelhanca) · [Taxas equivalentes](#t06-taxas) · [Tautologia](#t01-tautologia) · [Tempo (sexagesimal)](#t08-tempo) · [Torneiras](#t12-aritmeticos) · [Trabalhar de trás para frente](#t16-estrategias) · [Triângulos](#t14-triangulos)

**U** — [União de conjuntos](#t04-venn)

**V** — [Velocidade](#t08-velocidade) · [Verdades e mentiras](#t09-verdades) · [Volume e capacidade](#t08-capacidade)

<p align="right"><a href="#localizar-assunto">🔎 Localizar assunto</a> · <a href="#topo">⬆ Topo</a></p>
