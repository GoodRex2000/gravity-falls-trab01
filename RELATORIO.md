# Relatório de aprendizagem - TRAB01

**Aluno:** Lázaro Fornari  
**Turma:** 1G  
**Disciplina:** Desenvolvimento Web I

## 1. O que eu fiz

Para este trabalho escolhi criar um site sobre a série Gravity Falls. A ideia foi desenvolver uma página simples, com informações sobre a história, os personagens, a cidade e alguns elementos importantes da série.

Primeiro organizei o conteúdo que queria colocar no site. Depois criei o arquivo `index.html` e dividi a página em partes usando elementos semânticos como `header`, `main`, `section`, `article` e `footer`. Também usei links internos no menu para levar o usuário diretamente para cada seção da página.

Em seguida criei o arquivo `style.css` para definir cores, fontes, espaçamentos e a disposição dos elementos. Para organizar o layout, usei recursos como Flexbox e CSS Grid em diferentes partes da página. Também adicionei uma media query para adaptar a organização do conteúdo em telas menores.

As imagens foram colocadas em uma pasta chamada `imagens`, deixando os arquivos do projeto separados e facilitando o uso de caminhos relativos no HTML. As ilustrações utilizadas são arquivos SVG simples feitos para a página.

Por fim, coloquei o projeto em um repositório público no GitHub e utilizei o GitHub Pages para deixar o site disponível na internet.

## 2. Ferramentas usadas

Usei HTML para estruturar o conteúdo e CSS para definir a parte visual e o layout da página. O GitHub foi usado para armazenar e versionar os arquivos do projeto, e o GitHub Pages para hospedar a página estática.

Para pesquisar informações básicas sobre a série, consultei a página oficial da Disney sobre Gravity Falls.

## 3. O que eu aprendi

Como já tivemos contato com HTML e CSS durante o ano, o trabalho serviu mais para aplicar esses conhecimentos em um projeto completo e entender melhor como as partes se relacionam.

Uma das coisas que aprofundei foi o uso de HTML semântico. Em vez de organizar tudo apenas com `div`, utilizei elementos como `header`, `nav`, `main`, `section`, `article` e `footer`, deixando a estrutura do documento mais clara e organizada.

Também pratiquei melhor a construção de layouts com CSS. Usei Flexbox para organizar elementos em linha e CSS Grid para montar áreas com colunas e cards. Percebi que esses dois recursos podem ser usados em situações diferentes e ajudam a evitar posicionamentos manuais desnecessários.

Outro ponto foi trabalhar com responsividade. A página possui uma media query que altera os layouts com várias colunas para uma única coluna em telas menores. Também usei propriedades como `max-width`, unidades relativas e `clamp()` para controlar melhor o tamanho dos elementos sem depender apenas de valores fixos.

Na organização do projeto, entendi melhor a importância dos caminhos relativos. Como as imagens ficam dentro da pasta `imagens`, o HTML precisa apontar corretamente para esse diretório. Se a estrutura de pastas mudar sem atualizar os caminhos, os arquivos deixam de carregar.

Também entendi melhor a relação entre Git, GitHub e GitHub Pages dentro de um projeto web. Os commits registram alterações no código, o repositório mantém essas versões organizadas e o GitHub Pages usa os arquivos do projeto para disponibilizar a página como um site estático. Isso mostrou na prática que a organização do repositório também influencia o funcionamento do site publicado.

## 4. Fonte consultada

Disney - Gravity Falls: https://shows.disney.com/gravity-falls
