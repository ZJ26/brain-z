---
versão: 1.0
atualização: 12/06/2026
responsável_revisão: Marketing
status: vigente
---

# Sistema Tipográfico

> **Camada do sistema · Execução visual (tipografia).** Os estilos de texto da marca e suas regras. Traduz a leveza premium (teto de peso 500, tracking negativo nos tamanhos grandes) em hierarquia de leitura. Par com o Sistema de Cores.

---

# 01 · Display

**Função:** Hierarquia · Impacto máximo

### Preview

> Display hero

### O que é

Tipografia de maior impacto do sistema. Usada uma única vez por peça ou página, no momento de máximo destaque visual. Tamanho grande em peso Light com tracking apertado entrega autoridade premium com leveza.

### Por que vale ter

Cria o momento de impacto visual da composição. Sem um Display dedicado, você acaba forçando H1 a ser maior do que deveria, quebrando a hierarquia. Display dá liberdade para H1 cumprir seu papel real.

### Illustrator

| Propriedade | Valor        |
| ----------- | ------------ |
| Family      | Plus Jakarta |
| Style       | Light        |
| Size        | 60pt         |
| Tracking    | -50          |
| Leading     | 62pt         |
### Illustrator

| Propriedade | Valor        |
| ----------- | ------------ |
| Family      | Plus Jakarta |
| Style       | Light        |
| Size        | 60pt         |
| Tracking    | -50          |
| Leading     | 62pt         |

### CSS

```css
.text-display {
  font-family: 'Plus Jakarta Sans', sans-serif;
  font-weight: 300;
  font-size: 64px;
  line-height: 66px;
  letter-spacing: -2.9px;
}

@media (max-width: 1024px) {
  .text-display { font-size: 52px; line-height: 54px; letter-spacing: -2.35px; }
}
@media (max-width: 768px) {
  .text-display { font-size: 42px; line-height: 44px; letter-spacing: -1.9px; }
}
```

### Elementor · 3 breakpoints

| Propriedade | Mobile | Tablet | Desktop |
|---|---|---|---|
| Weight | 300 | 300 | 300 |
| Size | 42px | 52px | 64px |
| Line height | 44px | 54px | 66px |
| Letter spacing | -1.9px | -2.35px | -2.9px |

### Tamanhos por contexto (Illustrator)

| Contexto | Size / Leading |
|---|---|
| Post 1080×1080 | 108pt / 112pt |
| Story 1080×1920 | 124pt / 128pt |
| Banner 1920×1080 | 118pt / 122pt |
| Doc A4 | 60pt / 62pt |

> [!tip] Dica de aplicação
> Use Display **uma vez por peça ou página**. Quebre em 2 a 3 linhas para ganhar impacto vertical. Reserve para frases curtas de 3 a 6 palavras. Em peso Light, deixe o tamanho carregar a presença e o tracking apertado segurar a elegância. Evite acompanhar Display com outro título grande logo abaixo, deixe o momento respirar.

---

## 02 · Título (H1)

**Função:** Hierarquia · Principal

### Preview

> Título principal

### O que é

Título principal da peça ou página. Em sites equivale ao H1; em peças gráficas é o título dominante da composição. Peso 500 Medium com tracking negativo dá ao título o corpo necessário para se sustentar sozinho, contrastando com o Display em Light.

### Por que vale ter

É a base da hierarquia. Todo conteúdo precisa de um título principal: sem ele, a peça vira qualquer coisa. Define o assunto, dá entrada no conteúdo e prepara o leitor para o que vem depois. A relação Display em Light e H1 em Medium (grande e leve contra menor e encorpado) é um padrão premium reconhecido.

### Illustrator

| Propriedade | Valor |
|---|---|
| Family | Plus Jakarta |
| Style | Medium |
| Size | 34pt |
| Tracking | -30 |
| Leading | 38pt |

### CSS

```css
.text-titulo, h1 {
  font-family: 'Plus Jakarta Sans', sans-serif;
  font-weight: 500;
  font-size: 44px;
  line-height: 48px;
  letter-spacing: -1.6px;
}

@media (max-width: 1024px) {
  .text-titulo { font-size: 38px; line-height: 42px; letter-spacing: -1.35px; }
}
@media (max-width: 768px) {
  .text-titulo { font-size: 32px; line-height: 35px; letter-spacing: -1.1px; }
}
```

### Elementor · 3 breakpoints

| Propriedade | Mobile | Tablet | Desktop |
|---|---|---|---|
| Weight | 500 | 500 | 500 |
| Size | 32px | 38px | 44px |
| Line height | 35px | 42px | 48px |
| Letter spacing | -1.1px | -1.35px | -1.6px |

### Tamanhos por contexto (Illustrator)

| Contexto | Size / Leading |
|---|---|
| Post 1080×1080 | 74pt / 82pt |
| Story 1080×1920 | 84pt / 92pt |
| Banner 1920×1080 | 80pt / 88pt |
| Doc A4 | 34pt / 38pt |

> [!tip] Dica de aplicação
> Mantenha o Título **entre 5 e 8 palavras**. Se passar disso, considere quebrar em Título mais Subtítulo. Acompanhe sempre de um Subtítulo ou Body para dar contexto. Em peças gráficas, posicione na linha do terço superior para criar tensão visual.

---

## 03 · Título 2 (H2)

**Função:** Hierarquia · Seção

### Preview

> Título de seção

### O que é

Cabeçalho de seção dentro de uma página ou documento longo. Em sites equivale ao h2; em materiais impressos é o título que abre um bloco temático ainda relacionado ao H1 acima. Mesmo peso do H1 (500 Medium) em tamanho intermediário: cria quebra clara sem disputar com o título principal.

### Por que vale ter

Sem H2, conteúdo longo perde estrutura. O leitor não consegue navegar visualmente entre seções e o HTML fica semanticamente quebrado (importante para SEO e leitores de tela). H2 entrega a quebra natural que páginas institucionais, guias, propostas e materiais de método pedem, mantendo a hierarquia entre H1 (abertura única da peça) e Body (leitura).

### Illustrator

| Propriedade | Valor |
|---|---|
| Family | Plus Jakarta |
| Style | Medium |
| Size | 22pt |
| Tracking | -15 |
| Leading | 28pt |

### CSS

```css
.text-titulo-2, h2 {
  font-family: 'Plus Jakarta Sans', sans-serif;
  font-weight: 500;
  font-size: 30px;
  line-height: 36px;
  letter-spacing: -0.8px;
}

@media (max-width: 1024px) {
  .text-titulo-2 { font-size: 27px; line-height: 33px; letter-spacing: -0.65px; }
}
@media (max-width: 768px) {
  .text-titulo-2 { font-size: 24px; line-height: 30px; letter-spacing: -0.5px; }
}
```

### Elementor · 3 breakpoints

| Propriedade | Mobile | Tablet | Desktop |
|---|---|---|---|
| Weight | 500 | 500 | 500 |
| Size | 24px | 27px | 30px |
| Line height | 30px | 33px | 36px |
| Letter spacing | -0.5px | -0.65px | -0.8px |

### Tamanhos por contexto (Illustrator)

| Contexto | Size / Leading |
|---|---|
| Post 1080×1080 | 50pt / 58pt |
| Story 1080×1920 | 56pt / 64pt |
| Banner 1920×1080 | 54pt / 62pt |
| Doc A4 | 22pt / 28pt |

> [!tip] Dica de aplicação
> H2 só aparece em conteúdo longo (páginas institucionais com várias seções, documentos, artigos, guias). Em peças curtas como post, banner, hero ou capa, Display e H1 já carregam toda a hierarquia: não force um H2 que não precisa existir. Mantenha entre 4 e 8 palavras, sentence case, e dê respiro vertical generoso acima (50 a 80 % do tamanho do H2) para marcar a quebra de seção.

---

## 04 · Título 3 (H3)

**Função:** Hierarquia · Subseção

### Preview

> Título de subseção

### O que é

Cabeçalho de subseção dentro de uma seção aberta por H2. Em sites equivale ao h3; em documentos é o tópico interno do bloco. Mesmo peso do H1 e do H2 (500 Medium) em tamanho menor, com tracking quase neutro.

### Por que vale ter

Dentro de uma seção de H2 longa, o leitor precisa de granularidade fina. H3 cria essa quebra sem chegar perto da carga visual de H2. Em conteúdo técnico (documentação, guias passo-a-passo, FAQ), H3 é o ponto de entrada natural para listas, tabelas e blocos específicos.

### Illustrator

| Propriedade | Valor |
|---|---|
| Family | Plus Jakarta |
| Style | Medium |
| Size | 16pt |
| Tracking | -8 |
| Leading | 22pt |

### CSS

```css
.text-titulo-3, h3 {
  font-family: 'Plus Jakarta Sans', sans-serif;
  font-weight: 500;
  font-size: 22px;
  line-height: 30px;
  letter-spacing: -0.4px;
}

@media (max-width: 1024px) {
  .text-titulo-3 { font-size: 20px; line-height: 28px; letter-spacing: -0.32px; }
}
@media (max-width: 768px) {
  .text-titulo-3 { font-size: 19px; line-height: 26px; letter-spacing: -0.25px; }
}
```

### Elementor · 3 breakpoints

| Propriedade | Mobile | Tablet | Desktop |
|---|---|---|---|
| Weight | 500 | 500 | 500 |
| Size | 19px | 20px | 22px |
| Line height | 26px | 28px | 30px |
| Letter spacing | -0.25px | -0.32px | -0.4px |

### Tamanhos por contexto (Illustrator)

| Contexto | Size / Leading |
|---|---|
| Post 1080×1080 | 38pt / 50pt |
| Story 1080×1920 | 42pt / 54pt |
| Banner 1920×1080 | 40pt / 52pt |
| Doc A4 | 16pt / 22pt |

> [!tip] Dica de aplicação
> H3 só aparece se já houver H2 ativo na seção: nunca pule do H1 direto para H3 (quebra a semântica HTML). Use H3 para abrir subseções dentro de uma seção de H2 longa, ou para encabeçar listas, FAQs e tabelas. Em peças curtas, evite H3 inteiramente. Mantenha entre 3 e 6 palavras, sentence case.

---

## 05 · Subtítulo

**Função:** Descritor · Deck editorial

### Preview

> Subtítulo que acompanha o título principal e adiciona contexto editorial sem competir.

### O que é

Deck editorial que aparece logo abaixo de um Display ou H1 para expandir a ideia do título. Não é cabeçalho de seção (essa função é do H2 e do H3): Subtítulo descreve, não estrutura. Peso 300 Light com leading generoso cria contraste de hierarquia sem competir com o título acima.

### Por que vale ter

Permite expandir a ideia do título sem fazer o título crescer. Marcas premium usam quase sempre Título mais Subtítulo no hero da peça. Sem Subtítulo, o Título precisa carregar tudo sozinho. Para abrir nova seção dentro do conteúdo, use H2: misturar Subtítulo com cabeçalhos de seção quebra a hierarquia.

### Illustrator

| Propriedade | Valor |
|---|---|
| Family | Plus Jakarta |
| Style | Light |
| Size | 14pt |
| Tracking | -12 |
| Leading | 22pt |

### CSS

```css
.text-subtitulo {
  font-family: 'Plus Jakarta Sans', sans-serif;
  font-weight: 300;
  font-size: 19px;
  line-height: 30px;
  letter-spacing: -0.3px;
}

@media (max-width: 1024px) {
  .text-subtitulo { font-size: 17px; line-height: 27px; letter-spacing: -0.2px; }
}
@media (max-width: 768px) {
  .text-subtitulo { font-size: 16px; line-height: 26px; letter-spacing: -0.15px; }
}
```

### Elementor · 3 breakpoints

| Propriedade | Mobile | Tablet | Desktop |
|---|---|---|---|
| Weight | 300 | 300 | 300 |
| Size | 16px | 17px | 19px |
| Line height | 26px | 27px | 30px |
| Letter spacing | -0.15px | -0.2px | -0.3px |

### Tamanhos por contexto (Illustrator)

| Contexto | Size / Leading |
|---|---|
| Post 1080×1080 | 32pt / 50pt |
| Story 1080×1920 | 38pt / 59pt |
| Banner 1920×1080 | 36pt / 56pt |
| Doc A4 | 14pt / 22pt |

> [!tip] Dica de aplicação
> Espaçamento entre Título e Subtítulo: **metade do tamanho do Título**. Use Subtítulo para uma ideia complementar, não repita o título. Mantenha entre 10 e 20 palavras: se passar, virou Body.

---

## 06 · Texto (Body)

**Função:** Hierarquia · Corpo

### Preview

> Texto padrão para parágrafos do site e descrições de peças. O peso 400 e o line-height generoso garantem leitura confortável em qualquer dispositivo. Esta é a base da comunicação escrita do sistema.

### O que é

Estilo base para corpo de texto, parágrafos e descrições. Peso 400 Regular com line-height generoso (1.75) para conforto de leitura. É o estilo mais usado do sistema, cerca de 70% do conteúdo textual.

### Por que vale ter

Toda a leitura prolongada depende deste estilo. Sem calibragem correta de tamanho e line-height, o leitor cansa rapidamente. 16px com 28px de line-height é o padrão de leitura web confortável, com um respiro a mais que reforça a calma premium.

### Illustrator

| Propriedade | Valor |
|---|---|
| Family | Plus Jakarta |
| Style | Regular |
| Size | 11pt |
| Tracking | 0 |
| Leading | 19pt |

### CSS

```css
.text-corpo, body, p {
  font-family: 'Plus Jakarta Sans', sans-serif;
  font-weight: 400;
  font-size: 16px;
  line-height: 28px;
  letter-spacing: 0;
}
```

### Elementor · 3 breakpoints

| Propriedade | Mobile | Tablet | Desktop |
|---|---|---|---|
| Weight | 400 | 400 | 400 |
| Size | 16px | 16px | 16px |
| Line height | 28px | 28px | 28px |
| Letter spacing | 0 | 0 | 0 |

> [!warning] Body sempre 16px
> Mantém 16px em todos os breakpoints para acessibilidade. Abaixo disso, iOS Safari força zoom automático ao focar inputs.

### Tamanhos por contexto (Illustrator)

| Contexto | Size / Leading |
|---|---|
| Post 1080×1080 | 22pt / 38pt |
| Story 1080×1920 | 26pt / 45pt |
| Banner 1920×1080 | 24pt / 42pt |
| Doc A4 | 11pt / 19pt |

> [!tip] Dica de aplicação
> Mantenha **50 a 70 caracteres por linha** para conforto de leitura. Em sites, isso geralmente é uma largura de 600 a 700px. Em peças gráficas, mantenha parágrafos curtos, no máximo 3 a 4 linhas, para não cansar.

---

## 07 · Overline

**Função:** Marcador · Eyebrow

### Preview

> **MANIFESTO · MARCADOR DE SEÇÃO** (em UPPERCASE com tracking aberto)

### O que é

Pequeno marcador acima de um título principal. UPPERCASE com tracking aberto. Tem função de etiqueta: diz ao leitor "isto é tal tipo de conteúdo" antes mesmo de ele ler o título.

### Por que vale ter

É o elemento que mais comunica design pensado em uma peça. Marcas premium usam overlines em quase todas as composições hero. Custa pouquíssimo espaço e adiciona muito refinamento visual.

### Illustrator

| Propriedade | Valor |
|---|---|
| Family | Plus Jakarta |
| Style | Medium |
| Size | 8pt |
| Tracking | +200 |
| Leading | 12pt |
| Caps | All caps |

### CSS

```css
.text-overline {
  font-family: 'Plus Jakarta Sans', sans-serif;
  font-weight: 500;
  font-size: 11px;
  line-height: 16px;
  letter-spacing: 2.4px;
  text-transform: uppercase;
}
```

### Elementor · 3 breakpoints

| Propriedade | Mobile | Tablet | Desktop |
|---|---|---|---|
| Weight | 500 | 500 | 500 |
| Size | 11px | 11px | 11px |
| Line height | 16px | 16px | 16px |
| Letter spacing | 2.4px | 2.4px | 2.4px |

### Tamanhos por contexto (Illustrator)

| Contexto | Size / Leading |
|---|---|
| Post 1080×1080 | 14pt / 22pt |
| Story 1080×1920 | 16pt / 25pt |
| Banner 1920×1080 | 15pt / 23pt |
| Doc A4 | 8pt / 12pt |

> [!tip] Dica de aplicação
> Use Overline **sempre em UPPERCASE com tracking aberto**, é a identidade do estilo. Posicione 12 a 16px acima do título. Mantenha curto, de 1 a 4 palavras. O tracking generoso (2.4px) é o que dá ar premium à caixa alta.

---

## 08 · Caption

**Função:** Auxiliar · Legenda

### Preview

> Legenda da imagem · Fonte: dados internos Avanti · Atualizado em 2026

### O que é

Texto pequeno para créditos, fontes de dados, disclaimers curtos, datas e legendas. Peso 300 Light. É o texto miúdo do sistema, mas com personalidade definida.

### Por que vale ter

Toda peça profissional tem informações secundárias. Sem um estilo Caption definido, você fica reduzindo o Body e perdendo identidade. Caption tem peso e tamanho próprios que comunicam secundário automaticamente.

### Illustrator

| Propriedade | Valor |
|---|---|
| Family | Plus Jakarta |
| Style | Light |
| Size | 9pt |
| Tracking | +12 |
| Leading | 14pt |

### CSS

```css
.text-caption {
  font-family: 'Plus Jakarta Sans', sans-serif;
  font-weight: 300;
  font-size: 13px;
  line-height: 20px;
  letter-spacing: 0.2px;
}
```

### Elementor · 3 breakpoints

| Propriedade | Mobile | Tablet | Desktop |
|---|---|---|---|
| Weight | 300 | 300 | 300 |
| Size | 13px | 13px | 13px |
| Line height | 20px | 20px | 20px |
| Letter spacing | 0.2px | 0.2px | 0.2px |

### Tamanhos por contexto (Illustrator)

| Contexto | Size / Leading |
|---|---|
| Post 1080×1080 | 16pt / 25pt |
| Story 1080×1920 | 19pt / 30pt |
| Banner 1920×1080 | 17pt / 27pt |
| Doc A4 | 9pt / 14pt |

> [!tip] Dica de aplicação
> Use para datas, fontes e créditos. Em peças com imagens, posicione a caption 8 a 12px abaixo da foto. O peso Light é parte da identidade do estilo: não engorde a caption ou ela compete com o Body.

---

## 09 · Label

**Função:** Marcador · Tag

### Preview

> `[ HOME EQUITY ]`: badge pill em UPPERCASE com tracking aberto

### O que é

Pequenos badges para categorias, status e marcadores temáticos. Diferente do Overline porque é mais pontual e vive dentro de uma pílula com pill 100px.

### Por que vale ter

Sistemas com muitas categorias precisam diferenciar visualmente. Sem Label, você usa Overline para tudo e perde granularidade. Label é mais ativo que o Overline: chama atenção pontual.

### Illustrator

| Propriedade | Valor |
|---|---|
| Family | Plus Jakarta |
| Style | Medium |
| Size | 7pt |
| Tracking | +90 |
| Leading | 10pt |
| Caps | All caps |

### CSS

```css
.text-label {
  display: inline-block;
  font-family: 'Plus Jakarta Sans', sans-serif;
  font-weight: 500;
  font-size: 10px;
  line-height: 14px;
  letter-spacing: 1px;
  text-transform: uppercase;
  padding: 4px 12px;
  border-radius: 100px;
}
```

### Elementor · 3 breakpoints

| Propriedade | Mobile | Tablet | Desktop |
|---|---|---|---|
| Weight | 500 | 500 | 500 |
| Size | 10px | 10px | 10px |
| Line height | 14px | 14px | 14px |
| Letter spacing | 1px | 1px | 1px |
| Border radius | 100px | 100px | 100px |

### Tamanhos por contexto (Illustrator)

| Contexto | Size / Leading |
|---|---|
| Post 1080×1080 | 14pt / 20pt |
| Story 1080×1920 | 16pt / 22pt |
| Banner 1920×1080 | 15pt / 21pt |
| Doc A4 | 7pt / 10pt |

> [!tip] Dica de aplicação
> Label agora respeita o teto de peso 500 do sistema. Para garantir legibilidade no tamanho pequeno, compensa com tracking aberto (1px) em vez de peso pesado. Sempre dentro de pílula com pill 100px. Padding: 4px vertical, 12px horizontal.

---

## 10 · Footnote

**Função:** Auxiliar · Disclaimer

### Preview

> * Operações sujeitas a análise e aprovação das instituições parceiras. Condições variam conforme o cenário de cada caso.

### O que é

Texto legal, disclaimers, termos em letras pequenas, asteriscos explicativos e notas de rodapé. O menor texto do sistema. Peso 300 Light, discreto por definição.

### Por que vale ter

Operações de crédito têm informações obrigatórias e ressalvas que precisam aparecer sem roubar a cena. Sem um estilo Footnote definido, o disclaimer fica grande demais ou ilegível demais. Footnote resolve com tamanho e peso próprios.

### Illustrator

| Propriedade | Valor |
|---|---|
| Family | Plus Jakarta |
| Style | Light |
| Size | 8pt |
| Tracking | +8 |
| Leading | 12pt |

### CSS

```css
.text-footnote {
  font-family: 'Plus Jakarta Sans', sans-serif;
  font-weight: 300;
  font-size: 11px;
  line-height: 16px;
  letter-spacing: 0.1px;
}
```

### Elementor · 3 breakpoints

| Propriedade | Mobile | Tablet | Desktop |
|---|---|---|---|
| Weight | 300 | 300 | 300 |
| Size | 11px | 11px | 11px |
| Line height | 16px | 16px | 16px |
| Letter spacing | 0.1px | 0.1px | 0.1px |

### Tamanhos por contexto (Illustrator)

| Contexto | Size / Leading |
|---|---|
| Post 1080×1080 | 13pt / 19pt |
| Story 1080×1920 | 15pt / 22pt |
| Banner 1920×1080 | 14pt / 20pt |
| Doc A4 | 8pt / 12pt |

> [!tip] Dica de aplicação
> Use para ressalvas obrigatórias e condições de operação. Mantenha legível mesmo no menor tamanho: 11px é o piso. Disclaimer ilegível não cumpre função e ainda passa impressão de letra miúda escondendo algo, o oposto da transparência da marca.

---

## 11 · Quote

**Função:** Especialista · Citação

### Preview

> *"Resolveram em trinta dias o que meu banco recusou em anos."* (italic, peso 300)

### O que é

Citação em destaque, frase de manifesto, depoimento de cliente, frase de impacto. Itálico em peso 300 cria a voz humana, uma pausa editorial diferente do corpo do texto. Tamanho médio entre Body e Título.

### Por que vale ter

Citações precisam de tratamento visual diferente do texto comum. Sem Quote, depoimentos ficam idênticos ao Body e perdem força. Itálico Light em tamanho médio é o padrão editorial clássico, e é o gesto que mais aproxima o sistema do registro humano do Cuidador.

### Illustrator

| Propriedade | Valor |
|---|---|
| Family | Plus Jakarta |
| Style | Light Italic |
| Size | 18pt |
| Tracking | -15 |
| Leading | 24pt |

### CSS

```css
.text-quote, blockquote {
  font-family: 'Plus Jakarta Sans', sans-serif;
  font-weight: 300;
  font-style: italic;
  font-size: 26px;
  line-height: 34px;
  letter-spacing: -0.4px;
}

@media (max-width: 1024px) {
  .text-quote { font-size: 22px; line-height: 29px; letter-spacing: -0.3px; }
}
@media (max-width: 768px) {
  .text-quote { font-size: 19px; line-height: 26px; letter-spacing: -0.25px; }
}
```

### Elementor · 3 breakpoints

| Propriedade | Mobile | Tablet | Desktop |
|---|---|---|---|
| Weight | 300 Italic | 300 Italic | 300 Italic |
| Size | 19px | 22px | 26px |
| Line height | 26px | 29px | 34px |
| Letter spacing | -0.25px | -0.3px | -0.4px |

### Tamanhos por contexto (Illustrator)

| Contexto | Size / Leading |
|---|---|
| Post 1080×1080 | 36pt / 47pt |
| Story 1080×1920 | 42pt / 55pt |
| Banner 1920×1080 | 40pt / 52pt |
| Doc A4 | 18pt / 24pt |

> [!tip] Dica de aplicação
> Use aspas tipográficas grandes antes e depois da citação, em tamanho 1.5x maior, com opacidade reduzida. Após a citação, atribua o autor em Caption. Para respeitar a discrição da marca, prefira atribuição discreta (perfil e região) a nome completo e cargo. Mantenha citações curtas, até 25 palavras.

---

## 12 · Stat

**Função:** Especialista · Número

### Preview

> # R$ 500mi+
> **VOLUME ESTRUTURADO** (overline)

### O que é

Números grandes de destaque para apresentações, peças de resultado e provas de autoridade. Peso 400 Regular com tracking muito apertado cria densidade e solidez sem recorrer a peso pesado.

### Por que vale ter

Números costumam ser o argumento principal de uma peça comercial. Sem Stat dedicado, ficam com peso de Body e perdem impacto. Na v2, o Stat troca o antigo peso 600 por Regular em tamanho grande com tracking apertado: o resultado é mais premium e respeita o teto de peso do sistema.

### Illustrator

| Propriedade | Valor |
|---|---|
| Family | Plus Jakarta |
| Style | Regular |
| Size | 48pt |
| Tracking | -55 |
| Leading | 48pt |

### CSS

```css
.text-stat {
  font-family: 'Plus Jakarta Sans', sans-serif;
  font-weight: 400;
  font-size: 64px;
  line-height: 64px;
  letter-spacing: -3.2px;
}

@media (max-width: 1024px) {
  .text-stat { font-size: 54px; line-height: 54px; letter-spacing: -2.7px; }
}
@media (max-width: 768px) {
  .text-stat { font-size: 42px; line-height: 42px; letter-spacing: -2.1px; }
}
```

### Elementor · 3 breakpoints

| Propriedade | Mobile | Tablet | Desktop |
|---|---|---|---|
| Weight | 400 | 400 | 400 |
| Size | 42px | 54px | 64px |
| Line height | 42px | 54px | 64px |
| Letter spacing | -2.1px | -2.7px | -3.2px |

### Tamanhos por contexto (Illustrator)

| Contexto | Size / Leading |
|---|---|
| Post 1080×1080 | 110pt / 110pt |
| Story 1080×1920 | 130pt / 130pt |
| Banner 1920×1080 | 120pt / 120pt |
| Doc A4 | 48pt / 48pt |

> [!tip] Dica de aplicação
> Sempre acompanhe o número de um Overline explicando o que ele é. Em peças com vários stats, alinhe pela linha de base. O tracking muito apertado (-3.2px) é o que faz um número em peso Regular parecer sólido e caro, sem precisar de Bold.

---

## 13 · List

**Função:** Especialista · Lista

### Preview

> - Leitura de cenário antes da taxa
> - Acesso a uma rede de instituições parceiras
> - Condução do início ao fim, sem repasse

### O que é

Itens de lista em apresentações, descrições de diferenciais e comparativos. Mesmas propriedades do Body, mas com line-height maior (1.85 em vez de 1.75) para criar respiro entre itens.

### Por que vale ter

Listas precisam de leading maior que parágrafos para legibilidade. Sem isso, itens se confundem visualmente. Em materiais de método e diferenciais, esse estilo aparece o tempo todo.

### Illustrator

| Propriedade | Valor |
|---|---|
| Family | Plus Jakarta |
| Style | Regular |
| Size | 11pt |
| Tracking | 0 |
| Leading | 21pt |

### CSS

```css
.text-list, ul, ol {
  font-family: 'Plus Jakarta Sans', sans-serif;
  font-weight: 400;
  font-size: 16px;
  line-height: 30px;
  padding-left: 14px;
}

@media (max-width: 1024px) {
  .text-list { font-size: 16px; line-height: 30px; letter-spacing: 0; }
}
@media (max-width: 768px) {
  .text-list { font-size: 16px; line-height: 28px; letter-spacing: 0; }
}
```

### Elementor · 3 breakpoints

| Propriedade | Mobile | Tablet | Desktop |
|---|---|---|---|
| Weight | 400 | 400 | 400 |
| Size | 16px | 16px | 16px |
| Line height | 28px | 30px | 30px |
| Letter spacing | 0 | 0 | 0 |

### Tamanhos por contexto (Illustrator)

| Contexto | Size / Leading |
|---|---|
| Post 1080×1080 | 22pt / 41pt |
| Story 1080×1920 | 26pt / 48pt |
| Banner 1920×1080 | 24pt / 44pt |
| Doc A4 | 11pt / 21pt |

> [!tip] Dica de aplicação
> Use marcadores **discretos e elegantes**: bullet (•) ou ícones pequenos. Espaçamento entre marcador e texto: 0.8x o tamanho da fonte. Evite numeração tradicional (1, 2, 3) quando a ordem não importar.

---

## 14 · Button

**Função:** Especialista · CTA (sempre pill)

### Preview

> `[ Conversar com um especialista ]`: botão primário pill
> `[ Conhecer o método ]`: botão secundário pill outline

### O que é

Texto dentro de botões, calls-to-action e links visíveis. Peso 500 com tracking levemente aberto cria personalidade própria de botão, diferente de texto comum e de título.

### Por que vale ter

CTAs precisam de tratamento específico. Sem Button dedicado, botões herdam estilo de Body e perdem identidade. Em interfaces premium, o botão é convite educado: peso médio, não pesado, tracking sutil.

### Illustrator

| Propriedade | Valor |
|---|---|
| Family | Plus Jakarta |
| Style | Medium |
| Size | 10pt |
| Tracking | +20 |
| Leading | 14pt |

### CSS

```css
.text-button, button, .btn {
  font-family: 'Plus Jakarta Sans', sans-serif;
  font-weight: 500;
  font-size: 14px;
  line-height: 20px;
  letter-spacing: 0.3px;
  padding: 14px 28px;
  border-radius: 100px; /* pill obrigatório */
  cursor: pointer;
}
```

### Elementor · 3 breakpoints

| Propriedade | Mobile | Tablet | Desktop |
|---|---|---|---|
| Weight | 500 | 500 | 500 |
| Size | 14px | 14px | 14px |
| Line height | 20px | 20px | 20px |
| Letter spacing | 0.3px | 0.3px | 0.3px |
| Border radius | 100px | 100px | 100px |

> [!warning] Pill obrigatório
> **Border-radius 100px sempre.** Todos os botões do sistema têm cantos completamente arredondados nas laterais (formato cápsula). Não use border-radius menor, quebra a identidade visual.

### Tamanhos por contexto (Illustrator)

| Contexto | Size / Leading |
|---|---|
| Post 1080×1080 | 22pt / 31pt |
| Story 1080×1920 | 26pt / 36pt |
| Banner 1920×1080 | 24pt / 34pt |
| Doc A4 | 10pt / 14pt |

> [!tip] Dica de aplicação
> Padding sugerido: **1.2x tamanho da fonte vertical, 2.5x horizontal**. Para fonte 14px, padding 14px por 28px. Use peso 500, nunca 600 ou mais. Sentence case sempre: Title Case em botão grita performance marketing.

---

## 15 · Lead-in (Abertura)

**Função:** Editorial · Parágrafo de abertura

### Preview

> Há patrimônio que o mercado enxerga apenas como garantia. A Avanti enxerga como possibilidade.

### O que é

Primeiro parágrafo de um texto longo. Maior que o Body e em peso Light, convida à leitura e marca a entrada do conteúdo. Não é cabeçalho (essa função é do H2 e do H3) nem subtítulo de título (essa é do Subtítulo); é o parágrafo de abertura que dá o tom editorial antes de o Body assumir.

### Por que vale ter

Texto longo que começa direto no Body perde a entrada editorial das publicações premium. O Lead-in cria a transição entre título e corpo, sinaliza onde a leitura começa e dá ao conteúdo um ar de revista cuidada. Usado uma vez por texto, na abertura.

### Illustrator

| Propriedade | Valor |
|---|---|
| Family | Plus Jakarta |
| Style | Light |
| Size | 22pt |
| Tracking | -10 |
| Leading | 34pt |

### CSS

```css
.text-leadin {
  font-family: 'Plus Jakarta Sans', sans-serif;
  font-weight: 300;
  font-size: 22px;
  line-height: 34px;
  letter-spacing: -0.4px;
}

@media (max-width: 1024px) {
  .text-leadin { font-size: 20px; line-height: 31px; letter-spacing: -0.34px; }
}
@media (max-width: 768px) {
  .text-leadin { font-size: 18px; line-height: 28px; letter-spacing: -0.28px; }
}
```

### Elementor · 3 breakpoints

| Propriedade | Mobile | Tablet | Desktop |
|---|---|---|---|
| Weight | 300 | 300 | 300 |
| Size | 18px | 20px | 22px |
| Line height | 28px | 31px | 34px |
| Letter spacing | -0.28px | -0.34px | -0.4px |

### Tamanhos por contexto (Illustrator)

| Contexto | Size / Leading |
|---|---|
| Post 1080×1080 | 30pt / 46pt |
| Story 1080×1920 | 34pt / 52pt |
| Banner 1920×1080 | 32pt / 49pt |
| Doc A4 | 15pt / 24pt |

> [!tip] Dica de aplicação
> Use **uma vez por texto**, na abertura. Reserve para 1 a 3 frases. Em peso Light com leading generoso, ele contrasta com o Body sem competir com o título. Depois do Lead-in, o texto segue em Body. Não empilhe dois Lead-in nem use no meio do texto.

---

## 16 · Pull quote (Destaque editorial)

**Função:** Editorial · Frase destacada do texto

### Preview

> O premium está no trabalho, não na pose.

### O que é

Frase do próprio texto puxada para destaque grande no meio do conteúdo. Diferente do Quote (estilo 11), que é voz de terceiro (depoimento de cliente em itálico): o Pull quote é a própria voz do texto, em peso Light e tamanho grande, criando respiro e ritmo na leitura longa.

### Por que vale ter

Texto longo precisa de pausa visual e de pontos de destaque. Sem Pull quote, a única forma de enfatizar é o negrito no corpo, que é menos elegante e mais pesado. O Pull quote cria o respiro das publicações editoriais premium e guia o olho pelos pontos-chave. É espaço em branco trabalhando a favor da hierarquia.

### Illustrator

| Propriedade | Valor |
|---|---|
| Family | Plus Jakarta |
| Style | Light |
| Size | 34pt |
| Tracking | -20 |
| Leading | 42pt |

### CSS

```css
.text-pullquote {
  font-family: 'Plus Jakarta Sans', sans-serif;
  font-weight: 300;
  font-size: 34px;
  line-height: 42px;
  letter-spacing: -1.2px;
}

@media (max-width: 1024px) {
  .text-pullquote { font-size: 28px; line-height: 35px; letter-spacing: -0.95px; }
}
@media (max-width: 768px) {
  .text-pullquote { font-size: 24px; line-height: 31px; letter-spacing: -0.8px; }
}
```

### Elementor · 3 breakpoints

| Propriedade | Mobile | Tablet | Desktop |
|---|---|---|---|
| Weight | 300 | 300 | 300 |
| Size | 24px | 28px | 34px |
| Line height | 31px | 35px | 42px |
| Letter spacing | -0.8px | -0.95px | -1.2px |

### Tamanhos por contexto (Illustrator)

| Contexto | Size / Leading |
|---|---|
| Post 1080×1080 | 58pt / 70pt |
| Story 1080×1920 | 66pt / 80pt |
| Banner 1920×1080 | 62pt / 76pt |
| Doc A4 | 30pt / 38pt |

> [!tip] Dica de aplicação
> Puxe uma frase curta **do próprio texto**, não uma frase nova. Reserve para 4 a 12 palavras. Cerque de espaço em branco generoso, o respiro é metade do efeito. Não use itálico (isso é do Quote, estilo 11): o Pull quote é a voz do texto, não de um terceiro. No máximo um ou dois por texto longo.

---

## Showcase · Estilos aplicados

> [!example] Composição editorial completa
> Demonstração visual do sistema tipográfico em uma composição editorial da Avanti. Cada elemento textual corresponde a um dos estilos do sistema.

### Composição completa

**OVERLINE**
MANIFESTO

**DISPLAY linha 1** (peso 300 Light)
Seu imóvel pode financiar

**DISPLAY linha 2** (peso 300 Light)
o próximo passo.

**SUBTÍTULO** (peso 300)
A Avanti desenha cada operação caso a caso, com acesso a uma rede de instituições financeiras parceiras, e transforma patrimônio em capital com o imóvel permanecendo no seu nome.

**BUTTON primário pill**
`[ Conversar com um especialista ]`

**BUTTON secundário outline pill**
`[ Conhecer o método ]`

---

**H1** (peso 500)
O método que separa a Avanti

**BODY** (peso 400)
A Avanti é uma assessoria de crédito especializada na estruturação de operações com garantia de imóvel. Cada caso é analisado individualmente. A infraestrutura analítica cruza o cenário do cliente com as condições de uma rede de instituições parceiras e identifica a estrutura adequada antes de qualquer conversa sobre taxa. Não existe produto de prateleira. Existe um estudo da operação, conduzido por especialista, com precisão, critério e discrição.

---

**Grid de 3 colunas · Stat / List / Quote:**

#### Coluna 1 · Stat

**OVERLINE** EM NÚMEROS
**STAT** R$ 500mi+
**CAPTION** Em operações conduzidas desde 2021

#### Coluna 2 · List

**OVERLINE** DIFERENCIAIS
**LIST:**
- Leitura de cenário antes da taxa
- Acesso a uma rede de instituições parceiras
- Condução do início ao fim, sem repasse

#### Coluna 3 · Quote

**OVERLINE** DEPOIMENTO
**QUOTE** *"Resolveram em trinta dias o que meu banco recusou em anos."*
**CAPTION** Cliente empresário, interior de SP

---

**LABELS pill:**
`[ HOME EQUITY ]` `[ CASO A CASO ]` `[ DISCRIÇÃO ]`

**CAPTION**
Fonte: dados internos Avanti · 2021 a 2026

**FOOTNOTE**
* Operações sujeitas a análise e aprovação das instituições parceiras. Condições variam conforme o cenário de cada caso. Prazo médio de estruturação de 30 dias, podendo variar conforme a complexidade.

---

### Estilos identificados na composição

| # | Estilo | Aparece como |
|---|---|---|
| 01 | Display | "Seu imóvel pode financiar o próximo passo" |
| 02 | H1 | "O método que separa a Avanti" |
| 03 | H2 | Não aparece nesta peça (composição editorial curta; H2 só entra em conteúdo longo) |
| 04 | H3 | Não aparece nesta peça (composição editorial curta; H3 só entra em conteúdo longo) |
| 05 | Subtítulo | "A Avanti desenha cada operação caso a caso..." |
| 06 | Body | "A Avanti é uma assessoria de crédito..." |
| 07 | Overline | 4 ocorrências (manifesto, em números, diferenciais, depoimento) |
| 08 | Caption | "Fonte: dados internos..." e "Cliente empresário, interior de SP" |
| 09 | Label | Home Equity · Caso a caso · Discrição (3 badges) |
| 10 | Footnote | "* Operações sujeitas a análise..." |
| 11 | Quote | "Resolveram em trinta dias o que meu banco recusou em anos." |
| 12 | Stat | "R$ 500mi+" |
| 13 | List | Leitura de cenário, acesso a instituições, condução sem repasse |
| 14 | Button | 2 CTAs pill (primário e secundário) |

---

## Regras de ouro

### Princípios de peso

> [!success] Máximo peso 500, sem exceções
> Todo o sistema respeita o teto de 500. As antigas exceções de peso 600 (Stat e Label) foram eliminadas na v2.

> [!success] Leveza no tamanho grande
> Display em Light (300) e Stat em Regular (400). Em tamanho grande, peso leve com tracking apertado é o que entrega elegância premium. Peso pesado em tamanho grande lê varejo.

> [!success] Peso 300 nos auxiliares
> Subtítulo, Caption, Footnote e Quote em Light. Cria respiro premium contemporâneo.

> [!danger] Nunca peso 600 ou mais
> SemiBold (600), Bold (700) e ExtraBold (800) ficaram associados a varejo e performance marketing. Não use no sistema Avanti.

### Princípios de cabeçalhos

> [!success] Cascata Display, H1, H2, H3
> Display abre a peça (uma vez), H1 anuncia o título principal (uma vez), H2 abre seções dentro da peça, H3 abre subseções dentro de um H2. Nunca pule níveis (H1 direto para H3 quebra a estrutura, no HTML e no olho). Em peças curtas (post, banner, hero, capa), pare em Display e H1: H2 e H3 só fazem sentido em conteúdo longo.

> [!success] Subtítulo é deck, não cabeçalho
> Subtítulo descreve, não estrutura. Aparece colado debaixo de Display ou H1 para expandir a ideia do título, em Light 300. Para abrir nova seção, use H2; misturar Subtítulo com cabeçalhos de seção quebra a hierarquia.

### Princípios de tracking

> [!success] Tracking negativo crescente
> Quanto maior a fonte, mais apertado o tracking. -2.9px em Display e -3.2px em Stat. É o que dá densidade cara aos tamanhos grandes em peso leve.

> [!success] Tracking aberto em UPPERCASE
> Overline (2.4px) e Label (1px) precisam de tracking aberto para legibilidade e refinamento em caixa alta.

> [!success] Body sem tracking
> Texto de leitura mantém tracking 0 para máximo conforto visual.

### Princípios de caso

> [!success] Sentence case em headings
> Nunca Title Case. UPPERCASE somente em Overline e Label.

> [!success] Sentence case em botões
> "Conversar com um especialista", nunca "Conversar Com Um Especialista".

### Princípios de aplicação

> [!success] Botões sempre pill
> Border-radius 100px obrigatório em todos os botões. Cantos completamente arredondados.

> [!success] Linhas curtas em títulos
> Display: 3 a 6 palavras. H1: 5 a 8 palavras. H2: 4 a 8 palavras. H3: 3 a 6 palavras. Quebre se preciso.

> [!success] Body em 50 a 70 caracteres por linha
> Width máxima de 600 a 700px em desktop. Acima disso, a leitura quebra.

> [!warning] Body mínimo 16px no mobile
> Abaixo disso, iOS Safari força zoom automático.

---

> [!quote] Recado final
> **A disciplina é o que entrega o resultado.**
>
> Este sistema funciona se você seguir as regras. A tentação de "só dessa vez usar peso 600" ou "deixar este título em UPPERCASE" é o que diferencia marcas que parecem premium de marcas que realmente são. Na Avanti, o premium vem da leveza e do tracking, não do peso. Volte a este documento antes de criar cada peça nova. Use os Character Styles do Illustrator e os estilos globais do Elementor sempre que possível: automatizar a aplicação correta é a melhor defesa contra a falta de disciplina.
