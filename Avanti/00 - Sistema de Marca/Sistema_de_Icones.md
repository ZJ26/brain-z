---
versão: 1.0
atualização: 16/06/2026
responsável_revisão: Marketing
status: vigente
---

# Sistema de Ícones

> **Camada do sistema · Execução visual (ícone).** Como a marca usa ícones. Traduz a contenção do método em traço: um conjunto pareado em dois pesos, monocromático, colorido pela mesma lógica de tokens das cores, com economia no destaque. Par com o Sistema de Cores e o Sistema Tipográfico. Forma com eles o trio de execução visual da Avanti.

Os ícones são a menor unidade visual da marca. Aparecem em botão, lista, card, seção de produto, apresentação e documento de cliente. Por serem pequenos e repetidos, é fácil tratá-los como enfeite. Este documento existe para o contrário: garantir que cada ícone trabalhe a favor do método, com o mesmo rigor que a marca aplica a cor e tipografia.

| Metadado | Valor |
|---|---|
| Conjunto | Dois pesos pareados (Linha e Sólido), 1:1 |
| Total | 1000 conceitos por peso (2000 arquivos) |
| Categorias | 16 |
| Grade | viewBox 14, enquadramento único e compartilhado entre os pesos |
| Cor | Monocromática, herdada (`currentColor`), nunca cravada |
| Fonte de cor | `fill` em todos os ícones, nos dois pesos |
| Sistemas de cor | White · Dark (ver Sistema de Cores) |
| Onde vivem os arquivos | Kit de Marca (este documento é o sistema, não o arquivo) |

---

## Conceito · O traço a serviço do método

> [!info] Filosofia do sistema
> **O ícone esclarece, não decora.**
>
> É a mesma disciplina que a marca aplica à cor (contenção como assinatura) e ao texto (a sofisticação vem do controle). O ícone entra quando ajuda o leitor a entender ou a navegar mais rápido. Quando não ajuda, não entra. Ícone que está ali só para preencher espaço enfraquece a peça, do mesmo jeito que um adjetivo vazio enfraquece uma manchete.

### Princípio fundamental

**Cada ícone nomeia uma ideia. Uma só.**

O ícone é a versão visual da regra de copy "uma ideia por imagem". Ele aponta para um conceito concreto (patrimônio, garantia, prazo, contato) e cede o protagonismo ao conteúdo. A marca aparece como método, não como herói, e o ícone segue a mesma regra: organiza a leitura sem chamar atenção para si.

Três traços definem o ícone da Avanti, e são os mesmos da voz da marca:

- **Contido.** Traço limpo, sem ornamento. Nada de sombra, gradiente ou volume.
- **Consistente.** Mesma grade, mesmo peso visual, mesmo enquadramento. O conjunto é reconhecível de imediato, como a firmeza verbal que o Tom de Voz protege.
- **Funcional.** Cada ícone serve a uma função de leitura. Se não tem função, sai da peça.

---

## Os dois pesos

A marca trabalha com dois pesos do mesmo ícone: **Linha** e **Sólido**. Não são dois conjuntos diferentes. São o mesmo desenho em duas presenças, pareados um a um, na mesma grade. Isso permite trocar de peso sem que o ícone se desloque ou mude de tamanho.

A relação entre os dois espelha a lógica da cor. No Sistema de Cores, os navies são a base silenciosa e o Brand Accent é o destaque raro. Aqui vale o mesmo: **a Linha é a base, o Sólido é o destaque.**

| Peso | Papel | Quando usar |
|---|---|---|
| **Linha** | Base de leitura. O peso de trabalho do sistema. | Listas, navegação, itens de apoio, conteúdo denso, estados de repouso, qualquer lugar onde o ícone acompanha sem competir. É o padrão. |
| **Sólido** | Destaque e presença. O peso da ênfase. | O item ativo ou selecionado, o ícone-âncora de um bloco de destaque, o estado de hover, o momento em que um conceito precisa pesar mais que os vizinhos. Usado com economia. |

### O par em estado e em ênfase

O uso mais forte do conjunto é a troca Linha para Sólido para marcar estado. Em um menu, abas ou lista de etapas, o item em repouso fica em Linha e o item ativo vira Sólido. Como os dois pesos compartilham grade e enquadramento, a troca é limpa, sem salto.

> [!success] Sólido com economia, igual ao accent
> O Sólido vale pela raridade, do mesmo modo que o Brand Accent. Uma tela em que tudo é Sólido perde hierarquia: nada se destaca porque tudo grita. Mantenha a Linha como base e reserve o Sólido para o que precisa de presença. A exceção é o tamanho muito pequeno (ver "Tamanho e proporção"), onde o detalhe da Linha colapsa e o Sólido lê melhor.

> [!warning] Não misture pesos na mesma fileira
> Dentro de um mesmo grupo (uma lista, uma fileira de features, um conjunto de etapas), todos os ícones em repouso ficam no mesmo peso. Misturar Linha e Sólido lado a lado, sem que isso marque estado, quebra a consistência e parece descuido. A troca de peso só comunica quando significa alguma coisa (ativo, selecionado, em foco).

---

## Fundamento técnico

A coerência do sistema não é só estética. É técnica, e é o que faz o ícone obedecer ao Sistema de Cores em vez de brigar com ele.

### A cor é herdada, nunca cravada

Todo ícone usa `currentColor`. Nenhum ícone carrega cor fixa no arquivo. Isso significa que o ícone assume a cor definida pela peça (no Elementor, na cor primária do widget; em CSS, na propriedade de cor do contexto) e troca de cor junto com o modo White ou Dark, sem editar o arquivo.

Cor cravada no arquivo é o erro que impede a colorização e contradiz o princípio de tokens funcionais do Sistema de Cores. Por isso a regra é absoluta: o ícone não decide a própria cor, o sistema decide.

### A cor entra sempre por `fill`

Nos dois pesos, a cor do ícone vem de `fill`. O peso Sólido é preenchido por natureza. O peso Linha tem o contorno entregue como forma preenchida (o traço é uma forma fina, não uma linha aberta), para que também receba cor por `fill`, exatamente como o Sólido. Fonte de cor única nos dois pesos: nenhum ícone do sistema depende de `stroke` para colorir.

Esse detalhe evita o defeito clássico do ícone de linha que, ao receber cor, preenche o miolo inteiro e vira um bloco. No sistema da Avanti isso não acontece, porque a cor pinta o traço, não a área fechada.

### Grade e enquadramento

| Propriedade | Valor |
|---|---|
| viewBox | 14 (grade quadrada) |
| Enquadramento | Idêntico entre Linha e Sólido do mesmo conceito |
| Estrutura do arquivo | `fill="currentColor"`, sem `id`, sem cor fixa, sem `stroke` colorido |
| Tom | Monocromático: um token por ícone, sempre |

> [!danger] Nunca preto puro, nunca cor cravada
> O ícone nunca usa `#000000` (vale a mesma regra do Sistema de Cores: a base escura é BG Primary `#020B1A`, não preto puro). E nunca carrega cor fixa no arquivo. Cor fixa quebra a colorização e a coesão dos dois modos. Se um ícone novo chega com preto cravado, ele é convertido para `currentColor` antes de entrar no Kit.

> [!warning] Monocromático, sempre
> O sistema é de um tom por ícone. Ícone de duas ou mais cores, multicolorido ou com preenchimento parcial, está fora do sistema. A profundidade vem da escolha entre Linha e Sólido e do token de cor, não de cores internas no ícone.

---

## Cor do ícone

O ícone é colorido pelos mesmos cinco tokens do Sistema de Cores, e segue a mesma cor de texto de cada modo. A regra é direta: por padrão, o ícone tem a cor de texto do modo. O destaque em accent é exceção, não regra.

### Cor por modo

| Modo | Cor padrão do ícone | Destaque (raro) | Sobre card de presença |
|---|---|---|---|
| **White** | BG Primary `#020B1A` (cor de texto do modo) | Brand Accent `#2290FF`, no ícone-âncora de um único bloco | Sobre Brand Deep ou BG Primary, o ícone é BG Light `#F6F5F2` |
| **Dark** | BG Light `#F6F5F2` (cor de texto do modo) | Brand Accent `#2290FF`, com economia | Sobre BG Light, o ícone é BG Primary `#020B1A` |

A lógica é a do par invertido das cores: o ícone acompanha o texto. Onde o texto é escuro, o ícone é escuro; onde o texto é claro, o ícone é claro. Mesma cor, função espelhada entre os modos.

> [!warning] O ícone em accent entra na conta do accent
> O Sistema de Cores limita o Brand Accent a três ou quatro elementos por página. Um ícone pintado de Brand Accent conta nesse orçamento, junto com o botão primário, os Overlines e a palavra de destaque. Um ícone-âncora em accent costuma ser suficiente por bloco. Encher uma tela de ícones em accent gasta o destaque e contradiz a economia que é a assinatura da marca.

> [!info] Contraste de ícone
> O ícone é elemento gráfico, não texto pequeno, então segue o piso de 3:1 da WCAG para componentes, não o de 4,5:1 de texto. Mesmo assim, prefira os tokens de alto contraste do modo (cor de texto cheia). O Brand Accent sobre BG Light fica em 3,0:1: serve para ícone (gráfico), nunca para texto pequeno ao lado. Ver Sistema de Cores, "Matriz cruzada de combinações".

---

## Tamanho e proporção

O tamanho do ícone se ancora na escala tipográfica. O ícone que acompanha um texto cresce e diminui com ele, para manter o alinhamento óptico. Os valores abaixo são ponto de partida, ajustáveis ao contexto.

| Contexto | Tamanho do ícone | Pareado com (Sistema Tipográfico) |
|---|---|---|
| Ícone em linha com corpo de texto | 16 a 20px | Texto (Body), 16px |
| Ícone de item de lista ou menu | 20 a 24px | Texto e Button |
| Ícone ao lado de subtítulo | 24 a 28px | Subtítulo, 19px |
| Ícone-âncora de feature ou card | 28 a 40px | Título 3 (H3) e Título 2 (H2) |
| Ícone de destaque em hero ou abertura | 48px ou mais | Display e Título (H1) |

### Regras de proporção

- **Alinhamento.** O ícone alinha pelo centro óptico do texto que acompanha, não pela linha de base. Em fileira de features, todos os ícones ocupam a mesma caixa, mesmo que o desenho preencha áreas diferentes.
- **Respiro.** O ícone precisa de espaço ao redor. Comprimido contra o texto, perde leitura. Trate o espaço em volta como parte do ícone.
- **Não distorça.** O ícone é quadrado (grade 14). Escale proporcional. Nunca estique para preencher um espaço.

> [!tip] No tamanho pequeno, prefira o Sólido
> Abaixo de cerca de 18px, o detalhe fino da Linha começa a fechar e o ícone perde clareza. Nessas medidas, o Sólido lê melhor. É a única situação em que o Sólido vira a escolha padrão em vez do destaque.

---

## Seleção do ícone

Escolher o ícone certo é uma decisão de copy tanto quanto de design. O ícone errado diz a coisa errada, mesmo bonito.

### O literal vence o clichê

Prefira o ícone que nomeia o conceito de forma direta. Para garantia de imóvel, o imóvel ou a chave dizem mais que um cadeado genérico. Para prazo, o calendário ou o relógio dizem mais que uma seta. O clichê visual (o aperto de mão sorridente para "parceria", o foguete para "crescimento") é o equivalente gráfico do "executivo feliz apertando mão" que o Sistema de Copy proíbe em imagem. Use o aperto de mão quando ele significa um acordo concreto, não como enfeite de "confiança".

### A régua de relevância

O catálogo de ícones classifica cada ícone por aderência ao núcleo da marca. A régua orienta a escolha, não a proíbe: um ícone de relevância baixa pode entrar quando a peça pede, desde que com consciência.

| Relevância | O que significa | Exemplos de família |
|---|---|---|
| **Alta** | Núcleo da marca. Fala diretamente de patrimônio, capital, garantia, método, confiança, prazo ou contato. | Banco, imóvel, calculadora, balança da justiça, escudo, cadeado, gráfico de análise, calendário, telefone, documento |
| **Média** | Apoio. Sustenta o tema sem ser o centro. | Localização e abrangência, equipe, dados e tecnologia, crescimento como metáfora, interface essencial |
| **Baixa** | Pontual. Fora do núcleo financeiro. Uso editorial ou decorativo, caso a caso. | Alimentos, entretenimento, logos de rede social, cultura, esportes |

### Ícone por perfil e estágio

O ícone reforça o ângulo da peça. A escolha acompanha o perfil de público (ver documento de Público) e o estágio de funil (ver Sistema de Copy).

| Contexto | Famílias de ícone que reforçam |
|---|---|
| Empresário de patrimônio | Capital, alavancagem, gráfico de alta, maleta, negócio, oportunidade |
| Cliente em reestruturação | Organização, fôlego de caixa, calendário, leitura de cenário, escudo (proteção) |
| Patrimônio-rico de renda modesta | Imóvel, balança da justiça, segurança jurídica, reconhecimento, abrangência nacional |
| Topo de funil | Quase nenhum ícone. O topo observa a cena, não ilustra produto |
| Meio de funil | Método, etapas, comparativo, documento, análise |
| Fundo de funil | Prazo, contato, número, recibo, confirmação |

> [!info] Tecnologia com a ressalva da marca
> Ícones de dado, rede e inteligência analítica apoiam o argumento da infraestrutura que cruza cenários. Use sempre com aterrissagem funcional (ver Sistema de Copy) e lembre da posição da marca: a tecnologia acelera a análise e dá precisão, sem tomar o lugar do especialista. O ícone não deve sugerir automação que dispensa a pessoa.

---

## Aplicação por componente

O ícone se encaixa nos componentes definidos no Sistema de Cores. As cores abaixo seguem aquele sistema.

| Componente | Peso e cor do ícone |
|---|---|
| **Botão primário** | Quando houver ícone, ele é BG Light `#F6F5F2`, acompanhando o texto do botão. Use ícone só quando ele esclarece a ação. |
| **Botão secundário** | Ícone na mesma cor da borda e do texto do estado (Brand Accent ou Brand Deep, conforme modo e estado). |
| **Card de apoio (sobre o fundo claro ou surface)** | Linha como padrão, na cor de texto do modo. Sólido se o card é o destaque da seção. |
| **Card de presença (Brand Deep ou BG Primary)** | Ícone em BG Light. Pode usar Brand Accent no ícone-âncora, dentro do orçamento de accent. |
| **Lista e item de menu** | Linha, na cor de texto. Item ativo vira Sólido, e pode receber Brand Accent. |
| **Label** | Em geral sem ícone. Se houver, segue a cor do texto do label e mantém o tamanho pequeno legível. |
| **Bloco de feature ou etapa** | Ícone-âncora maior, um por bloco. Linha no conjunto, Sólido no bloco em foco. |

---

## O que evitar

- **Ícone decorativo.** Ícone sem função de leitura, só para preencher. Se a peça lê igual sem ele, ele sai.
- **Excesso.** Vários ícones disputando atenção na mesma tela. O destaque vale pela raridade, aqui também.
- **Mistura de pesos sem significado.** Linha e Sólido lado a lado sem marcar estado.
- **Cor cravada ou preto puro.** Quebra a colorização e a coesão dos modos.
- **Multicolorido.** Mais de um tom no mesmo ícone. O sistema é monocromático.
- **Clichê visual.** O ícone genérico de "sucesso", "confiança" ou "inovação" que não nomeia nada concreto.
- **Estética juvenil ou de trend.** Ícone arredondado em excesso, expressivo, de humor performático. A marca pública não fala nesse registro (ver antialvo, documento de Público).
- **Emoji no lugar de ícone.** Emoji é informal e foge do sistema. No atendimento, é aceito com parcimônia e sobriedade (ver Sistema de Copy, "WhatsApp e atendimento direto"), nunca como ícone de marca.
- **Ícone esticado.** Distorcer a proporção quadrada para encaixar num espaço.

---

## Checklist de validação

Antes de aplicar um ícone, percorrer estes pontos.

**Função**
- O ícone esclarece a leitura ou a navegação? Se a peça lê igual sem ele, ele não precisa estar ali.
- O ícone nomeia um conceito concreto, em vez de ilustrar uma sensação vaga?

**Peso**
- O peso está certo para o papel (Linha de base, Sólido de destaque)?
- Dentro do grupo, todos os ícones em repouso estão no mesmo peso?
- O Sólido está sendo usado com economia, e não em tudo?

**Cor**
- O ícone usa `currentColor`, sem cor cravada e sem preto puro?
- A cor segue a cor de texto do modo, com accent só no destaque?
- Se há ícone em accent, ele cabe no orçamento de três a quatro accents da página?

**Tamanho**
- O tamanho está ancorado na escala tipográfica do contexto?
- Em tamanho pequeno, o peso escolhido lê com clareza (Sólido quando a Linha fecha)?
- A proporção quadrada foi preservada, sem distorção?

**Marca**
- O ícone reforça o perfil e o estágio da peça?
- O ícone evita clichê, multicolorido e estética de trend?
- O conjunto da peça soa como a marca conduzindo, não como mais um material querendo parecer sofisticado?

---

## Regras de ouro

> [!success] Linha é a base, Sólido é o destaque
> A Linha é o peso de trabalho. O Sólido marca estado e ênfase, com a mesma economia do Brand Accent. Misturar pesos só comunica quando significa estado.

> [!success] Cor herdada, sempre
> Todo ícone usa `currentColor` e recebe cor por `fill`. Nunca cor cravada, nunca preto puro, nunca `stroke` colorido. O sistema decide a cor, não o arquivo.

> [!success] Um tom por ícone
> Monocromático sempre. A profundidade vem da escolha entre Linha e Sólido e do token de cor, não de cores internas.

> [!success] O ícone segue o texto
> Por padrão, o ícone tem a cor de texto do modo e o tamanho ancorado na escala tipográfica. Onde o texto é escuro, o ícone é escuro; onde é claro, é claro.

> [!success] Um ícone, uma ideia
> Cada ícone nomeia um conceito concreto e cede o protagonismo ao conteúdo. O ícone é método, não enfeite.

> [!danger] Contenção é assinatura
> O excesso de ícone enfraquece a peça do mesmo jeito que o excesso de accent ou de adjetivo. Na dúvida, menos ícone.

---

## Variáveis CSS

```css
:root {
  /* Tamanho do ícone, ancorado na escala tipográfica */
  --icon-inline: 18px;   /* em linha com o corpo de texto */
  --icon-list: 22px;     /* item de lista e menu */
  --icon-subtitle: 26px; /* ao lado de subtítulo */
  --icon-feature: 36px;  /* âncora de feature ou card */
  --icon-hero: 56px;     /* destaque em hero e abertura */

  /* Cor do ícone por modo (acompanha a cor de texto) */
  --icon-on-light: #020B1A;  /* modo White: BG Primary */
  --icon-on-dark: #F6F5F2;   /* modo Dark: BG Light */
  --icon-accent: #2290FF;    /* destaque raro, dentro do orçamento de accent */
}

/* Padrão de uso: o ícone herda a cor do contexto */
.icone {
  width: var(--icon-list);
  height: var(--icon-list);
  color: currentColor;   /* a cor vem do texto ao redor */
  fill: currentColor;    /* a cor entra por fill, nos dois pesos */
  flex: 0 0 auto;
}
```

> [!info] No Elementor
> Os ícones são SVG com `currentColor`. Use o widget Ícone na opção de carregar SVG e defina a Cor Primária: o ícone assume a cor escolhida sem encher o miolo, porque a cor entra por `fill`. O catálogo de busca e os dois pacotes (Sólido e Linha) vivem no Kit de Marca.

---

Este documento define como a marca usa ícones. Os arquivos em si, o catálogo de busca e a biblioteca completa pertencem ao Kit de Marca (ver Leia-me, "O que é o Sistema de Marca Avanti"). Mudança que crie um novo peso, um conjunto paralelo ou uma estética própria de ícone exige aprovação formal (ver Governança, "O que exige aprovação formal").
