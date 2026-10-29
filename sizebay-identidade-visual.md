# Identidade visual Sizebay — referências e regras

> Use este arquivo sempre que o assunto for **identidade visual da Sizebay** (posts, carrosséis, anúncios, materiais).
> As referências abaixo servem de **inspiração de linguagem**, não de cópia: recrie, não duplique layouts.

## 1. Referências no Figma

| # | Referência | Link | O que aprender |
|---|-----------|------|----------------|
| 1 | **Carrossel Material Rico** (`20082026 Carrossel Material Rico Social`) | https://www.figma.com/design/Xxpg0tKFjwtrvFbwghJ9TP/Redes-Sociais?node-id=12285-14655 | Referência principal para carrosséis: fundo azul-claro "vidro", texto centralizado, cards brancos, painel azul-escuro |
| 2 | **Campanhas** (anúncios Provador Virtual) | https://www.figma.com/design/1obt69r7jv7BCcWXk2anZS/Campanhas?node-id=5603-301 | Anúncios 1:1 e 9:16: headline condensada em caixa alta, tags, botões CTA, mockups de produto, variações claro/escuro |
| 3 | **Redesign do Site** (Home e páginas) | https://www.figma.com/design/Ed1Fk79P9lUw3tjJozOLDA/Redesign-Site?node-id=766-249 | Hero com foto de moda, seções de dados em cards, UI de produto, CTA em roxo no site (web, não usar no social) |
| 4 | **Brandbook 2026** (biblioteca de variáveis e estilos) | Biblioteca "Sizebay Brandbook 2026", ativa no arquivo Larissa Size | Paleta oficial (variáveis `Cor/...`) |
| 5 | Post LinkedIn "There are only three paths" (`17092026 Estático Linkedin Material Rico v2`) | arquivo Larissa Size, página *Proposta Redes Sociais*, node `12:5217` | Headline condensada branca sobre céu azul, logo-tag no topo |

Arquivo de trabalho dos carrosséis: https://www.figma.com/design/CVTv0X2kBSGmJ290pbYKHC/Larissa-Size (página *Redes Sociais*).
Carrossel WGSN criado a partir destas referências: artboard `30102026 Linkedin Pesquisa WGSN` (node `243:694`), 8 slides de 1080×1350.

## 2. Direção criativa (do arquivo "Proposta Redes Sociais")

- O feed alterna entre **FASHION** (foto, styling), **GRAPHIC** (tipografia, formas, composição) e **TECH** (produto, dados, inovação).
- Menos "comercial pastelaria" (produto + texto + CTA em toda peça). Mais personalidade visual e headline que já carrega conceito.
- A Sizebay é tech sem deixar de ser fashion. Referências: design editorial, capas de revista, cultura visual de moda.
- Evitar excesso de imagens geradas por IA; variar o repertório visual.

## 3. Cores (variáveis do Brandbook 2026)

Sempre que possível, **aplicar as variáveis da biblioteca** (não hex solto).

| Variável | Hex | Uso típico |
|----------|-----|-----------|
| Cor/1 Azul/Azul 50 | `#E6F4FF` | Topo do fundo claro |
| Cor/1 Azul/Azul 100 ⭐ | `#D2ECFF` | Textos secundários sobre escuro, superfícies suaves |
| Cor/1 Azul/Azul 200 | `#A8D8FA` | Base do fundo claro, linhas, trilhas |
| Cor/1 Azul/Azul 300 | `#84C4F1` | Brilhos, anéis |
| Cor/1 Azul/Azul 400 | `#5EAFE8` | Apoio |
| Cor/1 Azul/Azul 500 | `#4299D7` | Cards/tags azuis (ex.: card "Transforme dúvidas…") |
| Cor/1 Azul/Azul 600 | `#2F82BC` | Destaques, botões, overlay inferior |
| Cor/1 Azul/Azul 700 | `#21699B` | Headline condensada sobre claro, painéis escuros |
| Cor/1 Azul/Azul 800 | `#15507A` | Texto principal sobre claro |
| Cor/1 Azul/Azul 900 | `#07385A` | Fundo escuro |
| Cor/1 Azul/Azul 950 | `#042A44` | Texto de maior contraste, CTA escuro |
| Cor/3 Verde/Verde 01 | `#A5F3E6` | Destaque sobre escuro, barras positivas |
| Cor/3 Verde/Verde 02 ⭐ | `#5EB8A9` | Badges de tamanho ideal, indicadores |
| Cor/3 Verde/Verde 03 / 04 | `#20A790` / `#008F77` | Verde mais forte |
| Fashion White v1 | `#FFFFFF` | Branco da marca |
| Black Suit v1 | `#000000` | Preto da marca (logo-tag preta) |

Amarelo `#F2B705` aparece pontualmente nos elementos de UI; usar com parcimônia.

## 4. Tipografia

- **Texto e títulos leves: Outfit** (Light, Regular, Medium, SemiBold, Bold).
  - Títulos de carrossel: Outfit **Light**, com a palavra-chave em **SemiBold** (ex.: "O custo **escondido** nas devoluções por tamanho").
  - Números grandes: Outfit Medium.
  - Corpo: Outfit Regular/Light, destaques em SemiBold.
- **Display condensado em caixa alta: Kassi (Classic)** nas headlines de impacto (anúncios e posts gráficos), sempre em caixa alta, entrelinha apertada (~0,9).
  - ⚠️ A fonte Kassi **não está instalada no ambiente do Claude**; fica indisponível para escrita via API. Fallback usado: **Bebas Neue**. Trocar para Kassi manualmente no Figma quando for headline condensada.
- Tags pequenas e botões: Outfit Medium/SemiBold em **caixa alta** com tracking aberto (ex.: "E-COMMERCE DE MODA", "SOLICITE UMA DEMONSTRAÇÃO").

## 5. Logo

- Componente **`Logo Sizebay_Brand Mark Tag`** (tag branca com wordmark preto), instância de referência no arquivo Larissa Size: node `7:702` (página *Proposta Redes Sociais*), ~200×66.
- Posição padrão: **topo, centralizado**, encostado na borda superior. Em painéis escuros pode ficar dentro do painel.
- Variante preta (tag preta com wordmark branco) aparece nos anúncios de campanha.
- Sempre reutilizar a instância/componente; nunca redesenhar o logo.

## 6. Linguagem de composição

**Fundo claro "vidro"**
- Gradiente `Azul 50 (≈5%) → Azul 200 (≈89%)`, ~187°, com listras verticais suaves (efeito vidro fosco) e leve degradê de `Azul 600` na base.

**Painel escuro**
- Retângulo arredondado (raio ~40–48) inset ~40 px da borda, gradiente `Azul 700 → Azul 900`, brilho radial em `Azul 300` no canto superior. Texto branco centralizado.

**Cards**
- Brancos, raio ~28, sombra suave azulada (`Azul 800`, ~16% de opacidade, y 8–10, blur 30). Podem ser vidro: branco 35–60% com *background blur*.
- Cartões de lista: numeral grande Outfit Light (`01`, `02`, `03`) + título SemiBold + subtítulo itálico leve.
- Card azul (`Azul 500`) com tag branca no topo para chamadas de produto.

**Tags e botões**
- Tag: retângulo/pílula branca pequena, texto caixa alta, tracking aberto.
- CTA: botão azul (`Azul 700/600`) com texto branco caixa alta, ou pílula branca com seta em círculo azul.
- Setas "→" simples no texto do CTA.

**Texto**
- Centralizado na maioria dos posts e carrosséis; headline curta + 1 linha de apoio.
- Destaque por peso (Light → SemiBold) e/ou cor (`Azul 600` sobre claro, `Verde 01` sobre escuro).

**Imagem e UI**
- Fotografia de moda editorial (pessoas diversas, cenas urbanas, sacola com o símbolo "S"), recortes, UI do Provador Virtual (manequim 3D cinza com faixas verdes de medida, badge verde com tamanho "M"/"P").
- Elementos gráficos próprios: fita métrica, anéis concêntricos, esfera luminosa, símbolo "S" grande desfocado ao fundo.
- Fontes/legais: texto pequeno (≈20–24 px) Outfit Regular, centralizado no rodapé.

## 7. Formatos

- Carrossel LinkedIn/Instagram: **1080 × 1350** (4:5). O Material Rico usa 1080 × 1440.
- Anúncios: 1080 × 1080 (1:1) e 1080 × 1920 (9:16).
- Cada slide em um frame próprio, alinhado às `Slice` da artboard para exportação.

## 8. Regras de trabalho

1. Seguir a referência como **inspiração**, não duplicar o layout.
2. Texto **100% editável** no Figma (texto vivo, auto layout, nomes de camada claros: `Título`, `Texto`, `Fonte`, `Card / ...`).
3. Aplicar **variáveis do Brandbook** nas cores; reutilizar o componente do logo.
4. Manter o copy **exatamente** como o usuário enviou (sem acrescentar dados, números ou promessas).
5. Entregar dentro da artboard indicada pelo usuário (ex.: `30102026 Linkedin Pesquisa WGSN`).
6. Quando faltar imagem real (fotos, UI), usar elementos gráficos da marca e avisar que a imagem final deve ser inserida.
