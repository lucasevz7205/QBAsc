# QUEBRANDO A BANCA — A ASCENSÃO
## Design system | Guia de identidade e interface | V1

### Visão geral
Quebrando a Banca: A Ascensão é uma plataforma de aprendizagem estratégica para concursos públicos. Sua identidade combina disciplina, conhecimento, estratégia e conquista. A estética é cinematográfica, clássica e épica, com atmosfera de ascensão a uma cidadela no alto de uma montanha. O produto deve continuar sendo uma ferramenta de estudo altamente legível, acessível e cognitivamente eficiente, não uma tela de jogo sobrecarregada.

**Lema:** Conhecimento · Estratégia · Disciplina · Conquista.

### Fontes e fidelidade
- Os símbolos, cenários e composição de marca derivam das imagens de referência fornecidas pelo proprietário do projeto.
- As cores de interface `#0A1E34`, `#173653`, `#A58A67`, `#D0B386`, `#F1E8D5`, `#A92E3A` foram verificadas no CSS existente da aplicação Base44.
- As cores adicionais para a identidade ilustrada são aproximações visuais e precisam de validação com os arquivos originais de arte. Não devem ser tratadas como amostras oficiais de um arquivo vetorial.

## 1. Cores

### Núcleo existente e confirmado no código
| Token | HEX | Uso |
|---|---|---|
| `colors.navy-deep` | `#0A1E34` | Fundo principal das áreas de estudo |
| `colors.navy-raised` | `#173653` | Superfícies, painéis e cartões |
| `colors.bronze` | `#A58A67` | Bordas, separadores e ornamentos discretos |
| `colors.gold-muted` | `#D0B386` | Destaques, controles selecionados e foco |
| `colors.ivory` | `#F1E8D5` | Texto de alta prioridade sobre fundos escuros |
| `colors.crimson` | `#A92E3A` | Estado de alerta e acentos rubros |

### Extensão cinematográfica estimada das referências
| Token | HEX aproximado | Uso |
|---|---|---|
| `colors.obsidian` | `#080A0F` | Fundo dos emblemas e aberturas |
| `colors.midnight` | `#101C2D` | Céu noturno e superfícies profundas |
| `colors.steel-blue` | `#344E70` | Céu, névoa e painéis secundários |
| `colors.moonlight` | `#C8D9EA` | Luz fria noturna, nunca texto de corpo sem testar contraste |
| `colors.gold-bright` | `#F2C76E` | Reflexos e pontos de luz do metal dourado |
| `colors.gold-shadow` | `#87541F` | Sombra do metal e gradientes ilustrativos |
| `colors.ribbon-red` | `#B91522` | Faixa da espada e detalhes de marca |
| `colors.ribbon-highlight` | `#E43B35` | Reflexos da faixa vermelha |
| `colors.stone` | `#8C8278` | Rochas e arquitetura clássica |
| `colors.parchment` | `#E9DDC7` | Textos ornamentais, títulos secundários |

### Tokens semânticos de produto
- `colors.canvas = #0A1E34`
- `colors.surface = #173653`
- `colors.surface-deep = #080A0F`
- `colors.text-primary = #F1E8D5`
- `colors.text-secondary = #E9DDC7`
- `colors.border = #A58A67`
- `colors.accent = #D0B386`
- `colors.accent-hero = #F2C76E`
- `colors.alert = #A92E3A`
- `colors.focus = #F2C76E`
- Estados de acerto, erro, progresso e ausência de evidência devem ter tokens semânticos próprios, acompanhados de ícones/texto. Não reutilizar vermelho decorativo como indicador automático de erro.

### Regras de contraste
Texto normal com contraste mínimo WCAG AA de 4,5:1; texto grande e elementos não textuais essenciais com mínimo 3:1. Não presumir que `#D0B386` ou `#A58A67` funcionem em qualquer fundo. Verificar combinações em contexto, inclusive sobre imagens.

## 2. Identidade visual e assets

### Marca principal
Espada vertical de metal prateado e dourado, envolvida por arco/anel dourado, com fita vermelha em movimento; montanhas douradas ou rochosas na composição ampla. Palavra-marca **QUEBRANDO A BANCA**, subtítulo **A ASCENSÃO**. Louros dourados são ornamentos opcionais de composições institucionais.

### Variantes simbólicas
- **O Soldado:** elmo clássico com crista rubra. Representa disciplina e ação.
- **O Sábio:** coruja dourada, livro aberto e louros. Representa conhecimento e reflexão.
- **O Estrategista:** tabuleiro de estratégia com peças e louros. Representa visão e decisão.
- **A Ascensão:** templo/cidadela no cume e estrada ascendente rubra. Representa a união das virtudes na conquista.

Esses quatro símbolos são imagens de marca, não emojis ou ícones genéricos. Podem servir como marcos de jornada e gamificação, mas não devem substituir indicadores objetivos de desempenho.

### Aplicações
- **Logo horizontal:** espada, anel e fita à esquerda; palavra-marca e subtítulo à direita.
- **Logo vertical:** símbolo central acima da palavra-marca.
- **Ícone do app:** espada, anel e montanhas em placa quadrada com cantos arredondados.
- **Símbolos reduzidos:** montanha, espada, montanha com fita, espada com anel e fita; usar em contextos com pouco espaço e conferir reconhecimento a 24–32 px.
- **Fundo diurno:** templo monumental em penhasco, céu azul, nuvens claras, escadaria sinuosa e espada fincada na rocha.
- **Fundo noturno:** a mesma composição, céu azul profundo, lua e iluminação quente da cidadela.
- **Artefato ornamental:** disco circular de bronze com gravuras antigas; usar em selos, marcos e cenas de transição, nunca como controle sem rótulo.

### Hierarquia de uso das imagens
1. Marca principal e tela de boas-vindas: composição épica completa.
2. Dashboard: banner cinematográfico restrito ao cabeçalho, com contraste e overlay.
3. Sessões de estudo: fundos discretos ou planos, sem competir com a leitura.
4. Questões, flashcards, mapas e revisões: priorizar legibilidade, velocidade e foco.
5. Emblemas e medalhas: usar como reforço secundário, não como substituto de informação pedagógica.

## 3. Tipografia
- **Marca e títulos cerimoniais:** serifada clássica de alto contraste, inspirada na referência; opções de implementação: Cinzel (títulos de marca) e Cormorant Garamond (subtítulos), sujeitas a teste de legibilidade. Não afirmar que sejam as fontes originais da imagem.
- **Títulos de conteúdo:** Georgia ou uma serifada editorial de boa leitura.
- **Corpo e UI:** Inter, system-ui, sans-serif, para precisão e acessibilidade.
- **Dados e códigos:** JetBrains Mono ou ui-monospace.

Escala recomendada: display 48–64 px desktop e 32–40 px mobile; H1 32 px; H2 24 px; H3 20 px; corpo 16–18 px com line-height 1,5–1,65; legenda 13–14 px; rótulos de controles 14–16 px. Evitar letras excessivamente espaçadas em textos longos.

## 4. Layout e tokens dimensionais
- Base de espaçamento: 4 px; escala 4, 8, 12, 16, 24, 32, 48, 64, 96 px.
- Largura de conteúdo: máximo 1200–1280 px; leitura longa ideal até 65–75 caracteres por linha.
- Cartões: raio 16–20 px; campos e botões: 10–14 px; emblemas podem ter forma circular.
- Alvos de toque: pelo menos 44 × 44 px como meta do produto.
- Breakpoints propostos: mobile <640 px; tablet 640–1023 px; desktop >=1024 px.
- Zoom 200%, navegação por teclado e preferência por movimento reduzido obrigatórios.

## 5. Componentes
- `BrandHeader`: logo horizontal, navegação, busca, notificações e perfil; variante compacta durante o estudo.
- `HeroAscension`: composição panorâmica dia/noite com sobreposição escura legível e chamada discreta.
- `RadialNavigation`: atalhos do dashboard; alternativa linear acessível e responsiva.
- `StudySessionHeader`: matéria, assunto, progresso, tempo e opção de modo foco.
- `QuestionCard`: enunciado CEBRASPE, Certo/Errado, confiança, comentário e remissão ao conceito.
- `AnswerActionBar`: confirmar, revisar, pular quando permitido, estados disabled/loading.
- `FeedbackDrawer`: gabarito, fundamento, mecanismo de pegadinha e vínculo ao mapa.
- `MindMapCanvas`: mapa espacial/3D com foco, zoom, pan, expansão de ramos e fallback em lista.
- `ConceptPanel`: conteúdo do nó, exemplos, conexões, revisão ativa e fontes.
- `Flashcard`: frente, verso, autoavaliação e próxima revisão; manter SRS e dados reais fora do escopo do mockup.
- `CognitiveAlertBanner`: alerta de fadiga, atenção ou pegadinha sem diagnóstico fictício.
- `AchievementEmblem`: variantes Soldado, Sábio, Estrategista e Ascensão, ligadas a regras explícitas de progresso.
- `DesignSystemGallery`: tokens, componentes, estados, exemplos responsivos e acessibilidade.

### Estados obrigatórios
Default, hover, focus-visible, active/selected, loading, empty, error, disabled, reduced-motion e mobile. Respostas e progresso não podem ser comunicados somente por cor.

## 6. Comportamento e princípios pedagógicos
- Carga cognitiva mínima durante questões e revisões; cinematografia apenas em navegação, marcos e recompensas.
- Revelação progressiva de informações e justificativas.
- Remissão precisa: questão → nó exato do mapa → retorno à questão, preservando contexto.
- Flashcard → conceito original; preservar a origem e o estado da revisão.
- CEBRASPE Certo/Errado com justificativa conceitual, rastreabilidade e identificação do mecanismo de falsificação.
- IA tutora contextual, diagnóstico e SRS devem ser projetados com estados honestos de demonstração: não alegar conexão real, memória persistente ou adaptação se ainda não implementadas.
- Preservar usuários, permissões, histórico, IDs, conteúdo e algoritmo pedagógico na eventual integração.

## 7. Exemplo de CSS de tokens
```css
:root {
  --qb-canvas: #0A1E34;
  --qb-surface: #173653;
  --qb-obsidian: #080A0F;
  --qb-bronze: #A58A67;
  --qb-gold: #D0B386;
  --qb-gold-bright: #F2C76E;
  --qb-ivory: #F1E8D5;
  --qb-crimson: #A92E3A;
  --qb-ribbon-red: #B91522;
  --qb-stone: #8C8278;
  --qb-radius-control: 12px;
  --qb-radius-card: 18px;
  --qb-space-unit: 4px;
}
```

## 8. Instruções para o Claude Design
Crie um design system reutilizável chamado **Quebrando a Banca — A Ascensão**. Use as imagens anexadas como fontes primárias da identidade visual. Preserve os símbolos e cenas como imagens, não os redesenhe automaticamente. Utilize os hex confirmados para a interface e os hex estimados apenas como pontos de partida para a direção de arte. Gere componentes navegáveis, estados acessíveis, telas desktop/tablet/mobile e uma biblioteca visual. A experiência deve parecer uma jornada épica na navegação, mas um instrumento de estudo claro e preciso durante a aprendizagem. Não conectar à Base44, não alterar dados e não declarar IA real onde há apenas simulação.
