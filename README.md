# Clean Code

História
- criado em 2008 por Uncle Bob(Robert C Martin);
- ele foi um dos 17 signatários originais do manifesto ágil
- o SOLID foi criado pelo Michael Feathers, mas esses conceitos tiveram forte influência do artigo "Os principios da orientaçao a objetos" do Uncle Bob.

Motivações
- passamos 10 vezes mais lendo código do que escrevendo, isso significa que a facilidade na leitura e entendimento terá impacto direto no produtividade do time;
- mais tempo em manutençāo do que em código novo;
- nāo utilizar boas práticas leva a dividas, e essas dividas tendem a aumentar ao longo do tempo, a ponto de ser mais viavel criar uma api nova(um codigo novo)(obs.: dividas sao inevitaveis, mas os juros podem ser altos no futuro).

Caracteristicas de um codigo limpo
- Deve ser elegante e semantivo: boa aparencia e de facil entendimento;
- Codigo limpo é focado;
- Codigo limpo é cuidado: Alguem se deu o trabalho de criar/manter simples, organizado, se atentando aos detalhes, ou seja, se importaram.

Principios/Pontos Importantes
- nomes claros nas classes, metodos, variaveis ou arquivos), tenha foco e nao tenha medo de nomes grandes;
- o metodo deve ser o mais minimalista possivel;
- padronizaçao de nomes (exemplo: se fetchCards(), getInvoices() e findBenefits() obtem algo, entāo o ideal seria usar o mesmo prefixo);
- regra do escoteiro: antes de desmontar o acampamento, eles precisam deixar mais limpo do que estava quando chegaram;
- DRY(Don't Repeat Yourself): nao repita codigo/implementaçao;
- Nunca insira comentarios; codigo com nomes claros e respeitando o minimalismo nao precisam ser comentados;
- testes limpos: rapidos, independentes, possibilidade de repetir varias vezes, assertions claros(clareza no esperado e retornado), TDD;
- refatoraçao faz parte do dia a dia, nao existe melhoria definitiva, aceita que dói menos;
- como identificar um codigo ruim: afastar e aproximar da margem(if, else, for, when,...) / muitas linhas de codigo;
- criar codigo para as outras pessoas entenderem, e nao somente quem criou;
- cultura de Code Review.

Nomes de Classes
- devem estar no substantivo como por exemplo Cliente, WikiPage, Conta e AddressParser. 
Metodos
- devem ser verbos ou frase verbal como por exemplo postPayment, deletePage e save. Acessores, moditicadores e predicados devem ser nomeados de acordo com seus valores e prefixados com get e set.
Paramentros do Metodo
- deve ter no maximo 3, caso necessario criar um objeto.
Exceptions
- cuidado para nao misturar tratamento de erros com regras de negocio no mesmo lugar.
Constantes
- sempre que possivel utilize constantes, evite numeros magicos(nomes e valores que nao sabemos ou temos duvidas do seu significado)

Pontos Importantes
- os beneficios sao a longo prazo;
- praticar ira tornar essa atividade mais facil e rapida, mas sempre irá demorar mais do que nao fazer o uso;
- possiveis problemas caso o time como um todo nao tenha essa preocupacao:
 > quem faz uso dessas "boas praticas" demora mais pra entregar uma feature;
 > "um limpa, mas o outro suja".
- o livro possui 3 partes:
 > principios, padroes e praticas para criar um codigo limpo;
 > casos de estudo de complexidade cada vez maior;
 > lista de heuristicas e "odores" reunidos durante a criacao dos estudos de casos.

Minhas consideraçoes
- apesar de todos os beneficios acredito que como tudo na vida existem tradeoff, ou seja, nao devemos impor o que achamos meljor, e sim mostrar as possibilidades e entender junto ao time o que melhor se encaixa naquele momento.

Slides: https://prezi.com/view/qePgSJxFx3A4IwcmH5T6/
