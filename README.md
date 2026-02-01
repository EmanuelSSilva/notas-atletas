🏆 Sistema de Avaliação de Atletas – Ginástica Artística
📖 Sobre o Projeto

Este projeto foi desenvolvido em JavaScript com o objetivo de simular o sistema de avaliação de uma competição de ginástica artística.

A aplicação recebe uma lista de atletas contendo seus nomes e cinco notas atribuídas por jurados. Seguindo as regras oficiais da competição, a maior e a menor nota são desconsideradas, e a média final é calculada com base nas três notas restantes.

O projeto demonstra domínio de:

Manipulação de arrays

Ordenação numérica

Estruturas de repetição

Cálculo de média

Organização e clareza de código

Lógica aplicada a regras de negócio

📐 Regra de Negócio

Cada atleta recebe 5 notas (de 1 a 10).

Para calcular a média válida:

As notas são ordenadas em ordem crescente.

A menor nota é removida.

A maior nota é removida.

A média é calculada com base nas 3 notas intermediárias.

Essa abordagem é comumente utilizada em competições para evitar distorções causadas por notas extremas.

🧠 Conceitos Aplicados

O projeto utiliza conceitos fundamentais da linguagem JavaScript:

for para iteração

.sort() para ordenação numérica

.slice() para extração de elementos

.forEach() para soma dos valores

.length para cálculo da média

Template literals para formatação da saída

📥 Estrutura de Entrada
let atletas = [
 {
   nome: "Cesar Abascal",
   notas: [10, 9.34, 8.42, 10, 7.88]
 }
];


Cada objeto representa um atleta contendo:

nome → String

notas → Array de números

📤 Exemplo de Saída
Atleta: Cesar Abascal
Notas Obtidas: 7.88,8.42,9.34,10,10
Média Válida: 9.253333333333334

🚀 Como Executar
✔ Via Navegador

Abra o DevTools (F12)

Cole o código no console

Execute e visualize o resultado

✔ Via Node.js
node nome-do-arquivo.js

🎯 Objetivo Educacional

Este projeto foi desenvolvido com foco em:

Prática de lógica de programação

Consolidação de manipulação de arrays

Aplicação de regras de negócio reais

Escrita de código limpo e organizado

📌 Possíveis Melhorias Futuras

Implementação de interface gráfica (HTML/CSS)

Entrada dinâmica de atletas

Validação de notas

Formatação da média com número fixo de casas decimais

Transformação em API REST com Node.js ou Spring Boot

👨‍💻 Autor

Emanuel Silva
Estudante de desenvolvimento backend com foco em JavaScript e Java.
Interesse em lógica de programação, APIs e arquitetura de sistemas.# notas-atletas