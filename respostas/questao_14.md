## Questão 14

O uso de índices pode trazer grandes melhorias para o desempenho do banco de dados. Os registros são armazenados em páginas de dados, páginas estas que compõem o que chamamos de pilha, que por sua vez é uma coleção de páginas de dados que contém os registros de uma tabela. Cada página de dados tem seu tamanho definido em até 8 Kb, apresenta um cabeçalho, também conhecido como header, que contém arquivos de links com outras páginas e identificadores (hash) que ocupam a nona parte do seu tamanho total (8 Kb) e o resto de sua área é destinada aos dados.

Os índices aceleram a recuperação dos dados. Por exemplo, imagine que você compre um livro de 800 páginas para suas pesquisas acadêmicas e este não apresente em seu conteúdo um índice reportando o seu conteúdo. Uma pesquisa talvez não fosse tão pavorosa, mas se você precisar de várias pesquisas, seria muito desagradável ficar horas procurando o conteúdo que deseja estudar. Por outro lado, um livro que apresente um índice de suas abordagens, se faz muito mais fácil e torna as pesquisas até prazerosas, pois teremos condição de irmos direto ao ponto que queremos.

Por padrão, os SGBDs criam índices automaticamente para campos de Chave Primária, Chave Estrangeira e Constraint UNIQUE. Além disso, podemos criar índices para outras colunas usadas com frequência em buscas ou junções.

## Referências

[Link externo 1](https://www.devmedia.com.br/entendendo-e-usando-indices/6567)

[Link externo 2](http://www.bosontreinamentos.com.br/bancos-de-dados/o-que-sao-indices-em-bancos-de-dados-indexacao-em-tabelas/)
