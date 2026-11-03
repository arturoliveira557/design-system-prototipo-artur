# 1ª Avaliação — Design System & Protótipo

**Aluno:** Artur Oliveira de Lima  
**Disciplina/Módulo:** UI/UX e Design de Produtos  
**Ferramenta:** Figma

## Link do protótipo no Figma

https://www.figma.com/design/th2iPWj4odBYo1hk8JfbAq

## Objetivo

Criar um Design System estruturado e um protótipo navegável no Figma, utilizando variáveis locais reutilizáveis, componentes reais e padrões visuais consistentes.

## Design System

### Cores
Foram criadas variáveis locais para:

- Primary
- Secondary
- Tertiary
- Background
- OnBackground
- onSurface

As cores estão organizadas em duas coleções:
- `Colors / Light`
- `Colors / Dark`

> Observação: a conta Figma utilizada está no plano Starter, que permite apenas um modo por coleção. Por isso, Light e Dark foram organizados em coleções separadas, preservando os mesmos nomes e funções semânticas.

### Tipografia
Foram criadas variáveis e estilos reutilizáveis para:

- Headline
- Subtitle
- Body
- Button
- Title

Fonte utilizada: **Inter**.

## Componentes

Foram criados como componentes reais do Figma:

- `Button/Primary`
- `Button/Secondary`
- `Button/Tertiary`
- `AppBar`

A AppBar possui duas variantes:
- `Theme=Light`
- `Theme=Dark`

## Protótipo navegável

Fluxo:

`Home → Projetos → Detalhes → Concluído → Home`

Telas:
1. Home
2. Projetos
3. Detalhes
4. Concluído

Todas as telas utilizam a AppBar e componentes do Design System.

## Critérios da avaliação atendidos

- [x] Variáveis locais de cores reutilizáveis
- [x] Tipografias reutilizáveis
- [x] Primary, Secondary, Tertiary, Background e OnBackground
- [x] onSurface em Light e Dark
- [x] Headline, Subtitle, Body, Button e Title
- [x] Botão Primário como componente
- [x] Botão Secundário como componente
- [x] Botão Terciário como componente
- [x] AppBar como componente
- [x] Variante Dark da AppBar
- [x] AppBar presente em todas as telas
- [x] Protótipo navegável
- [x] Uso das variáveis e componentes criados

## Estrutura do repositório

```text
design-system-prototipo-artur/
├── README.md
└── docs/
    ├── figma.md
    └── checklist.md
```
