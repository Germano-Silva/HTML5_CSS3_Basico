# Curso de HTML5 e CSS3 para iniciantes.

O curso "HTML5 e CSS3 para Iniciantes", ministrado pelo professor Luiz Otávio Miranda, é um bônus do curso completo de JavaScript e TypeScript Full Stack. Nele, você aprenderá desde a estrutura básica do HTML5 até o uso avançado do CSS3 para estilização e layout. Entre os temas abordados estão: semântica no HTML5, o CSS Box-Model, seletores CSS, pseudo-classes, Flexbox, CSS Grid e media queries para responsividade. É um conteúdo essencial para quem deseja iniciar na criação de sites modernos e responsivos.

## Material utilizado

- [Visual Studio Code](https://code.visualstudio.com/)
- [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-csshttps:/)
- [Live Server](https://github.com/ritwickdey/vscode-live-server-plus-plushttps:/)
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-taghttps:/)
- [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-taghttps:/)
- [Image Preview](https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-gutter-previewhttps:/)
- [IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicodehttps:/)
- [Google Chrome](https://support.google.com/chrome/answer/95346?hl=pt-BR&co=GENIE.Platform%3DDesktophttps:/)

## Exercícios realizados

### **Introdução à seção**

Nesta curso usaremos o VS CODE, Live Server e o Google Chrome.

VS CODE como editor de texto.

No VS CODE usamos a extensão Live Server para criar um servidor onde podemos renderizar a visualização do arquivo HTML.

O Google Chrome vai ser utilizado como renderizador do arquivo HTML pelo Live Server utilizando o servidor.

---

### **Estrutura do HTML**

Tags de abertura e fechamento indicam o início e o fim de um elemento, definindo onde o conteúdo começa e termina.

Tags chamadas de auto-fechadas, não precisam de fechamento porque são auto-suficientes e não contêm conteúdo interno.

Tags podem ter atributos, que são informações extras inseridas na tag de abertura para personalizar o comportamento ou a aparência do conteúdo.

informações sobre as tags estarão no arquivo crido para a aula 01.

para melhor verificar se o seu arquivo HTML esta seguindo as normas evitando erro entrar no validador W3C no link: https://validator.w3.org/

---

### **Estrutura do HTML e Meta ViewPort**

informações sobre as tags estarão no arquivo crido para aula 02.

Nesta aula aprendemos sobre identação, utilização manual e automativa via editor de texto.

Aprendemos também para que serve a viewport, tag h1, p e br.

---

### **Atributos de id e class**

O atributo **id** identifica um elemento de forma única na página. Ele deve ser exclusivo, permitindo aplicar estilos específicos com CSS ou manipular o elemento com JavaScript. É útil para personalizar e controlar um elemento específico dentro do documento.

O atributo **class** é usado para agrupar elementos que compartilham o mesmo estilo ou comportamento. Vários elementos podem ter a mesma classe, permitindo aplicar o mesmo estilo ou manipulação a todos eles de uma vez com CSS ou JavaScript.

A especificidade no CSS3 define qual regra de estilo será aplicada a um elemento. A ordem de prioridade é: seletores de ID (mais específicos), seguidos por seletores de classe e pseudo-classes, e, por fim, seletores de tipo (tags). Quanto maior a especificidade, maior a prioridade da regra. Se duas regras tiverem a mesma especificidade, a última no código será aplicada.

---

### **Headings: do H1 ao H6**

Títulos são definidos pelas tags ```<h1>``` a ```<h6>```. O ```<h1>``` é o título mais importante e geralmente usado para o título principal da página, enquanto o ```<h6>``` é o título de menor importância. Essas tags ajudam a organizar o conteúdo de forma hierárquica, permitindo que o navegador e os motores de busca entendam a estrutura e a relevância do conteúdo na página.

---

### **Tags HTML para texto (links, imagens, etc)**

Algumas tegs têm o comportamento padrão de display: block. Isso significa que elas ocupam toda a largura disponível e começam em uma nova linha, empurrando o próximo conteúdo para baixo.

São usadas principalmente para estruturar seções maiores e separar o conteúdo visualmente, ajudando a organizar a página em blocos distintos de informação.

As tags semânticas têm um significado claro sobre o conteúdo que elas representam, enquanto as tags não semânticas não indicam diretamente o tipo de conteúdo.

Mais informações da aula 5 esta no documento HTML.

---

### **Conheça todas as tags HTML**

Link com todas as tags HTML https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element

Neste video vimos o que seria a teg navegação de forma semantica e como funciona as tags de lista ordenana e não ordenada.

Mais informações da aula 6 esta no documento HTML.

---

### **Semântica na estrutura do HTML5**

Neste video vimos como estruturar o HTML de forma sematica utilizando tags de separação.

Eu utilizei o modelo do professor e inteligencia artificial para melhor o template com base em uma loja de roupas.

Também apredemos como utilizar o validador de HTML para verificar se o mesmo esta semantico.

Mais informações da aula 7 esta no documento HTML.

---

### **Pensando em HTML e CSS**

Durante a aula foi mostrado sobre a utilização das tags e como o espaçamento delas funcionan.

Depois foi realizado o processo de tentativa de clonagem da pagina inicial da netflix utilizando os conceitos abordados na aula.

Mais informações da aula 8 esta nos documentos HTML.

---

### **Introdução ao CSS Box-Model**

Durante essa aula aprendemos como funciona o css para Box-model de forma pratica.

Documentação: https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_box_model/Introduction_to_the_CSS_box_model

---

### **Listas e Menus com HTML e CSS**

Nesta aaula aprendemos  diferença de HTML e CSS.

Aprendemos o que são listas ordenadas.

documentação link: https://www.w3schools.com/

No HTML, listas ordenadas (`<ol>`) são numeradas e usadas quando a sequência é importante. Listas não ordenadas (`<ul>`) têm marcadores e são ideais para itens sem ordem. Ambos usam `<li>` para itens, podendo ter estilos personalizados para marcadores e números.

foi realizado um piqueno projeto de menu com o que aprendemos em aula.

Para mais informações verificar os documentos html da aula 10.

---

### **Tabelas HTML**

Vimos no vídeo exemplos de tabelas HTML com títulos, descrições e rodapés. Utilizamos colspan para mesclar colunas e rowspan para mesclar linhas. As tabelas também são estilizadas com CSS para responsividade e bordas.

Para mais informações verificar os documentos html da aula 11.

---

### **Formulários e Inputs HTML - Parte 1**

[Documentação formularios](https://www.w3schools.com/html/html_forms.asphttps:/)

[HTML Input Types](https://www.w3schools.com/html/html_form_input_types.asphttps:/)

[Como estruturar um formulário HTML](https://developer.mozilla.org/pt-BR/docs/Learn/Forms/How_to_structure_a_web_formhttps:/)

---

### **Formulários e Inputs HTML - Parte 2**

Aprendemos a criar um formulário HTML com diferentes tipos de campos, incluindo texto, checkbox, radio buttons e data, além de botões para envio e reset. Exploramos atributos como `placeholder` e `required` para melhorar a experiência do usuário, e usamos o CSS para estilizar o formulário, como ao aplicar `cursor: pointer` aos `labels` para tornar a interação mais intuitiva. A organização do formulário em seções com `<section>` e separadores `<hr>` ajuda na clareza visual, facilitando o preenchimento.

---

### **Formulários e Inputs HTML - Parte 3**

Na aula, foi aprendido como utilizar diferentes tipos de inputs no HTML para criar formulários mais específicos e interativos. Com o uso de `<input>`, exploramos tipos como `date` para selecionar datas de aniversário, `datetime-local` para datas e horários completos, `time` para apenas o horário, `color` para escolher uma cor preferida, `email` para validação de e-mails, `file` para upload de arquivos com extensões específicas e `number` para selecionar números dentro de um intervalo.

---

### **Formulários e Inputs HTML - Parte 4**

Exploramos diversos elementos de entrada que tornam o preenchimento mais prático e funcional para o usuário. Usamos o tipo `password` para mascarar senhas, `range` com `datalist` para selecionar volumes com marcas visuais, `url` para validar links e `search` para criar um campo de busca. usamos também o `<select>` com `optgroup` para organizar opções em grupos, permitindo selecionar múltiplas opções. O campo `textarea` foi utilizado para textos longos.

---

### **Separando HTML e CSS em arquivos diferentes**

Para linkar um arquivo CSS ao HTML, coloca-se a tag `<link>` dentro do `<head>`, usando o atributo `href` para apontar o caminho do arquivo CSS e `rel="stylesheet"` para indicar que é uma folha de estilo.

---

### **Quem dá estilo ao HTML é o CSS**

CSS (Cascading Style Sheets) é uma linguagem de estilo usada para definir a aparência e o layout de páginas HTML. Com CSS, é possível controlar cores, fontes, espaçamentos, tamanhos e posicionamentos de elementos, separando o conteúdo da apresentação visual. Ele permite criar páginas mais organizadas, responsivas e atrativas, e funciona em conjunto com o HTML, aplicando estilos que podem ser definidos em arquivos externos, internos ou em linha, com prioridade determinada pela ordem e especificidade das regras.

Exemplo de pagina: https://codepen.io/luizomf/pen/KKNwMeG

---

### **Seletores básicos do CSS - Parte 1**

São como endereços para os elementos HTML.

Indicam quais elementos da página serão estilizados.

Exemplo: `p` seleciona todos os parágrafos.

**Tipos de Seletores**

- Simples:
  - Tipo: `p`, `div`, `span` (seleciona todos de um tipo)
  - Classe: .destaque, .importante (seleciona por classe)
- Combinadores: `div` `p` (págrafos dentro de divs), `ul` > `li` (itens de lista diretos)

**Por que usar Seletores?**

- Precisão: Estiliza exatamente onde você quer.
- Reusabilidade: Cria classes e as reutiliza.
- Manutenção: Facilita alterações em grandes projetos.

**Dicas**

- Especificidade: Quanto mais específico, maior a chance de ser aplicado.
- Herança: Algumas propriedades são herdadas.
- Cascata: A ordem das regras e a especificidade definem qual estilo é aplicado.

**Resumo Final**

- **Seletores gerais** (`*`) afetam todos os elementos.
- **Seletores de tipo** aplicam estilos a tags específicas.
- **Seletores de tipo dependente** consideram a hierarquia no HTML.
- **Seletores de classe** afetam elementos com uma classe específica.
- **Seletores de classe pai** selecionam elementos filhos dentro de um pai específico.
- **Seletores de filhos diretos** (`>`) aplicam estilo apenas aos filhos imediatos.
- **Herança de estilos** pode ser usada para propagar estilos entre elementos.

---

### **Seletores básicos do CSS - Parte 2**

**Seletores de Irmãos Adjacentes (Sibling Adjacente)**

- Sintaxe: `A + B`, onde `B` é o elemento que vem logo após `A`
- Usado para estilizar um elemento específico que vem imediatamente depois de outro no mesmo nível

**Seletores de Irmãos Gerais (General Sibling)**

- Sintaxe: `A ~ B`, onde `B` é qualquer irmão de `A` que aparece depois
- Aplica estilo a todos os elementos que seguem um elemento específico, mas não precisam ser imediatos

**Seletores de Atributo**

- Seleciona elementos com um atributo específico usando `[atributo]`
- Dá pra estilizar elementos que possuem um atributo específico, e até aplicar estilos diferentes dependendo do valor do atributo (ex.: `[atributo="valor"]`)

**Seletores de Atributo Padrão**

- Usam atributos padrão do HTML como `[checked]`
- Podem aplicar estilos a elementos que possuem atributos como `checked`, `disabled`, entre outros nativos.

---

### **Seletores de atributos do CSS**

**Seletores de Atributo com Vários Valores**

- Seleciona elementos onde um atributo contém um valor específico em uma lista, usando `[atributo~="valor"]`
- Útil para estilizar elementos que têm mais de um valor em um atributo, separados por espaços

**Seletor de Atributo com Prefixo e Traço**

- Seleciona elementos onde o atributo começa com um valor seguido de um traço, usando `[atributo|="valor"]`
- Bom para atributos que têm prefixos e valores (ex.: `pt-BR` ou `en-US`)

**Seletor de Atributo que Começa com um Valor Específico**

- Seleciona elementos onde o valor do atributo começa com algo específico, usando `[atributo^="valor"]`
- Serve para capturar elementos com valores que começam com uma palavra ou parte específica

**Seletor de Atributo que Termina com um Valor Específico**

- Seleciona elementos onde o valor do atributo termina com algo específico, usando `[atributo$="valor"]`
- Usado para pegar elementos que terminam com um valor, como extensões de arquivo (`.jpg`, `.pdf`)

**Seletor de Atributo que Contém um Valor Específico**

- Seleciona elementos onde o valor do atributo contém uma sequência específica, usando `[atributo*="valor"]`
- Útil para estilizar elementos que têm uma palavra ou parte dela dentro do valor do atributo

---

### **Pseudo-classes**

Documentação link: https://developer.mozilla.org/pt-BR/docs/Web/CSS/Pseudo-classes

Ao utilizar pseudo-classes para interações: como `:hover`, alterando estilos ao passar o mouse, `:focus` para destacar campos ativos, e `:disabled` para indicar campos desativados. A classe `.titulo` demonstra transições suaves, enquanto os estilos de links (`a`) mudam cores conforme o estado (`:link`, `:visited`, `:hover`, `:active`). Além disso, são usados seletores combinados, como `input:checked + p`, para estilizar elementos relacionados. Essa abordagem ilustra como manipular a aparência e comportamento visual de forma responsiva e interativa.

---

### **Pseudo-classe :not()**

A pseudo-classe `:not()` é usada para selecionar elementos que **não correspondem** a um seletor específico, permitindo exclusões em regras de estilo.

---

### **Pseudo-classe :nth-child()**

Aprendemos a utilizar o seletor `:nth-child()` para aplicar estilos a elementos com base em sua posição dentro de um pai. O `nth-child(odd)` seleciona elementos em posições ímpares, enquanto o `nth-child(even)` estiliza os elementos em posições pares. Com expressões como `nth-child(3n)`, é possível selecionar elementos em múltiplos de 3, e com `nth-child(3n+3)`, ajusta-se o início da sequência adicionando um deslocamento. Esses seletores permitem aplicar estilos alternados e padrões dinâmicos em listas ou outros conjuntos de elementos de forma eficiente.

---

### **Pseudo-elements**

O `::after` e o `::before` são usados para inserir conteúdo extra antes ou depois de um elemento, configurando propriedades como texto, cor e fundo. O `::first-letter` aplica estilos exclusivos à primeira letra de um parágrafo, como tamanho ou cor. Já o `::first-line` estiliza apenas a primeira linha do texto, útil para destacar introduções. O `::selection` personaliza a aparência do texto selecionado pelo usuário, enquanto o `::placeholder` altera a aparência do texto exibido como dica em campos de entrada.

---

### **Especificidade CSS**

Especificidade é a forma como o navegador decide qual regra CSS aplicar quando múltiplas regras se aplicam ao mesmo elemento. Cada seletor possui um "peso" que determina sua prioridade.

**Hierarquia de Especificidade**
1. **Estilos Inline**: possuem a maior prioridade.
2. **IDs**: têm maior peso que classes, atributos e pseudo-classes.
3. **Classes, pseudo-classes e atributos**: têm prioridade intermediária.
4. **Elementos e pseudo-elementos**: possuem o menor peso.

**Regras Gerais**
- A regra mais específica tem prioridade.
- Em caso de empate, a última regra definida no código será aplicada.
- **!important** sobrescreve a especificidade, mas deve ser usado com moderação.

**Boas Práticas**
- Use seletores com especificidade moderada para evitar conflitos.
- Evite IDs no CSS; prefira classes para maior flexibilidade.
- Mantenha o código organizado para minimizar dependência de `!important`.

links inportantes:

https://specificity.keegan.st/

https://www.w3.org/TR/selectors-3/#specificity

documentação - https://developer.mozilla.org/pt-BR/docs/Web/CSS/Specificity

---

### **Herança e as propriedades que são passadas para elementos filhos**

É utilizada para que elementos filhos possam usurfruir das caracteristicas do elemento pai, sendo útil para economizar linhas de código e manter a consistencia de estilo. Algumas propriedades não herdadas. Para que seja forçado a herança utiliza-se a propriedade `inherit`.

links inportantes:

https://www.w3schools.com/cssref/css_inherit.php

https://developer.mozilla.org/pt-BR/docs/Learn/CSS/Building_blocks/Cascade_and_inheritance

https://www.sitepoint.com/css-inheritance-introduction/

---

### **Propriedade específicas do Box-Model (largura, altura, padding, border e margin)**

**Box Model no CSS**

O Box Model define como o navegador calcula o tamanho e o espaço de um elemento HTML. Ele é composto pelas seguintes áreas:

1. **Content**: A área onde o conteúdo do elemento é exibido.
2. **Padding**: Espaço entre o conteúdo e a borda (border).
3. **Border**: A borda ao redor do padding.
4. **Margin**: Espaço externo ao redor da borda.

**Resumo do Código**

**`display`**
- `block`: Elementos ocupam toda a largura disponível.
- `inline`: Elementos ocupam apenas o espaço necessário e ignoram as propriedades `width` e `height`.

**`overflow`**
- Controla como o conteúdo que excede o tamanho do elemento é tratado:
  - `hidden`: Oculta o conteúdo excedente.
  - `scroll`: Adiciona uma barra de rolagem (sempre visível).
  - `auto`: Adiciona uma barra de rolagem apenas quando necessário.

**`box-sizing: border-box`**
- Inclui o `padding` e a `border` no cálculo do `width` e `height`, facilitando o controle do tamanho final do elemento.

**Propriedades de Dimensão**
- `width` e `height`: Determinam o tamanho básico do conteúdo.
- `max-width` / `max-height`: Limite máximo para largura e altura.
- `min-width` / `min-height`: Limite mínimo para largura e altura.

**Espaçamentos**
- `margin`: Define espaço externo ao redor do elemento.
- `padding`: Define espaço interno entre o conteúdo e a borda.

**Destaques do Código**
- O uso de `overflow` demonstra o comportamento de elementos com conteúdo excedente.
- A classe com `box-sizing: border-box` mostra como o tamanho total do elemento pode ser controlado.
- `margin: 0 auto` centraliza o elemento horizontalmente.

**Boas Práticas**
- Use `box-sizing: border-box` para facilitar o cálculo de dimensões.
- Ajuste `overflow` para controlar como o conteúdo excedente deve ser exibido.
- Combine `width`, `height`, `max-*` e `min-*` para criar layouts responsivos.

---

### **Float e Display (Block, Inline-Block e Inline)**

Float e display são propriedades fundamentais no CSS que controlam como os elementos são posicionados e comportam-se no layout da página.

**Float**
- Usado para posicionar elementos horizontalmente, removendo-os do fluxo normal do documento.
- Necessita de "clearfix" para evitar colapsos no layout ao conter elementos flutuantes.
- No código:
  - `float: left;` posiciona os elementos lado a lado.
  - A classe `.grid::after` utiliza o método "clearfix" para limpar flutuações, garantindo que o pai (.grid) se ajuste aos filhos flutuantes.

**Display**
1. **block**
   - Ocupa toda a largura disponível.
   - Quebra a linha após o elemento.
   - Ideal para estrutura de blocos no layout.

2. **inline**
   - Ocupa apenas o espaço necessário para o conteúdo.
   - Ignora propriedades `width` e `height`.
   - Usado para textos ou elementos pequenos.

3. **inline-block**
   - Combina características de `inline` e `block`.
   - Permite definir `width` e `height`, mas os elementos ficam na mesma linha.

**CSS 1 (Float)**  
- Utiliza `float: left` para criar uma grade responsiva.
- `box-sizing: border-box` garante que padding e borda sejam incluídos no tamanho total dos elementos.
- Cada `.col` ocupa 33,33% da largura da grade.

**CSS 2 (Inline)**  
- Usado `display: inline` para elementos lado a lado.
- Ignora as propriedades de dimensão (`width` e `height`).
- Funciona bem para itens pequenos, como botões ou ícones.

**CSS 3 (Inline-Block)**  
- Utiliza `display: inline-block` para alinhar elementos horizontalmente enquanto respeita as dimensões definidas.
- Resolve o problema de ignorar `width` e `height` presente em `inline`.

**Boas Práticas**
- Use `float` apenas quando necessário; prefira flexbox ou grid para layouts modernos.
- Escolha o valor de `display` baseado no comportamento desejado:
  - `block` para elementos de estrutura.
  - `inline` para itens pequenos ou texto.
  - `inline-block` para combinar flexibilidade e dimensões.
- Adote o "clearfix" para garantir o alinhamento correto em layouts flutuantes.

---

### **Cores HTML**

As cores são uma parte fundamental do design, usadas para personalizar textos, fundos, bordas e outros elementos no CSS.

**Modos de Declaração de Cores**
1. **Nome da Cor**
   - Utilize nomes pré-definidos como `red`, `blue`, `green`.

2. **RGB**
   - Define a cor com valores de vermelho, verde e azul.
   - Sintaxe: `rgb(255, 0, 0)`.

3. **RGBA**
   - Igual ao RGB, mas com um canal alfa para opacidade.
   - Sintaxe: `rgba(255, 0, 0, 0.5)` (o último valor varia entre 0 e 1).

4. **HEX**
   - Representa a cor em valores hexadecimais.
   - Sintaxe: `#FF0000` ou a versão reduzida `#F00`.

5. **HSL**
   - Baseado no matiz (hue), saturação e luminosidade.
   - Sintaxe: `hsl(0, 100%, 50%)`.

6. **HSLA**
   - Igual ao HSL, mas com o canal alfa para opacidade.
   - Sintaxe: `hsla(0, 100%, 50%, 0.5)`.

**Propriedades Principais**
- `color`: Define a cor do texto.
- `background-color`: Define a cor de fundo do elemento.
- `border-color`: Define a cor da borda.

**Opacidade**
- Controlada pela propriedade `opacity` (de 0 a 1).
- Afeta o elemento e seus filhos.

**Boas Práticas**
- Use **RGBA** ou **HSLA** para controle preciso de transparências.
- Prefira **HEX** para consistência e compatibilidade.
- Combine **HSL** com variáveis CSS para criar esquemas de cores dinâmicos e acessíveis.

**Sites importantes**

- https://coolors.co/e4572e-17bebb-ffc914-2e282a-76b041
- https://www.shutterstock.com/pt/colors/color-palette-generator
- https://www.radix-ui.com/colors/custom
- https://uicolors.app/create

---

### **Unidades de medidas no CSS (px, rem, em, vw, vh, %)**

No CSS, as unidades de medida são usadas para definir tamanhos, margens, espaçamentos e dimensões. Elas se dividem em **absolutas** e **relativas**.

**Unidades Absolutas**
- São fixas e independentes de outros elementos ou configurações do navegador.
- Exemplos:
  - **px** (pixels): Unidade fixa mais comum, representando pontos na tela.

**Unidades Relativas**
- Baseiam-se no contexto, tornando o design mais flexível e responsivo.
- Exemplos:
  - **% (porcentagem)**: Relativa ao elemento pai.
  - **em**: Relativa ao tamanho da fonte do elemento pai.
  - **rem** (root em): Relativa ao tamanho da fonte do elemento raiz (`html`).
  - **vw** (viewport width): Relativa à largura da viewport (1vw = 1% da largura da tela).
  - **vh** (viewport height): Relativa à altura da viewport (1vh = 1% da altura da tela).

**Comparação e Boas Práticas**
1. **px**
   - Ideal para elementos que exigem tamanhos fixos.
   - Menos flexível para layouts responsivos.

2. **%**
   - Excelente para larguras de containers e layouts fluidos.
   - Depende do tamanho do elemento pai.

3. **em**
   - Usado para espaçamentos ou fontes dependentes do contexto.
   - Pode acumular, dificultando cálculos.

4. **rem**
   - Mais previsível que `em`, pois sempre se refere ao elemento raiz.
   - Preferido para fontes e tamanhos escaláveis.

5. **vw e vh**
   - Ótimos para layouts responsivos em tela cheia.
   - `vw` para larguras dinâmicas e `vh` para alturas.
6. **vmin e vmax**
   - **`vmin`**: Representa 1% do menor valor entre a largura (viewport width - `vw`) e a altura (viewport height - `vh`) da viewport.
   - **`vmax`**: Representa 1% do maior valor entre a largura (`vw`) e a altura (`vh`) da viewport.
   - Ajustar tamanhos de elementos proporcionalmente à menor ou maior dimensão da tela.
   - Criar margens, paddings ou larguras/alturas adaptáveis.


**Boas Práticas**
- Use **rem** para fontes e dimensões gerais para facilitar a escalabilidade.
- Combine **%**, **vw** e **vh** para layouts responsivos.
- Evite usar apenas **px** em designs adaptativos.
- Use `vmin` para elementos que precisam se ajustar com base na dimensão mais restrita (ex.: dispositivos em modo retrato).
- Use `vmax` para elementos que se beneficiam do maior lado disponível (ex.: banners horizontais).

**Link importante**

- https://www.w3schools.com/cssref/css_units.php

---

### **Propriedades para textos**

**Propriedades de Estilo e Aparência**
- **`color`**: Define a cor do texto.
- **`background-color`**: Define a cor de fundo do elemento de texto.
- **`font-size`**: Especifica o tamanho da fonte.
- **`font-style`**: Define o estilo da fonte, como *normal*, *italic* ou *oblique*.
- **`font-weight`**: Controla a espessura da fonte (ex.: normal, bold, valores numéricos).

**Propriedades de Espaçamento e Alinhamento**
- **`letter-spacing`**: Controla o espaçamento entre letras.
- **`word-spacing`**: Controla o espaçamento entre palavras.
- **`line-height`**: Define o espaçamento vertical entre as linhas.
- **`text-align`**: Alinha o texto (ex.: left, center, right, justify).
- **`text-indent`**: Adiciona indentação à primeira linha do texto.

**Propriedades Decorativas**
- **`text-decoration`**: Adiciona efeitos decorativos, como linhas (*underline*, *overline*, *line-through*, *none*).
- **`text-shadow`**: Aplica uma sombra ao texto (eixo x, eixo y, desfoque, cor).
- **`text-transform`**: Altera a capitalização do texto (ex.: uppercase, lowercase, capitalize).

**Outras Propriedades**
- **`direction`**: Define a direção do texto (ex.: `ltr` para da esquerda para a direita ou `rtl` para da direita para a esquerda).

**Boas Práticas**
- Use **`line-height`** para melhorar a legibilidade.
- Combine **`text-align`** e **`text-indent`** para layouts estruturados.
- **`text-shadow`** deve ser usado com moderação para evitar impacto na legibilidade.
- [Propriedades de texto CSS](https://www.w3schools.com/css/css_text.asp)

---

### **Posicionamento - Position**

1. **`static`** (padrão)
   - Elementos seguem o fluxo normal do layout.
   - Não são afetados por propriedades de deslocamento como `top`, `left`, `right` ou `bottom`.

2. **`relative`**
   - Posiciona o elemento relativo à sua posição original.
   - `top`, `left`, `right`, `bottom` deslocam o elemento sem alterar o fluxo original.

3. **`absolute`**
   - Posiciona o elemento em relação ao seu elemento ancestral mais próximo com posição diferente de `static`.
   - Remove o elemento do fluxo normal do documento.
   - Exemplo: Usado para sobrepor elementos.

4. **`fixed`**
   - Posiciona o elemento em relação à viewport.
   - Fixa o elemento na tela, mesmo ao rolar a página.

5. **`sticky`**
   - Combina características de `relative` e `fixed`.
   - Fixa o elemento no momento em que ele atinge um ponto definido no scroll (`top`, `left`, etc.).

**Propriedades Complementares**
- **`z-index`**: Define a ordem de empilhamento dos elementos (camadas).
  - Elementos com valores maiores aparecem acima.
  - Valores negativos empilham os elementos abaixo.

**Casos Demonstrados no Código**

1. **Posições Relativa e Estática**
   - Elementos com `relative` podem ser deslocados de sua posição original.
   - `static` é a posição padrão e não é afetada por deslocamentos.

2. **Posição Absoluta**
   - Usada para sobrepor elementos.
   - Pode ser centralizada com deslocamentos baseados na viewport.

3. **Camadas com `z-index`**
   - Controla a sobreposição visual de elementos.
   - Elementos com maior `z-index` ficam na frente.

4. **Posição Fixa**
   - Elementos permanecem fixos na viewport, independentemente do scroll.

5. **Sticky**
   - Elementos como listas podem "grudar" no topo ou em outra posição especificada durante o scroll.

**Boas Práticas**
- Use `absolute` com cuidado para não quebrar o fluxo do layout.
- Combine `relative` com `absolute` para layouts flexíveis.
- Utilize `sticky` para cabeçalhos ou elementos que devem permanecer visíveis ao rolar a página.
- Configure corretamente o `z-index` para evitar problemas de sobreposição indesejada.

---

### **Media queries e breakpoints**

**Media Queries** são técnicas utilizadas no CSS para aplicar estilos condicionais com base nas características do dispositivo, como largura da tela, altura ou orientação. Elas são fundamentais para criar layouts responsivos que se adaptam a diferentes tamanhos de tela.

**Breakpoints** são os pontos definidos no código onde o layout muda, ajustando-se para melhorar a experiência do usuário em dispositivos variados. No código fornecido:

- **Até 568px:** As colunas ocupam 100% da largura, ideal para dispositivos móveis pequenos.
- **Entre 569px e 768px:** As colunas ocupam 50%, adequado para tablets.
- **Entre 768px e 1200px:** As colunas retornam a 33.33%, comum para telas médias e desktops pequenos.
- **A partir de 1200px:** As colunas ocupam 25%, para telas grandes e desktops amplos.
- **Layout base:** Colunas inicialmente configuradas para 33.33% de largura.
- **Responsividade:** Adaptação automática das colunas utilizando breakpoints e media queries.
- **Boas práticas:** Organize os estilos começando pelo layout mobile-first, usando `min-width` para escalonar até telas maiores.

**Links importantes**
- [DevFacts - Media Queries e Breakpoints](https://devfacts.com/media-queries-breakpoints-2021/)
- [W3Schools - Media Queries](https://www.w3schools.com/cssref/atrule_media.php)
- [MDN - Usando Media Queries](https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_media_queries/Using_media_queries)

---

### **Uma breve junção de tudo aprendido até aqui**

Foi explorado na aula as práticas modernas de design responsivo, utilizando um sistema de grade flexível que adapta colunas para diferentes tamanhos utilizando media queries (mobile-first). Inclui um menu fixo com animações suaves, estilo global para reset de margens e paddings, além de suporte a seções em tela cheia. Foca em centralização, reutilização de classes e transições para melhorar a navegação, aplicando boas práticas para garantir uma experiência consistente e otimizada em dispositivos variados.

---

### **Border-radius (elementos redondos ou curvados)**

---

### **Box-shadow (sombra em elementos)**

---

### **Flexbox - parte 1**

---

### **Flexbox - Parte 2**

---

### **Flexbox - Parte 3**

---

### **Flexbox - Parte 4**

---

### **CSS Grid - Parte 1**

---

### **CSS Grid - Parte 2**

---

### **Espaçamento entre linhas e colunas - GAP**

---

### **Grid template areas**

---

