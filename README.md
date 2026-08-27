# projeto-integrador-frontend-vinicius
O tema escolhido para esse projeto será um site de vendas especializados em RPG's de mesa.
se é esperado no projeto final a possível compra de coisas como dados, livros de regras, suplementos de regras, miniaturas e etc que se é esperado do hobby.
também se espera um espaço dedicado para a possível  integração de usuário interessados a outros clientes, para que eles formem seus próprio grupo de jogos.


CODE REVIEW - Luís Guilherme Soares Amorim 27/08/26

Ao analisar o código, percebo que ele apresenta uma boa estrutura inicial em HTML5, principalmente por utilizar elementos semânticos como `<header>`, `<main>`, `<section>` e `<footer>`. Também considero positivo o uso do `lang="pt-BR"`, da configuração de `viewport` e das tags de acessibilidade, como `<label>` nos campos do formulário e `alt` nas imagens. A tabela também está bem estruturada, utilizando `<caption>`, `<thead>`, `<tbody>` e `scope`, o que demonstra uma preocupação com a organização e acessibilidade do conteúdo.

Por outro lado, existem alguns pontos que precisam ser corrigidos. Um dos principais problemas é que as tags `<meta>` e `<title>` aparecem novamente dentro do `<main>`, sendo que elas devem ficar somente dentro do `<head>`. Também existe uma possível inconsistência no caminho utilizado para carregar os arquivos do vídeo, já que ele está diferente do padrão utilizado nas imagens. Outro ponto é que algumas partes do conteúdo ainda estão funcionando mais como uma descrição das ideias do projeto do que como funcionalidades reais do site.

O formulário também pode ser melhorado com nomes de `id` e `name` mais descritivos, como `nome` em vez de `fname`. Além disso, seria interessante organizar a tabela de livros dentro de uma `<section>` com um título próprio, deixando a estrutura da página mais semântica e fácil de entender. O uso de `width` e `height` diretamente nas imagens também poderia ser substituído por CSS, principalmente pensando na responsividade.

De forma geral, considero que o código está bem encaminhado. Ele demonstra conhecimento dos principais elementos do HTML5 e uma preocupação inicial com acessibilidade e semântica. Os principais pontos a melhorar são a organização do código, a correção de alguns elementos posicionados incorretamente e a implementação das funcionalidades propostas, como venda de livros, compra de miniaturas e localização de mesas de RPG. O próximo passo seria trabalhar a estilização com CSS e, posteriormente, utilizar JavaScript para tornar o site mais interativo.
