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

#### - **Introdução à seção**

Nesta curso usaremos o VS CODE, Live Server e o Google Chrome.

VS CODE como editor de texto.

No VS CODE usamos a extensão Live Server para criar um servidor onde podemos renderizar a visualização do arquivo HTML.

O Google Chrome vai ser utilizado como renderizador do arquivo HTML pelo Live Server utilizando o servidor.

---

#### - **Estrutura do HTML**

Tags de abertura e fechamento indicam o início e o fim de um elemento, definindo onde o conteúdo começa e termina.

Tags chamadas de auto-fechadas, não precisam de fechamento porque são auto-suficientes e não contêm conteúdo interno.

Tags podem ter atributos, que são informações extras inseridas na tag de abertura para personalizar o comportamento ou a aparência do conteúdo.

informações sobre as tags estarão no arquivo crido para a aula 01.

para melhor verificar se o seu arquivo HTML esta seguindo as normas evitando erro entrar no validador W3C no link: https://validator.w3.org/

---

#### - **Estrutura do HTML e Meta ViewPort**

informações sobre as tags estarão no arquivo crido para aula 02.

Nesta aula aprendemos sobre identação, utilização manual e automativa via editor de texto.

Aprendemos também para que serve a viewport, tag h1, p e br.

---

#### - **Atributos de id e class**

O atributo **id** identifica um elemento de forma única na página. Ele deve ser exclusivo, permitindo aplicar estilos específicos com CSS ou manipular o elemento com JavaScript. É útil para personalizar e controlar um elemento específico dentro do documento.

O atributo **class** é usado para agrupar elementos que compartilham o mesmo estilo ou comportamento. Vários elementos podem ter a mesma classe, permitindo aplicar o mesmo estilo ou manipulação a todos eles de uma vez com CSS ou JavaScript.

A especificidade no CSS3 define qual regra de estilo será aplicada a um elemento. A ordem de prioridade é: seletores de ID (mais específicos), seguidos por seletores de classe e pseudo-classes, e, por fim, seletores de tipo (tags). Quanto maior a especificidade, maior a prioridade da regra. Se duas regras tiverem a mesma especificidade, a última no código será aplicada.

---

#### - **Headings: do H1 ao H6**

Títulos são definidos pelas tags ```<h1>``` a ```<h6>```. O ```<h1>``` é o título mais importante e geralmente usado para o título principal da página, enquanto o ```<h6>``` é o título de menor importância. Essas tags ajudam a organizar o conteúdo de forma hierárquica, permitindo que o navegador e os motores de busca entendam a estrutura e a relevância do conteúdo na página.

---

#### - **Tags HTML para texto (links, imagens, etc)**

Algumas tegs têm o comportamento padrão de display: block. Isso significa que elas ocupam toda a largura disponível e começam em uma nova linha, empurrando o próximo conteúdo para baixo.

São usadas principalmente para estruturar seções maiores e separar o conteúdo visualmente, ajudando a organizar a página em blocos distintos de informação.

As tags semânticas têm um significado claro sobre o conteúdo que elas representam, enquanto as tags não semânticas não indicam diretamente o tipo de conteúdo.

Mais informações da aula 5 esta no documento HTML.

---

#### - **Conheça todas as tags HTML**

Link com todas as tags HTML https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element

Neste video vimos o que seria a teg navegação de forma semantica e como funciona as tags de lista ordenana e não ordenada.

Mais informações da aula 6 esta no documento HTML.

---

#### - **Semântica na estrutura do HTML5**

Neste video vimos como estruturar o HTML de forma sematica utilizando tags de separação.

Eu utilizei o modelo do professor e inteligencia artificial para melhor o template com base em uma loja de roupas.

Também apredemos como utilizar o validador de HTML para verificar se o mesmo esta semantico.

Mais informações da aula 7 esta no documento HTML.

---

#### - **Pensando em HTML e CSS**

Durante a aula foi mostrado sobre a utilização das tags e como o espaçamento delas funcionan.

Depois foi realizado o processo de tentativa de clonagem da pagina inicial da netflix utilizando os conceitos abordados na aula.

Mais informações da aula 8 esta nos documentos HTML.

---

#### - **Introdução ao CSS Box-Model**

Durante essa aula aprendemos como funciona o css para Box-model de forma pratica.

Documentação: https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_box_model/Introduction_to_the_CSS_box_model

---

#### - **Listas e Menus com HTML e CSS**

Nesta aaula aprendemos  diferença de HTML e CSS.

Aprendemos o que são listas ordenadas.

documentação link: https://www.w3schools.com/

No HTML, listas ordenadas (`<ol>`) são numeradas e usadas quando a sequência é importante. Listas não ordenadas (`<ul>`) têm marcadores e são ideais para itens sem ordem. Ambos usam `<li>` para itens, podendo ter estilos personalizados para marcadores e números.

foi realizado um piqueno projeto de menu com o que aprendemos em aula.

Para mais informações verificar os documentos html da aula 10.

---

#### - **Tabelas HTML**

Vimos no vídeo exemplos de tabelas HTML com títulos, descrições e rodapés. Utilizamos colspan para mesclar colunas e rowspan para mesclar linhas. As tabelas também são estilizadas com CSS para responsividade e bordas.

Para mais informações verificar os documentos html da aula 11.

---

#### - **Formulários e Inputs HTML - Parte 1**

[Documentação formularios](https://www.w3schools.com/html/html_forms.asphttps:/)

[HTML Input Types](https://www.w3schools.com/html/html_form_input_types.asphttps:/)

[Como estruturar um formulário HTML](https://developer.mozilla.org/pt-BR/docs/Learn/Forms/How_to_structure_a_web_formhttps:/)

---

#### - **Formulários e Inputs HTML - Parte 2**

Aprendemos a criar um formulário HTML com diferentes tipos de campos, incluindo texto, checkbox, radio buttons e data, além de botões para envio e reset. Exploramos atributos como `placeholder` e `required` para melhorar a experiência do usuário, e usamos o CSS para estilizar o formulário, como ao aplicar `cursor: pointer` aos `labels` para tornar a interação mais intuitiva. A organização do formulário em seções com `<section>` e separadores `<hr>` ajuda na clareza visual, facilitando o preenchimento.

---

#### - **Formulários e Inputs HTML - Parte 3**

Na aula, foi aprendido como utilizar diferentes tipos de inputs no HTML para criar formulários mais específicos e interativos. Com o uso de `<input>`, exploramos tipos como `date` para selecionar datas de aniversário, `datetime-local` para datas e horários completos, `time` para apenas o horário, `color` para escolher uma cor preferida, `email` para validação de e-mails, `file` para upload de arquivos com extensões específicas e `number` para selecionar números dentro de um intervalo.

---

#### - **Formulários e Inputs HTML - Parte 4**

Exploramos diversos elementos de entrada que tornam o preenchimento mais prático e funcional para o usuário. Usamos o tipo `password` para mascarar senhas, `range` com `datalist` para selecionar volumes com marcas visuais, `url` para validar links e `search` para criar um campo de busca. usamos também o `<select>` com `optgroup` para organizar opções em grupos, permitindo selecionar múltiplas opções. O campo `textarea` foi utilizado para textos longos.

---

#### - **Separando HTML e CSS em arquivos diferentes**

Para linkar um arquivo CSS ao HTML, coloca-se a tag `<link>` dentro do `<head>`, usando o atributo `href` para apontar o caminho do arquivo CSS e `rel="stylesheet"` para indicar que é uma folha de estilo.

---

#### - **Quem dá estilo ao HTML é o CSS**

CSS (Cascading Style Sheets) é uma linguagem de estilo usada para definir a aparência e o layout de páginas HTML. Com CSS, é possível controlar cores, fontes, espaçamentos, tamanhos e posicionamentos de elementos, separando o conteúdo da apresentação visual. Ele permite criar páginas mais organizadas, responsivas e atrativas, e funciona em conjunto com o HTML, aplicando estilos que podem ser definidos em arquivos externos, internos ou em linha, com prioridade determinada pela ordem e especificidade das regras.

Exemplo de pagina: https://codepen.io/luizomf/pen/KKNwMeG

---

#### - **Seletores básicos do CSS - Parte 1**

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

#### - **Seletores básicos do CSS - Parte 2**

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

#### - **Seletores de atributos do CSS**

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

#### - **Pseudo-classes**
#### - **Pseudo-classe :not()**
#### - **Pseudo-classe :nth-child()**
#### - **Pseudo-elements**
#### - **Especificidade CSS**
#### - **Herança e as propriedades que são passadas para elementos filhos**
#### - **Propriedade específicas do Box-Model (largura, altura, padding, border e margin)**
#### - **Float e Display (Block, Inline-Block e Inline)**
#### - **Cores HTML**
#### - **Unidades de medidas no CSS (px, rem, em, vw, vh, %)**
#### - **Propriedades para textos**
#### - **Posicionamento - Position**
#### - **Media queries e breakpoints**
#### - **Uma breve junção de tudo aprendido até aqui**
#### - **Border-radius (elementos redondos ou curvados)**
#### - **Box-shadow (sombra em elementos)**
#### - **Flexbox - parte 1**
#### - **Flexbox - Parte 2**
#### - **Flexbox - Parte 3**
#### - **Flexbox - Parte 4**
#### - **CSS Grid - Parte 1**
#### - **CSS Grid - Parte 2**
#### - **Espaçamento entre linhas e colunas - GAP**
#### - **Grid template areas**
