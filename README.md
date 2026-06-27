# Comunicação Visual na Arquitetura Corporativa
### Uma publicação interativa desenvolvida para a **Quadoo Arquitetura Corporativa**

---

## Sobre o Projeto

Esta é uma publicação de rolagem fluida — um formato de apresentação moderno que combina **design editorial**, **tipografia expressiva** e **animações sincronizadas com o scroll** para criar uma experiência imersiva e profissional no navegador.

O conteúdo explora a importância da Comunicação Visual para marcas corporativas, apresentando os elementos visuais da identidade da Quadoo e um portfólio de projetos executados.

---

## Experiência

Ao rolar a página, o usuário encontra:

- **Efeito typewriter** na pergunta de abertura, simulando digitação em tempo real
- **Linhas que se desenham horizontalmente**, revelando seções progressivamente
- **Animações de entrada e saída simétricas** — cada elemento aparece e desaparece no mesmo eixo de movimento
- **Tipografia em três famílias** combinadas artisticamente — Circular Std, Roboto e Bricolage Grotesque
- **Paleta de cores** da marca apresentada em barras verticais com dados técnicos (Pantone, CMYK, RGB e HEX)
- **Formas geométricas** desenhadas em código, sem imagem
- **Portfólio de projetos** em scroll contínuo com alternância de direção
- **Tela de encerramento** com chamada para ação

---

## Estrutura da Publicação

```
01 — Logo                  Apresentação da marca com fade de entrada
02 — Pergunta              Barra de busca com efeito typewriter
03 — Tipografia            Texto + linha rosa + letras em fontes mistas
04 — Paleta de Cores       Barras coloridas com dados técnicos completos
05 — Formas                Geometrias em SVG animadas individualmente
06 — Textura               Padrão gráfico da identidade visual
07 — Exemplos              Marcas globais + ecossistema Google
08 — Mockups               Identidade aplicada em materiais reais
09 — Portfólio             8 projetos corporativos executados
10 — Encerramento          CTA com símbolo da marca
```

---

## Tecnologias Utilizadas

| Tecnologia | Uso |
|---|---|
| HTML5 semântico | Estrutura da publicação |
| CSS3 + Transitions | Animações e layout responsivo |
| Intersection Observer API | Detecção de scroll sem impacto na performance |
| CSS `mix-blend-mode` | Remoção de fundos sem edição de imagem |
| Google Fonts | Roboto + Bricolage Grotesque |
| Circular Std (OTF) | Fonte primária da marca, embutida em base64 |
| SVG inline | Formas geométricas e ícones |

---

## Características Técnicas

- **Arquivo único** — todo o conteúdo (fontes, imagens, código) está embutido em um único `.html`
- **Funciona offline** — não depende de servidor ou conexão após o carregamento
- **Sem dependências externas** — nenhuma biblioteca JavaScript (jQuery, GSAP, etc.)
- **Responsivo** — adaptado para desktop e mobile
- **Acessível** — suporte nativo a `prefers-reduced-motion` para usuários com sensibilidade a movimento
- **Performance** — animações exclusivamente em `transform` e `opacity`, rodando na GPU sem reflow

---

## Fontes Utilizadas

- **Circular Std** — Light, Book, Medium, Bold, Black (família completa)
- **Roboto** — Light, Regular, Medium, Bold (Google Fonts)
- **Bricolage Grotesque** — Light, Regular, Medium, SemiBold, Bold (Google Fonts)

---

## Paleta de Cores

| Nome | HEX | Referência |
|---|---|---|
| Rubine | `#CE0058` | Pantone Rubine Red C |
| Aqua | `#00C1D4` | Pantone 3115 C |
| Lead | `#252525` | CMYK 0 0 0 K93 |
| Gray | `#727272` | CMYK 0 0 0 K70 |
| Off White | `#F9F9F9` | CMYK 0 0 0 K5 |

---

## Como Visualizar

Baixe o arquivo `quadoo-publicacao.html` e abra diretamente em qualquer navegador moderno (Chrome, Firefox, Safari, Edge). Nenhuma instalação necessária.

Para hospedar e compartilhar o link com qualquer pessoa:

1. Acesse [netlify.com/drop](https://netlify.com/drop)
2. Arraste o arquivo `quadoo-publicacao.html` para a área indicada
3. Copie o link gerado e compartilhe

---

## Sobre a Quadoo

**Quadoo Arquitetura Corporativa** é uma empresa especializada em transformar ambientes de trabalho em espaços que refletem a identidade e os valores das organizações. A comunicação visual é parte central de cada projeto — do briefing à entrega final.

> *"It all starts in the workplace."*

---

*Publicação desenvolvida com HTML, CSS e JavaScript puros — sem frameworks, sem bibliotecas, sem limites.*
