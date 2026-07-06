# Semana 05

## Objetivos da Semana

Nesta semana, o objetivo foi compreender o conceito de **Sprites** e sua importância no desenvolvimento de jogos digitais. As atividades foram voltadas para a criação, configuração e exibição de personagens dentro do Game Lab, permitindo substituir figuras geométricas por elementos gráficos mais elaborados.

## Code.org

Durante a **Lição 5 – Sprites**, foram apresentados os principais recursos para criação de sprites no Game Lab. Aprendemos que um sprite representa um objeto ou personagem capaz de possuir propriedades próprias, animações e comportamentos independentes.

Ao longo das atividades, foram desenvolvidos exercícios para criar sprites, posicioná-los na tela e associar animações disponíveis na biblioteca do Code.org. Também foi introduzida a função `drawSprites()`, responsável por renderizar todos os sprites criados durante a execução do programa.

Essa etapa marcou uma evolução importante em relação às semanas anteriores, pois deixou de ser necessário desenhar manualmente cada elemento utilizando figuras geométricas. A partir desse momento, os personagens passaram a ser representados por sprites com imagens e animações próprias.

## Exercício Desenvolvido

### Criação de Sprites

Neste exercício foi desenvolvido um cenário simples utilizando dois sprites: um gato e um cachorro. Cada personagem recebeu sua própria animação e foi posicionado em locais diferentes da tela, enquanto a função `drawSprites()` ficou responsável por exibi-los durante a execução do programa.

#### Código

```javascript
// Create sprite 1
var catSprite = createSprite(100, 200);
catSprite.setAnimation("cat");

// Create sprite 2
var dogSprite = createSprite(300, 200);
dogSprite.setAnimation("dog");

function draw() {
  background("lightblue");

  // Draw all sprites
  drawSprites();
}
```

#### Conceitos aplicados

- Criação de sprites utilizando `createSprite()`;
- Associação de animações através de `setAnimation()`;
- Posicionamento de objetos utilizando coordenadas `(x, y)`;
- Utilização da função `draw()` para atualizar continuamente a aplicação;
- Exibição de todos os sprites por meio da função `drawSprites()`.

## Desafios Encontrados

Durante as atividades, alguns desafios precisaram ser superados:

- Compreender a diferença entre desenhar figuras geométricas e utilizar sprites;
- Posicionar corretamente os personagens na tela;
- Entender a função de cada comando relacionado à criação dos sprites;
- Organizar o código para facilitar futuras modificações.

## Aprendizados

Ao final da semana, foram consolidados os seguintes conhecimentos:

- Criação e manipulação de sprites;
- Utilização da biblioteca de animações do Game Lab;
- Organização de personagens dentro do cenário;
- Funcionamento da função `drawSprites()`;
- Importância dos sprites para o desenvolvimento de jogos digitais.

## Conclusão

As atividades desenvolvidas nesta semana permitiram compreender como os sprites simplificam o desenvolvimento de jogos e aplicações gráficas. A possibilidade de utilizar personagens prontos e controlar suas propriedades torna o processo de desenvolvimento mais organizado e eficiente. Esse conteúdo servirá como base para as próximas lições, nas quais os sprites passarão a receber movimentos, interações e comportamentos mais complexos.
