# FACERJ — Design System para Sites e Páginas

**Versão:** 1.0  
**Status:** Diretriz visual e funcional  
**Marca:** FACERJ Aikido  
**Objetivo:** estabelecer padrões consistentes para criação, evolução e manutenção de sites, landing pages, páginas institucionais, artigos, campanhas e infográficos da FACERJ.

---

## 1. Essência da marca

A identidade digital da FACERJ deve comunicar:

- **Tradição:** respeito à história e aos fundamentos do Aikido.
- **Disciplina:** organização, precisão e consistência visual.
- **Autoridade:** comunicação institucional clara e confiável.
- **Equilíbrio:** composição harmoniosa, sem excesso de elementos.
- **Acolhimento:** uma instituição séria, acessível a praticantes, famílias, interessados e parceiros.

### Princípio central

> Tradicional na essência, contemporânea na experiência.

A interface deve parecer institucional e marcial, nunca uma página genérica de academia fitness, loja esportiva ou marca de entretenimento.

## 2. Logotipo e uso da marca

Utilizar os arquivos oficiais do logotipo FACERJ fornecidos pela instituição.

### Regras

- Preservar proporções, geometria, cores e legibilidade do símbolo.
- Não redesenhar, distorcer, inclinar, esticar ou aplicar efeitos ao logotipo.
- Não alterar as letras, o símbolo ou a URL incorporada nas versões oficiais.
- Manter área livre ao redor do logo, equivalente a pelo menos a largura do traço principal do símbolo ou 5% da largura total do logo — usar o maior valor que garanta boa leitura.
- Usar a versão horizontal em cabeçalhos largos e rodapés; a versão vertical em espaços estreitos ou peças com composição vertical, quando adequada.
- Preferir fundo Branco Washi ou branco neutro. Em fundo escuro, usar somente uma versão oficial aprovada para esse contexto.
- Não colocar o logo sobre imagens ou texturas que prejudiquem a leitura.
- Não recriar o logo com texto digitado quando o arquivo oficial estiver disponível.

**Importante:** o endereço `www.facerj.com.br` faz parte de uma das versões fornecidas do logo. Verificar se a URL continua correta antes de reutilizá-la em novas peças.

## 3. Paleta de cores

A paleta é baseada no arquivo de identidade visual fornecido. O azul é a cor principal; preto e branco sustentam o contraste. As cores complementares devem aparecer com moderação.

| Token | Nome | HEX | Uso |
|---|---|---|---|
| `color-primary` | Azul Bushidō | `#1F4E8C` | Identidade principal, links, botões primários, ícones e destaques |
| `color-text` | Preto Sumi | `#0D0D0D` | Textos, títulos, bordas fortes e ícones |
| `color-background` | Branco Washi | `#F5F5F2` | Fundo principal e áreas de leitura |
| `color-accent` | Vermelho Torii | `#C1121F` | Alertas e chamadas pontuais; uso moderado |
| `color-wood` | Marrom Madeira Dojo | `#6B4F3A` | Seções secundárias e detalhes de apoio |
| `color-gold` | Dourado Envelhecido | `#C6A85C` | Marcos históricos, certificações e detalhes premium |
| `color-night` | Azul Noturno | `#0F2A44` | Fundos escuros, banners institucionais e rodapés |

### Proporção de uso sugerida

- **60–70%:** Branco Washi ou superfícies claras.
- **20–30%:** Azul Bushidō e Azul Noturno.
- **Até 10%:** preto e cores de apoio combinados, sem competir com o azul.

Essas proporções são referências, não regras rígidas. O conteúdo e a acessibilidade têm prioridade.

### Regras de aplicação

- Não introduzir novas cores de marca sem aprovação.
- Evitar azul-claro genérico, neon, vermelho puro (`#FF0000`) e gradientes chamativos.
- Não usar o vermelho como cor dominante.
- Garantir contraste suficiente entre texto e fundo. Não confiar apenas na cor para comunicar estados ou categorias.
- Em interfaces digitais, validar combinações de contraste conforme WCAG 2.2 AA: em geral, 4,5:1 para texto comum e 3:1 para texto grande e componentes gráficos relevantes.

## 4. Tipografia

### Direção

Usar tipografia sem serifa, contemporânea, sólida e legível. A identidade deve transmitir clareza e autoridade, sem parecer excessivamente tecnológica.

### Sugestão de famílias

- **Primária:** `Inter` ou `Source Sans 3`.
- **Alternativa de sistema:** `Arial`, `Helvetica`, sans-serif.
- **Fonte decorativa:** uma fonte de pincel ou caligrafia japonesa pode aparecer em peças editoriais especiais, nunca em textos longos, navegação ou informações essenciais.

A escolha final deve respeitar licenças, desempenho e disponibilidade.

### Escala tipográfica sugerida

| Elemento | Desktop | Mobile | Peso sugerido |
|---|---:|---:|---|
| H1 | 40–56 px | 32–40 px | 700–800 |
| H2 | 32–40 px | 26–32 px | 700 |
| H3 | 24–28 px | 22–26 px | 600–700 |
| H4 | 20–22 px | 18–20 px | 600 |
| Corpo | 16–18 px | 16–18 px | 400 |
| Texto auxiliar | 14–15 px | 14–15 px | 400 |
| Legendas | 12–14 px | 12–14 px | 400 |

Usar `rem` sempre que possível e permitir zoom sem perda de conteúdo. Evitar parágrafos extensos em caixa alta. Reservar caixa alta para siglas, rótulos curtos e usos oficiais da marca.

## 5. Layout e espaçamento

### Princípios

- Layout limpo, com hierarquia visual clara e áreas de respiro.
- Conteúdo organizado em blocos curtos e escaneáveis.
- Alinhamento consistente entre títulos, textos, imagens e chamadas para ação.
- Evitar ornamentos que não ajudem a compreender o conteúdo.
- Priorizar leitura e navegação antes de efeitos visuais.

### Grade e dimensões

- Largura máxima de conteúdo: `1200–1280px`.
- Largura máxima de leitura de texto corrido: `65–75ch`.
- Margens laterais responsivas: `24px` em telas médias e grandes; `16–20px` em telas pequenas.
- Grade desktop: 12 colunas, com espaçamento de `24px`.
- Grade tablet: 6 ou 8 colunas conforme o conteúdo.
- Grade mobile: 4 colunas ou fluxo de uma coluna.
- Espaçamentos baseados em múltiplos de 4 ou 8px.

### Escala de espaçamento

`4 / 8 / 12 / 16 / 24 / 32 / 48 / 64 / 80 / 96px`

Usar espaçamento para agrupar elementos relacionados e separar seções distintas. Evitar interfaces comprimidas ou com grandes vazios sem propósito.

## 6. Formas, bordas e profundidade

- Preferir geometria precisa, linhas finas e círculos inspirados no emblema da FACERJ.
- Usar círculos, arcos e divisões radiais como detalhes gráficos discretos, nunca como decoração excessiva.
- Bordas padrão: `1px solid` em tons neutros ou azul com baixa intensidade.
- Raio de borda: `4–8px` para cards e campos; `2–4px` para botões institucionais, quando adequado.
- Sombras suaves e raras. Evitar aparência de cartões flutuantes em excesso.
- Não aplicar efeitos 3D, brilho, bevel ou gradientes pesados ao logo e aos elementos institucionais.

## 7. Elementos gráficos e fotografia

### Texturas e referências

- Papel japonês (*washi*) como textura muito sutil.
- Pinceladas inspiradas em *sumi-e* apenas em materiais editoriais ou campanhas específicas.
- Linhas técnicas, círculos e formas radiais derivadas do símbolo da marca.
- Fotografia real de treinos, seminários, mestres, praticantes e eventos da FACERJ sempre que houver material autorizado.

### Tratamento de imagens

- Preferir imagens nítidas, naturais e com boa iluminação.
- Usar contraste equilibrado; versões em preto e branco ou com predominância de azul podem ser utilizadas em campanhas.
- Não aplicar filtros que distorçam a cor dos uniformes, das faixas ou das pessoas.
- Confirmar autorização de uso de imagem, especialmente para menores de idade.
- Evitar imagens genéricas de artes marciais que representem técnicas, uniformes ou tradições de forma incorreta.
- Usar texto alternativo descritivo em imagens informativas; imagens puramente decorativas devem ter alternativa vazia quando implementadas em HTML.

## 8. Iconografia

- Preferir ícones simples, lineares e consistentes.
- Manter a mesma família visual, espessura de traço e escala em toda a interface.
- Usar ícones para reforçar significado, nunca para substituir rótulos pouco claros.
- Evitar misturar emojis, ícones 3D e pictogramas de estilos diferentes em páginas institucionais.
- Elementos japoneses devem ser usados com contexto e respeito, sem virar decoração temática genérica.

## 9. Componentes de interface

### Cabeçalho

- Logo em tamanho suficiente para reconhecimento, sem dominar a página.
- Navegação curta e previsível.
- Links com estados visíveis de hover e foco.
- Em mobile, menu acessível por teclado e leitor de tela.
- CTA principal opcional: “Conheça a FACERJ”, “Encontre um dojo” ou “Entre em contato”, conforme o objetivo da página.

### Botões

**Primário**
- Fundo: Azul Bushidō (`#1F4E8C`).
- Texto: Branco (`#FFFFFF`) para contraste.
- Uso: ação principal da página.

**Secundário**
- Fundo transparente ou Branco Washi.
- Borda: Azul Bushidō.
- Texto: Azul Bushidō.

**Ação crítica ou destaque**
- Vermelho Torii (`#C1121F`) somente quando o contexto justificar, não como padrão para todos os CTAs.

Estados obrigatórios: padrão, hover, foco visível, pressionado, desabilitado e carregando quando aplicável. A área de interação deve ser confortável, preferencialmente com pelo menos 44 × 44px em dispositivos touch.

### Links

- Cor azul com sublinhado em contextos de leitura.
- Não diferenciar links apenas pela cor.
- Estado de foco claramente visível.
- Texto do link deve descrever o destino; evitar “clique aqui”.

### Cards

- Usar para conteúdos relacionados: notícias, eventos, dojos, cursos ou materiais.
- Título claro, descrição breve e ação identificável.
- Imagens com proporção consistente dentro de cada conjunto.
- Evitar colocar cada parágrafo em um card.

### Formulários

- Rótulos persistentes acima dos campos.
- Indicar campos obrigatórios de forma explícita.
- Mensagens de erro próximas ao campo, em linguagem clara e com orientação para correção.
- Preservar os dados digitados quando houver erro.
- Não usar placeholder como único rótulo.
- Informar como os dados serão utilizados quando houver coleta de informações pessoais.

### Alertas e avisos

- Azul para informação.
- Vermelho para erro ou situação crítica.
- Dourado ou marrom para observações e avisos não críticos.
- Sempre combinar cor com ícone ou texto explícito.

### Citações e dados históricos

- Utilizar Azul Noturno, Azul Bushidō ou Dourado Envelhecido com moderação.
- Dar destaque à fonte, data e contexto.
- Não apresentar datas, graduações, títulos ou números institucionais sem validação.

## 10. Padrões de páginas

### Página inicial

1. Cabeçalho com logo e navegação.
2. Área principal com proposta institucional objetiva.
3. Apresentação da FACERJ e do Aikido.
4. Conteúdos prioritários: dojos, eventos, formação ou notícias.
5. Evidências institucionais verificáveis.
6. Chamada para ação principal.
7. Rodapé com contatos, navegação secundária e informações legais.

### Página institucional / Sobre

- Apresentar missão, atuação, história e valores com linguagem objetiva.
- Usar linha do tempo quando houver marcos históricos confirmados.
- Priorizar fotografias e documentos reais.
- Evitar afirmações grandiosas sem fonte ou comprovação.

### Página de dojo ou unidade

- Nome e localização.
- Instrutores e credenciais confirmadas.
- Horários e informações de contato atualizados.
- Faixa etária, acessibilidade e condições de participação, quando aplicável.
- Mapa ou orientação de chegada, se relevante.
- CTA para contato ou aula experimental, quando disponível.

### Página de evento

- Nome, objetivo, data, horário e local.
- Público-alvo, requisitos, programação e responsáveis.
- Instruções de inscrição, valores e prazos confirmados.
- Avisos sobre cancelamento, acessibilidade e uso de imagem, quando aplicável.
- Estado da inscrição claramente indicado.

### Artigo ou conteúdo educativo

- Título descritivo e introdução curta.
- Subtítulos hierárquicos.
- Parágrafos curtos, listas e imagens contextualizadas.
- Autor, data e referências quando pertinentes.
- Links relacionados e chamada final não intrusiva.

### Landing page de campanha

- Uma meta principal por página.
- Proposta de valor clara na primeira tela.
- Evidências e contexto antes de pedir uma conversão.
- CTA consistente e repetido apenas quando fizer sentido.
- Reduzir distrações sem ocultar informações importantes.

## 11. Tom de voz e conteúdo

A comunicação deve ser:

- **Respeitosa:** sem agressividade, humilhação ou linguagem de confronto.
- **Clara:** explicar termos japoneses quando necessário.
- **Institucional:** segura e objetiva, sem parecer burocrática.
- **Acolhedora:** convidar pessoas de diferentes níveis de experiência.
- **Responsável:** distinguir fatos, opiniões e informações ainda não confirmadas.

Evitar promessas absolutas, sensacionalismo, clichês de marketing e alegações não verificadas sobre benefícios físicos, psicológicos ou terapêuticos.

## 12. Responsividade

Projetar primeiro para conteúdo e legibilidade; adaptar a composição para cada tela.

Pontos de referência sugeridos:
- Mobile: até `767px`.
- Tablet: `768–1023px`.
- Desktop: a partir de `1024px`.

Esses breakpoints podem variar conforme o layout. Validar no mínimo:
- 320px de largura;
- 375–390px;
- 768px;
- 1024px;
- 1440px ou superior.

Não permitir rolagem horizontal involuntária, texto cortado, botões sobrepostos ou imagens distorcidas. Menus, tabelas e diagramas devem ter comportamento apropriado em telas pequenas.

## 13. Acessibilidade

Adotar WCAG 2.2 nível AA como referência.

- Estruturar páginas com títulos semânticos e ordem lógica.
- Garantir navegação completa por teclado.
- Manter foco visível e não encoberto.
- Usar contraste adequado para texto e controles.
- Associar campos a rótulos programáticos.
- Fornecer textos alternativos úteis para imagens informativas.
- Legendar vídeos com fala relevante.
- Não transmitir informações apenas por cor, posição ou forma.
- Respeitar a preferência `prefers-reduced-motion`.
- Evitar animações desnecessárias, flashes e movimento automático.
- Usar linguagem de link e botão que descreva sua finalidade.

## 14. SEO, desempenho e compartilhamento

- Usar um único H1 descritivo por página, sempre que possível.
- Manter títulos de página e descrições meta específicos.
- Usar URLs legíveis e estrutura de navegação coerente.
- Comprimir imagens e usar formatos modernos quando suportados.
- Definir dimensões de imagem para reduzir mudanças de layout.
- Carregar imagens fora da primeira tela de forma preguiçosa, quando adequado.
- Evitar scripts, fontes e bibliotecas desnecessárias.
- Criar metadados Open Graph para compartilhamento.
- Adicionar dados estruturados somente quando corresponderem a informações reais e verificáveis.
- Monitorar Core Web Vitals e corrigir problemas de estabilidade visual e carregamento.

## 15. Privacidade e confiança

- Coletar somente os dados necessários para a finalidade informada.
- Publicar política de privacidade e informações de contato adequadas.
- Solicitar consentimento quando exigido e explicar o uso dos dados.
- Não expor dados pessoais em páginas públicas.
- Tratar imagens e informações de crianças e adolescentes com cuidado especial.
- Garantir que formulários e integrações utilizem conexões seguras.
- Não criar depoimentos, credenciais, estatísticas ou certificações fictícias.

## 16. Tokens de design para implementação

Exemplo de tokens CSS que podem ser adaptados ao projeto:

```css
:root {
  /* Marca */
  --color-primary: #1F4E8C;
  --color-text: #0D0D0D;
  --color-background: #F5F5F2;
  --color-accent: #C1121F;
  --color-wood: #6B4F3A;
  --color-gold: #C6A85C;
  --color-night: #0F2A44;

  /* Superfícies e bordas */
  --color-surface: #FFFFFF;
  --color-border: #D7D9DD;
  --color-muted: #5D626A;
  --color-focus: #1F4E8C;

  /* Tipografia */
  --font-family-base: Inter, "Source Sans 3", Arial, sans-serif;
  --font-size-small: 0.875rem;
  --font-size-base: 1rem;
  --font-size-large: 1.125rem;
  --line-height-body: 1.6;
  --line-height-heading: 1.15;

  /* Espaçamento: múltiplos de 4px */
  --space-1: 0.25rem;
  --space-2: 0.5rem;
  --space-3: 0.75rem;
  --space-4: 1rem;
  --space-6: 1.5rem;
  --space-8: 2rem;
  --space-12: 3rem;
  --space-16: 4rem;

  /* Geometria */
  --content-max-width: 80rem;
  --reading-max-width: 72ch;
  --radius-small: 0.25rem;
  --radius-medium: 0.5rem;
  --border-width: 1px;

  /* Movimento */
  --motion-fast: 120ms;
  --motion-standard: 200ms;
}
```

Os tokens são uma base inicial. Validar o contraste de cada combinação antes de aplicar em produção.

## 17. Checklist antes de publicar

- [ ] O logo oficial está correto e sem distorção?
- [ ] A paleta está consistente com a identidade FACERJ?
- [ ] O conteúdo está correto, atualizado e aprovado?
- [ ] A página funciona em mobile, tablet e desktop?
- [ ] O contraste e o foco por teclado foram verificados?
- [ ] Links, botões, formulários e menus funcionam?
- [ ] Imagens têm autorização de uso e tratamento adequado?
- [ ] Títulos, metadados e textos alternativos foram revisados?
- [ ] Não há informações institucionais inventadas ou desatualizadas?
- [ ] A página carrega sem scripts ou efeitos desnecessários?
- [ ] A política de privacidade e a coleta de dados são adequadas?

## 18. Regra final de consistência

Toda página nova da FACERJ deve parecer parte do mesmo sistema visual, mesmo quando tiver objetivos diferentes. A identidade deve ser reconhecível pela combinação de azul profundo, preto, fundo claro, geometria precisa, tipografia legível e comunicação respeitosa.

Quando houver conflito entre estética e clareza, acessibilidade, veracidade ou facilidade de uso, **priorizar clareza, acessibilidade, veracidade e facilidade de uso**.

---

**Documento-base:** identidade visual e paleta FACERJ fornecidas pelo usuário.  
**Observação:** este arquivo é uma diretriz de design; detalhes institucionais, endereços, credenciais, dados históricos e informações operacionais devem ser validados pela FACERJ antes da publicação.
