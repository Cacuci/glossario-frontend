# Glossário Frontend

O objetivo deste documento é descrever brevemente os termos comumente utilizados quando falamos sobre front end. A grande oferta de ferramentas (e também de serviços, métodos, padrões e minucias em geral) confunde quem não vive o dia-a-dia do desenvolvimento web.

Sinta-se à vontade para fazer fork, complementar/melhorar a lista e solicitar fazer um pull request.

### Frontend
Tudo o que for relacionado a ambiente browser. Nesta categoria podemos incluir HTML, CSS, Javascript, Flash, imagens, SVG, frameworks e bibliotecas.
* * *

### Routes
São os pontos de acesso aos recursos (funcionalidades) da sua aplicação e costumam ser confundidas com as URL. Na verdade URL é apenas uma parte da rota, que tem por responsabilidade fazer a ligação entre a URL  com um *controller* que será responsável por processar a requisição.

No frontend, as rotas (normalmente) estão associadas à *Single Page Applications*
* * *

### Single Page Applications
Popularizadas pelo lançamento do Gmail em 2004, as *Single Page Application* tem como características não utilizar a navegação tradicional que atualiza completamente a página  para mostrar uma nova funcionalidade. Pedaços de HTML são mesclados com informações vindas do servidor e mostrados imediatamente, sem que seja necessário o *refresh* da página.

A criação de *Single Page Applications* foi bastante simplificada com o surgimento dos frameworks MVC para Frontend, notadamente [AngularJS](http://angularjs.org), [Backbone](http://backbonejs.org) e [Ember.js](http://emberjs.com).

* * *

### Resources

* * *

### Promises

* * *

### Framework
Um framework normalmente é um conjunto de bibliotecas para conseguir executar uma operação maior. É comum um framework encapsular os comportamentos da API em implementações mais complexas, permitindo o seu uso de forma mais flexível, frequentemente através de extensões, configurações e inversões de controle. Como pode ser considerada uma camada em cima da API eventualmente pode simplificá-la em certo sentido. Ele costuma dar consistência a um conjunto de bibliotecas (pena que acontece o oposto em alguns casos).

### Library/ Biblioteca
A biblioteca normalmente é uma implementação real das regras de uma API. Portanto ela é mais concreta. Assim como a API, você não precisa saber os detalhes da implementação para usá-la. A biblioteca precisa respeitar as regras da API sempre, mas não precisa ter sua implementação estável. A biblioteca costuma ser autossuficiente.

### Pre-processadores (Less/Sass)

* * *

### Verbos HTTP
São ações associadas às chamadas HTTP feitas a um servidor. Quando se informa uma URL na barra de endereço do browser e se pressiona o ENTER, uma chamada HTTP é feita para o servidor associado ao domínio informado. Esta chamada é o do tipo GET e visa solicitar recursos. Já quando se preenche um formulário e se pressiona o botão para submeter as informações, (normalmente) uma chamada do tipo POST é feita e sua finalidade é enviar informações ao servidor.

GET, POST, PUT, DELETE e outros...

Os 4 verbos citados acima são os mais comuns, por estarem diretamente associados com as ações de CRUD (create, read, update e delete), ações básicas para gerenciamento da informações pelo software. A lista completa dos verbos pode ser encontrada [neste link](http://pt.wikipedia.org/wiki/Hypertext_Transfer_Protocol#M.C3.A9todos).

Numa web application tradicional, que não faz uso do AJAX, normalente apenas GET e POST são utilizados. Já quando se está desenvolvendo com o uso do AJAX (provavelmente utilizando um framework), se costuma utilizar os 4 verbos para identificar o propósito da chamada: GET (obter dados), POST (salvar novo), PUT (atualizar existente) e DELETE (remover existente).

* * *

### API/Webservice/REST

* * *

### AJAX

* * *

### UI/UX
 * UX
User experience” (experiência do usuário), é a experiência que o usuário tem ao usar seu produto, seja ele um APP, um site, sistema desktop ou lata de milho.

* UI
User interface (interface do usuário), parte responsável em auxiliar o usuário a concluir suas ações, é a parte visivel do seu sistema, APP ou que seja. Ou seja, cores, elementos e sua distribuição, informações ect. A interface do usuário é a ponte para a UX.
* * *

### DOM
**Document Object Model** é uma API Javascript provida pelo browser para acesso aos elementos HTML. É através dela que podemos escrever `document.getElementById('id_do_elemento')` e assim ler seus valores e propriedades.

![Document Object Model](https://infinit.io/link/Fabio_Vedovelli/8xXK4bW.png) 

* * *

### Coffee Script

* * *

### Type Script

*TypeScript é um superconjunto de JavaScript desenvolvido pela Microsoft que adiciona tipagem e alguns outros recursos a linguagem. Anders Hejlsberg, arquiteto da linguagem C# e criador das linguagens Delphi e Turbo Pascal, trabalhou no desenvolvimento do TypeScript.[1][2][3][4] A linguagem pode ser usada para desenvolver aplicações JavaScript no lado cliente e lado servidor (Node.js).

Foi considerada pelo público a 4ª linguagem "mais amada", de acordo com uma pesquisa conduzida pelo site Stack Overflow em 2018, e está entre as 15 linguagens mais populares, de acordo com uma pesquisa conduzida pela RedMonk

### ES6

* * *

### Grunt e Gulp
São **automatizadores de tarefas**: ferramentas de linhas de comando que executam - de forma automatizada - tarefas que normalmente são executadas manualmente. Alguns exemplos:

+ Verificar código Javascript procurando por erros;
+ Concatenar e minificar código Javascript, CSS e HTML;
+ Comprimir imagens;
+ Processar arquivos SASS e LESS, transformando-os em CSS;
+ Copiar arquivos, colando-os em outra pasta;
+ ... entre muitas outras.

Uma característica importante é que eles possuem a habilidade de "observar" os arquivos do projeto, aguardando modificações, para então executar (em ordem) as instruções a eles passadas em seu arquivo de configuração.

* * *

### Node.js e NPM

* * *

### Concatenar e Minificar

* * *

