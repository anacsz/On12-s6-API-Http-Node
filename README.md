# On11-TodasEmTech-s6-Introducao-Node
Turma Online 11 - Todas em Tech | Back-end | 2021 | Introdução à API:
HTTP e NodeJS

## Para o lar
Abra o PullRequest Respondendo as seguintes questões:

1) Qual a relação entre os métodos HTTP e o CRUD?

Resposta = A relação seria entre HTTP e o CRUD via o protocolo "HTTP", é que você pode via API criar, ler, realizar update e deletar um registro.

Comente, com exemplos, a diferença entre o PUT e o PATCH.

PATCH - Alterações parciais a um recuro.
Exemplo: (/usuario/1234) :

Resultado: {'name': 'João'}


PUT - Possibilita Alterações completas de um documento. 
Exemplo: (/usuario/1234) :

Resultado: {'id': 1234, 'name': 'Joao', 'idade': 25, 'documento': '123.321.12-X'}
    
2) Assim como na aula, apresente os dados dos JSONs no console

No colors-rgb.js apresente o nome da cor e o codigo RGB como no exemplo: "gainsboro - rgb(220, 220, 220, 1)"

No estados-cidade.js apresente o nome do Estado, a sigla e todas as cidadades, sem arrays aparentes no console

No filmes.js apresente titulo, plot, generos e lingua. Genero e lingua devem ser apresentados em arrays no console.

3)Defina o conceito de idempotência e como uma API pode ser idempotente

Resposta = Idempotência é um metodo que indenpendete da quantidade de vezes que é executado, retorna sempre o mesmo valor. A API pode ser idempotente quando utilizamos os métodos GET e PUT.

4)Cite alguns diferentes padrões de projetos de software.

Resposta = 

***Padrões estruturais - ligados diretamente a composição de uma classe, ou seja como é formada sua estrutura.

***Padrões de Criação - estão associados diretamente com os mecanismos que controlam a criação de objetos.

***Padrões Comportamentais - tem como obetivo lidar com a forma com que o objeto se comunica com os outros.