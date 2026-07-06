Relatório de Aprendizagem – Semanas 07 a 10
Introdução

Entre as semanas 07 e 10 foram estudados conteúdos fundamentais para o desenvolvimento de jogos no Game Lab do Code.org. Nesse período, os exercícios passaram a envolver maior interação entre os elementos da tela, utilizando animações, movimentação automática de sprites e estruturas condicionais para alterar comportamentos durante a execução do programa.

O principal objetivo dessas semanas foi compreender como controlar objetos de forma dinâmica, permitindo que personagens mudem de posição, executem ações automáticas e reajam a determinadas condições definidas no código.

Conteúdos Estudados
Semana 07 – Text

Nesta semana foi aprendido como exibir informações textuais na tela utilizando comandos específicos do Game Lab. Os exercícios permitiram compreender a importância do texto para transmitir mensagens ao usuário, apresentar instruções, pontuações e informações sobre o estado do jogo.

Também foram realizados testes de posicionamento e organização visual dos textos dentro do cenário.

Semana 08 – The Draw Loop

O foco desta semana foi o funcionamento do draw loop, responsável pela atualização contínua da tela. Foi compreendido que os comandos presentes dentro da função draw() são executados repetidamente, possibilitando a criação de animações e movimentos em tempo real.

Esse conceito serviu como base para todas as atividades posteriores envolvendo movimentação e interação.

Semana 09 – Sprite Movement

Nesta etapa foram desenvolvidos exercícios de movimentação de sprites utilizando alterações nas coordenadas dos objetos. Os personagens passaram a se deslocar automaticamente pela tela, permitindo compreender como pequenas mudanças nos valores de posição produzem animações contínuas.

Semana 10 – Conditionals

Na semana 10 foi introduzido o uso de estruturas condicionais, principalmente o comando if. Aprendeu-se a verificar condições durante a execução do programa e modificar o comportamento dos sprites quando determinadas situações forem atendidas.

Aplicação Prática

Durante as atividades foi desenvolvido um exercício no qual um dinossauro se movimenta automaticamente para cima. Quando sua posição ultrapassa um determinado limite da tela, sua animação é alterada de um tiranossauro para um pterodáctilo.

Código Desenvolvido

```javascript var backdrop = createSprite(200, 200); backdrop.setAnimation("sci_fi");

var dinosaur = createSprite(200, 350); dinosaur.scale = 0.2; dinosaur.setAnimation("tyrannosaurus");

function draw() { // move o dinossauro para cima dinosaur.y = dinosaur.y - 5;

// se chegar ao céu, muda para pterodáctilo if (dinosaur.y
