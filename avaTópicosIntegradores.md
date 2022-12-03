### Por que devemos fazer testes automatizados nas aplicações que desenvolvemos? :wrench: :hammer:

Devemos fazer testes automatizados porque eles são importantes para conseguimos minimizar os erros que ao desenvolvermos uma aplicação, ou , ao implementarmos alguma função nova em um sistema surgem com a abordagem manual.  Com a automação o teste é repetido varias vezes, sendo assim, mais fácil de encontrar novos erros e usando também cenários específicos.

 Temos também as vantagens acerca dos testes automatizados, dentre elas :

- Escalabilidade
- Confiabilidade
- Ciclos de feedback mais rápidos
- Economia de recursos
- Desenvolvimento mais rápido
- Mais valor agregado à aplicação

Todas essas citadas trazem qualidade, redução de custos e melhor retorno em cima do investimento.

Se o software é entregue para o público-alvo com poucos erros, seu uso será muito mais amplo, pois os usuários não terão problemas para executar suas atividades diárias.

### O que são testes unitários? :mag_right:

Os testes unitários ou testes de unidade é o processo de testar os componentes de programa, como métodos ou classes de objeto, ou seja, todas as pequenas frações do seu programa.

Exemplo //Quando estamos testando as classes de objeto, devemos fornecer uma cobertura de todas as características desse objeto, ou seja:

- Testar e verificar o valor de todos os atributos associados ao objeto
- Definir e verificar o valor de todos os atributos associados ao objeto
- Colocar o objeto em todos os estados possíveis, o que significa simular todos os eventos que causam mudanças de estado

A generalização ou herança faz testes de classes de objeto mais complicados. Você não pode simplesmente testar uma operação na classe em que ela está definida e que funcionará corretamente nas subclasses que herdam a operação. A operação que é herdada pode fazer suposições sobre outras operações e atributos. Essas operações podem não ser válidas em algumas subclasses que herdam a operação. Portanto, é necessário testar a operação herdada em todos os contextos de uso.

### O que são testes automatizados? :mag_right:

Os testes automatizados tem como base a verificação de várias características de uma aplicação. Tudo isso sem a interferência de quem está criando o sistema. Como consequência disso o tempo que se leva para corrigir erros, bugs, brechas de segurança e etc... são diminuídos consideravelmente.

Um teste automatizado tem três partes: 

1. Uma parte de configuração, em que você inicia o sistema com o caso de teste, ou seja, as entradas e saídas esperadas.
2. Uma parte de chamada, quando você chama o objeto ou método a ser testado. 
3. Uma parte de afirmação, em que você compara o resultado da chamada com o resultado esperado. Se a afirmação avaliada for verdadeira, o teste foi bem-sucedido, se for falsa, ele falhou.

Temos também os três principais testes automatizados que são eles:

- Testes de unidade automatizada (Unit Tests) // esse tipo de teste funciona com a interação direta com o código fonte da aplicação, com ele é possível rastrear problemas de sintaxe, variáveis mal estruturadas e estruturas que possam comprometer o desempenho da aplicação.
- Testes de Web Service/ API Tests // esse tipo de teste valida se as APIs da sua aplicação estão funcionando corretamente, geralmente é feita com o apoio de uma interface de usuário. Com os testes de Web Service/ API Tests a pessoa que está escrevendo o software também consegue rastrear bugs de segurança. Como consequência, o aplicativo será finalizado com APIs que são funcionais e manterá um bom nível de disponibilidade.
- Testes de GUI // são basicamente os testes de usuários e sua integração com a interface do software, procura e busca situações que possivelmente podem acontecer durante o uso e manuseio do app, website ou seja lá o que for, toques acidentais, cliques involutários etc.



### Escolha uma pirâmide de testes e descreva com suas palavras cada secção da pirâmide. :bulb:



![Pirâmide de Testes: o que você precisa saber sobre esse conceito](https://blog.onedaytesting.com.br/wp-content/uploads/2021/08/unnamed.png)



A divisão mais comum que temos

- Base: Testes de Unidade
- Meio: Testes de Integração
- Topo: Testes Ponta a Ponta (E2E, UI ou Testes de Interface)

Os testes da base(testes de unidade) como já dito são os pequenos movimentos feitos na menor parte testável do código fonte, não muitos extensos e por isso é mais fácil encontrar o erro ou local da falha com precisão.

Os testes de integração(integration) tem como principal objetivo unir e verificar o funcionamento de unidades interagindo uma com a outra. Sucede o teste unitário, para garantir que não houve nenhuma quebra naquilo que foi feito unitáriamente. A exemplos, a comunicação com a API, banco de dados, interfaces e outros micro-serviços.

Os testes de ponta a ponta (E2E) esse teste simula o comportamento de um usuário no final da aplicação, é quando o software passa a ser usado literalmente, onde há navegações, preenchimento de informações, cliques em botões e busca garantir o funcionamento com base em uma navegação comum que o usuário faria ao ultiliza-lo.