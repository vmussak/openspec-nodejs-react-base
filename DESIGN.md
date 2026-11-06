---
version: alpha
name: Generic Blue Template
description: Template genérico de design para reutilização em diferentes projetos, com uma base visual neutra, paleta de azuis, tipografia acessível e componentes adaptáveis a sites e aplicações.

colors:
  primary: "#2563EB"
  primary-hover: "#1D4ED8"
  primary-active: "#1E40AF"
  primary-disabled: "#DBEAFE"
  ink: "#0F172A"
  body: "#334155"
  body-strong: "#1E293B"
  muted: "#475569"
  muted-soft: "#64748B"
  hairline: "#CBD5E1"
  border-control: "#64748B"
  focus: "#2563EB"
  hairline-soft: "#E2E8F0"
  canvas: "#F8FAFC"
  surface-soft: "#EFF6FF"
  surface-card: "#FFFFFF"
  surface-strong: "#DBEAFE"
  surface-dark: "#0F172A"
  surface-dark-elevated: "#1E293B"
  surface-dark-soft: "#172554"
  on-primary: "#FFFFFF"
  on-dark: "#F8FAFC"
  on-dark-soft: "#CBD5E1"
  accent-light: "#60A5FA"
  accent-deep: "#1E40AF"
  success: "#166534"
  warning: "#92400E"
  error: "#B91C1C"

typography:
  display-xl:
    fontFamily: "Inter, system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: 64px
    fontWeight: 600
    lineHeight: 1.05
    letterSpacing: -1.5px
  display-lg:
    fontFamily: "Inter, system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: 48px
    fontWeight: 600
    lineHeight: 1.1
    letterSpacing: -1px
  display-md:
    fontFamily: "Inter, system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: 36px
    fontWeight: 600
    lineHeight: 1.15
    letterSpacing: -0.5px
  display-sm:
    fontFamily: "Inter, system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: 28px
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: -0.3px
  title-lg:
    fontFamily: "Inter, system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: 22px
    fontWeight: 500
    lineHeight: 1.3
    letterSpacing: 0
  title-md:
    fontFamily: "Inter, system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: 18px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 0
  title-sm:
    fontFamily: "Inter, system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: 16px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 0
  body-md:
    fontFamily: "Inter, system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0
  body-sm:
    fontFamily: "Inter, system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0
  caption:
    fontFamily: "Inter, system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: 13px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 0
  caption-uppercase:
    fontFamily: "Inter, system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: 12px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 1.5px
  code:
    fontFamily: "JetBrains Mono, ui-monospace, monospace"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0
  button:
    fontFamily: "Inter, system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 0
  nav-link:
    fontFamily: "Inter, system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 0

rounded:
  xs: 4px
  sm: 6px
  md: 8px
  lg: 12px
  xl: 16px
  pill: 9999px
  full: 9999px

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  section: 96px

components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
    padding: 12px 20px
    minHeight: 44px
  button-primary-hover:
    backgroundColor: "{colors.primary-hover}"
    textColor: "{colors.on-primary}"
  button-primary-active:
    backgroundColor: "{colors.primary-active}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.md}"
  button-primary-disabled:
    backgroundColor: "{colors.primary-disabled}"
    textColor: "{colors.muted}"
    rounded: "{rounded.md}"
  button-secondary:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    borderColor: "{colors.border-control}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
    padding: 12px 20px
    minHeight: 44px
  button-secondary-on-dark:
    minHeight: 44px
    backgroundColor: "{colors.surface-dark-elevated}"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
    padding: 12px 20px
  button-text-link:
    minHeight: 44px
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.button}"
  button-icon-circular:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    rounded: "{rounded.full}"
    size: 44px
  text-link:
    backgroundColor: transparent
    textColor: "{colors.primary}"
    typography: "{typography.body-md}"
  top-nav:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    height: 64px
  hero-band:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.display-xl}"
    padding: 96px
  hero-illustration-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    rounded: "{rounded.xl}"
  feature-card:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.ink}"
    typography: "{typography.title-md}"
    rounded: "{rounded.lg}"
    padding: 32px
  product-mockup-card-dark:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.title-md}"
    rounded: "{rounded.lg}"
    padding: 32px
  code-window-card:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.code}"
    rounded: "{rounded.lg}"
    padding: 24px
  comparison-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.title-md}"
    rounded: "{rounded.lg}"
    padding: 32px
  pricing-tier-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.title-lg}"
    rounded: "{rounded.lg}"
    padding: 32px
  pricing-tier-card-featured:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.title-lg}"
    rounded: "{rounded.lg}"
    padding: 32px
  callout-card-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.title-md}"
    rounded: "{rounded.lg}"
    padding: 32px
  connector-tile:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.title-sm}"
    rounded: "{rounded.lg}"
    padding: 20px
  text-input:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    borderColor: "{colors.border-control}"
    rounded: "{rounded.md}"
    padding: 10px 14px
    minHeight: 44px
  text-input-focused:
    borderColor: "{colors.focus}"
    outline: "2px solid {colors.focus}"
    outlineOffset: 2px
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
  cookie-consent-card:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.lg}"
    padding: 24px
  category-tab:
    minHeight: 44px
    backgroundColor: transparent
    textColor: "{colors.muted}"
    typography: "{typography.nav-link}"
    padding: 8px 14px
    rounded: "{rounded.md}"
  category-tab-active:
    minHeight: 44px
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    rounded: "{rounded.md}"
  badge-pill:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.ink}"
    typography: "{typography.caption}"
    rounded: "{rounded.pill}"
    padding: 4px 12px
  badge-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.caption-uppercase}"
    rounded: "{rounded.pill}"
    padding: 4px 12px
  cta-band-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.display-sm}"
    rounded: "{rounded.lg}"
    padding: 64px
  cta-band-dark:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.display-sm}"
    rounded: "{rounded.lg}"
    padding: 64px
  footer:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark-soft}"
    typography: "{typography.body-sm}"
    padding: 64px
---

# Template genérico de design

## Visão geral

Este documento é um **template genérico** de design para servir como base em outros projetos. Define tokens e padrões reutilizáveis para sites, landing pages, painéis e aplicações, sem depender de uma marca, produto ou segmento específico.

A identidade padrão combina azuis para ações e destaques, fundos claros, textos em tons de azul-acinzentado e superfícies opcionais em azul-marinho. O estilo é simples, legível e consistente, com componentes adaptáveis ao conteúdo de cada projeto.

O bloco YAML concentra os valores de referência. Ao reutilizar esta base, personalize nome, conteúdo, marca e componentes necessários, mantendo os tokens e a documentação coerentes.

## Cores

### Paleta principal

| Token | Cor | Uso |
|---|---|---|
| `{colors.primary}` | #2563EB | Ações principais, links em fundos claros e destaques |
| `{colors.primary-hover}` | #1D4ED8 | Ação principal ao passar o ponteiro |
| `{colors.primary-active}` | #1E40AF | Ação principal pressionada |
| `{colors.primary-disabled}` | #DBEAFE | Fundo de ações desabilitadas |
| `{colors.accent-light}` | #60A5FA | Ilustrações, detalhes e links em fundos escuros |
| `{colors.accent-deep}` | #1E40AF | Ênfase em superfícies claras ou azul suave |
| `{colors.focus}` | #2563EB | Contorno de foco em superfícies claras |
| `{colors.on-primary}` | #FFFFFF | Texto em ações e faixas de azul primário |

Use o azul principal para orientar a atenção. O azul claro é um acento visual; para texto pequeno em fundos claros, prefira o azul principal ou profundo. Sobre `{colors.surface-strong}`, use `{colors.accent-deep}` para links. Em fundos escuros, links e contornos de foco usam `{colors.accent-light}` para preservar contraste.

### Superfícies e bordas

| Token | Cor | Uso |
|---|---|---|
| `{colors.canvas}` | #F8FAFC | Fundo padrão da página |
| `{colors.surface-soft}` | #EFF6FF | Seções suaves, áreas de apoio |
| `{colors.surface-card}` | #FFFFFF | Cartões, formulários e painéis |
| `{colors.surface-strong}` | #DBEAFE | Seleções e destaques suaves |
| `{colors.surface-dark}` | #0F172A | Seções escuras e rodapé opcionais |
| `{colors.surface-dark-elevated}` | #1E293B | Cartões sobre fundos escuros |
| `{colors.surface-dark-soft}` | #172554 | Áreas internas com tom azul-marinho |
| `{colors.hairline}` | #CBD5E1 | Bordas decorativas de cartões e divisores |
| `{colors.hairline-soft}` | #E2E8F0 | Divisores discretos |
| `{colors.border-control}` | #64748B | Bordas de controles e campos em fundos claros |

Superfícies escuras são opcionais. A página pode permanecer clara; não há obrigação de alternar cores entre seções. Use bordas decorativas apenas para agrupamento e bordas de controles com contraste suficiente para identificar sua área interativa.

### Texto

| Token | Cor | Uso |
|---|---|---|
| `{colors.ink}` | #0F172A | Títulos e texto de maior destaque |
| `{colors.body-strong}` | #1E293B | Texto enfatizado |
| `{colors.body}` | #334155 | Parágrafos e descrições |
| `{colors.muted}` | #475569 | Texto secundário em superfícies claras |
| `{colors.muted-soft}` | #64748B | Legendas sobre canvas ou cartão branco |
| `{colors.on-dark}` | #F8FAFC | Texto principal em superfícies escuras |
| `{colors.on-dark-soft}` | #CBD5E1 | Texto secundário em superfícies escuras |

Em `{colors.surface-strong}`, prefira `{colors.body}` ou `{colors.muted}` para textos pequenos. Não reduza a opacidade do texto a ponto de comprometer a leitura.

### Estados semânticos

- `{colors.success}` (#166534): confirmação e sucesso.
- `{colors.warning}` (#92400E): atenção e avisos.
- `{colors.error}` (#B91C1C): erros e ações destrutivas.

Essas cores são exceções funcionais à paleta azul. Use-as como texto, ícones ou bordas sobre superfícies claras e acompanhe-as de rótulos ou mensagens; a cor sozinha não deve transmitir o estado.

## Tipografia

Use **Inter** para títulos, textos e controles, com fontes do sistema como alternativas. O template funciona sem fontes proprietárias. **JetBrains Mono**, com fallback `ui-monospace, monospace`, é opcional para trechos de código.

| Token | Tamanho | Peso | Altura de linha | Uso |
|---|---|---|---|---|
| `{typography.display-xl}` | 64px | 600 | 1.05 | Título principal em telas amplas |
| `{typography.display-lg}` | 48px | 600 | 1.1 | Títulos de seção |
| `{typography.display-md}` | 36px | 600 | 1.15 | Subdivisões e chamadas |
| `{typography.display-sm}` | 28px | 600 | 1.2 | Títulos de cartões grandes |
| `{typography.title-lg}` | 22px | 500 | 1.3 | Cabeçalhos de cartões |
| `{typography.title-md}` | 18px | 500 | 1.4 | Títulos de componentes |
| `{typography.title-sm}` | 16px | 500 | 1.4 | Rótulos e listas |
| `{typography.body-md}` | 16px | 400 | 1.55 | Texto padrão e campos |
| `{typography.body-sm}` | 14px | 400 | 1.55 | Texto auxiliar |
| `{typography.caption}` | 13px | 500 | 1.4 | Legendas e badges |
| `{typography.caption-uppercase}` | 12px | 500 | 1.4 | Rótulos curtos opcionais |
| `{typography.code}` | 14px | 400 | 1.6 | Código e dados técnicos |
| `{typography.button}` | 14px | 500 | 1.4 | Botões |
| `{typography.nav-link}` | 14px | 500 | 1.4 | Navegação |

Mantenha textos de leitura em 16px e limite parágrafos a cerca de 65–75 caracteres por linha. Em telas pequenas, reduza títulos de 64px para 32px e de 48px para 28px. Preserve a hierarquia sem cortar conteúdo quando o usuário ampliar a fonte.

## Layout e espaçamento

- Unidade base de 4px: `{spacing.xxs}` 4px, `{spacing.xs}` 8px, `{spacing.sm}` 12px, `{spacing.md}` 16px, `{spacing.lg}` 24px, `{spacing.xl}` 32px e `{spacing.xxl}` 48px.
- Seções amplas usam `{spacing.section}` (96px) de espaço vertical em desktop, reduzido para 48px em mobile.
- Contêiner padrão centralizado, com largura máxima de 1200px e margens laterais de 16px em mobile, 24px em tablet e 32px em desktop.
- Cartões usam 24px ou 32px de preenchimento, conforme a densidade. Faixas de chamada usam 64px em desktop e 24px em mobile.
- Grades de conteúdo usam três colunas em desktop, duas em tablet e uma em mobile. Ajuste a quantidade ao conteúdo, preservando sua legibilidade.
- Hero pode usar uma ou duas colunas. Navegação, sidebar e rodapé são opcionais e dependem das necessidades do projeto.

Os valores de padding dos componentes no YAML são referências de desktop. No hero, `padding: 96px` representa o espaço vertical; as laterais seguem o contêiner. Adapte esses valores em telas menores sem criar rolagem horizontal na página.

## Formas e profundidade

| Token | Valor | Uso |
|---|---|---|
| `{rounded.xs}` | 4px | Pequenos detalhes |
| `{rounded.sm}` | 6px | Itens compactos |
| `{rounded.md}` | 8px | Botões, campos e abas |
| `{rounded.lg}` | 12px | Cartões e painéis |
| `{rounded.xl}` | 16px | Destaques e grandes contêineres |
| `{rounded.pill}` | 9999px | Badges |
| `{rounded.full}` | 9999px | Avatares e botões circulares |

Prefira superfícies e bordas para separar conteúdo. Sombras discretas são opcionais para menus, modais ou cartões elevados; não use sombras fortes como padrão. Use ícones SVG de uma mesma família e imagens pertinentes ao projeto, sem elementos de marca predefinidos.

## Componentes reutilizáveis

As chaves em `components:` são pontos de partida, não uma lista obrigatória de elementos da página. Referencie-as como `{components.button-primary}` ou `{components.feature-card}`.

### Navegação e ações

- **`top-nav`**: barra de 64px com identificação do projeto, links essenciais e ação principal opcional. Em mobile, o menu deve poder ser aberto por teclado e toque.
- **`button-primary`**: fundo azul principal, texto branco, altura mínima de 44px, padding de 12px × 20px e raio de 8px. As variantes `-hover`, `-active` e `-disabled` representam seus estados.
- **`button-secondary`**: fundo claro, texto escuro e borda de 1px em `{colors.border-control}`. A variante `-on-dark` usa superfície escura elevada e texto claro.
- **`button-text-link`**: ação textual com área de toque mínima de 44px de altura. **`button-icon-circular`**: botão de 44px × 44px com nome acessível.
- **`text-link`**: link azul sublinhado em superfícies claras; em superfícies escuras, use `{colors.accent-light}`. Links dentro de texto não precisam ter altura de botão.

### Cartões e seções

- **`hero-band`** e **`hero-illustration-card`**: apresentação inicial com título, descrição, ação e imagem ou prévia opcional do projeto.
- **`feature-card`**: cartão branco com título, descrição e ícone opcional; padding de 32px e raio de 12px.
- **`comparison-card`**: cartão para comparar opções, serviços ou recursos, sem categorias fixas.
- **`product-mockup-card-dark`** e **`code-window-card`**: variações opcionais para prévias de interface ou conteúdo técnico sobre fundo escuro.
- **`pricing-tier-card`** e **`pricing-tier-card-featured`**: opcionais para projetos com planos; a variante destacada usa fundo escuro e texto claro.
- **`callout-card-primary`**: chamada azul com texto branco, padding de 32px e raio de 12px.
- **`connector-tile`**: cartão genérico de integração ou recurso, com ícone, título e descrição.
- **`cta-band-primary`** e **`cta-band-dark`**: faixas de chamada opcionais. Sobre azul principal, use botão branco com texto azul profundo; sobre fundo escuro, use a variante secundária escura.
- **`footer`**: rodapé opcional com links relevantes ao projeto. O padrão usa fundo azul-marinho; uma versão clara pode usar canvas e texto escuro.

### Campos, abas e indicadores

- **`text-input`**: cartão branco como fundo, texto de 16px, borda de 1px em `{colors.border-control}`, raio de 8px, padding de 10px × 14px e altura mínima de 44px. Todo campo precisa de rótulo visível.
- **`text-input-focused`**: herda a base do campo e acrescenta borda e contorno de foco azul. Mostre erros próximos do campo, com texto e associação acessível.
- **`category-tab`** e **`category-tab-active`**: filtros ou abas com altura mínima de 44px. A seleção deve ser indicada também por texto, peso ou borda, além da cor de fundo.
- **`badge-pill`**: indicador de categoria com fundo claro e texto escuro. **`badge-primary`**: destaque azul com texto branco. Badges não interativos não precisam ter 44px de altura.
- **`cookie-consent-card`**: variação opcional de aviso flutuante, usada apenas quando o projeto precisar desse fluxo.

Variantes de estado herdam dimensões, tipografia e espaçamento do componente base e sobrescrevem apenas as propriedades declaradas no YAML. Preserve esse comportamento ao implementar os tokens.

## Interação e acessibilidade

- Ofereça feedback ao passar o ponteiro, pressionar e focar controles, sem alterar seu tamanho ou deslocar o layout.
- Use foco visível por teclado: contorno de 2px com afastamento de 2px. Em superfícies escuras, utilize o azul claro.
- Garanta contraste mínimo de 4.5:1 para textos comuns e 3:1 para texto grande e indicadores visuais essenciais de controles.
- Use áreas de toque de pelo menos 44px × 44px para botões e controles isolados.
- Preserve a ordem lógica de navegação por teclado. Menus e modais devem devolver o foco ao elemento de origem quando fechados.
- Durante operações assíncronas, apresente carregamento, evite envios duplicados e comunique o resultado.
- Combine cores de estado com ícones ou mensagens. Controles desabilitados devem estar identificados semanticamente.
- Use transições discretas de 150–200ms e respeite `prefers-reduced-motion`.
- Forneça texto alternativo para imagens informativas, rótulos para campos e nomes acessíveis para botões de ícone.

## Comportamento responsivo

| Faixa | Largura | Comportamento padrão |
|---|---|---|
| Mobile | < 768px | Coluna única, menu recolhido, títulos menores e padding reduzido |
| Tablet | 768px–1023px | Grades de até duas colunas e navegação adaptada ao espaço |
| Desktop | 1024px–1439px | Grades de até três colunas e navegação completa quando couber |
| Wide | ≥ 1440px | Contêiner limitado a 1200px e margens externas maiores |

Empilhe texto e mídia no mobile seguindo a ordem de leitura. Imagens devem manter a proporção e caber no contêiner. Tabelas e blocos de código podem ter rolagem interna quando necessário, sem fazer a página inteira rolar horizontalmente. Verifique também a navegação por teclado e o layout com zoom de 200%.

## Como reutilizar em outros projetos

1. Copie este documento e substitua o nome e a descrição pelo contexto do novo projeto.
2. Use a paleta azul como padrão e ajuste os tokens centrais quando uma identidade própria for definida.
3. Selecione os componentes necessários e personalize textos, imagens e navegação para o produto.
4. Acrescente componentes específicos sem acoplar a base a um serviço, marca ou fonte proprietária.
5. Mantenha valores no YAML e referências na documentação sincronizados, usando `{colors.*}`, `{typography.*}`, `{rounded.*}`, `{spacing.*}` e `{components.*}`.
6. Valide contraste, foco, estados e adaptação a telas pequenas após cada personalização visual.

Esta base define um tema claro com superfícies escuras opcionais. Um tema escuro completo, gráficos, tabelas complexas e fluxos específicos devem receber tokens e padrões próprios conforme a necessidade do projeto.
