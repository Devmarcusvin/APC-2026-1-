# Semana 06

## Objetivos da Semana

Nesta semana, o objetivo foi aprofundar os conhecimentos sobre as propriedades dos sprites, compreendendo como modificar suas características visuais e posicioná-los corretamente dentro do cenário. As atividades tiveram como foco a personalização de objetos gráficos por meio da alteração de propriedades como escala, animação e posição.

## Code.org

Durante a **Lição 6 – Sprite Properties**, foram exploradas as principais propriedades disponíveis para os sprites no Game Lab. Após aprender a criar personagens na semana anterior, o foco passou a ser a manipulação de suas características para construir cenas mais organizadas e visualmente agradáveis.

Ao longo das atividades, foi possível compreender como utilizar diferentes animações da biblioteca do Code.org e ajustar o tamanho dos sprites utilizando a propriedade `scale`. Também foram realizados exercícios envolvendo posicionamento dos objetos na tela, permitindo que diferentes elementos ocupassem o mesmo cenário de forma equilibrada.

Esses conceitos demonstraram que os sprites possuem diversas propriedades que podem ser alteradas durante a execução do programa, tornando possível criar interfaces, cenários e jogos com maior riqueza visual.

## Exercício Desenvolvido

### Composição de um cenário utilizando propriedades dos sprites

Neste exercício foi criado um prato utilizando diferentes alimentos representados por sprites. Foram utilizadas animações da biblioteca do Game Lab para representar uma porção de batatas fritas, um hambúrguer e uma fatia de melancia. Cada sprite teve seu tamanho ajustado utilizando a propriedade `scale`, permitindo criar uma composição visual mais harmoniosa.

#### Código

```javascript
background("burlywood");
fill("white");
ellipse(200,200,350,350);

var fries = createSprite(200,200);
fries.setAnimation("fries");
fries.scale = 0.3;

var burger = createSprite(200,200);
burger.setAnimation("burger");
burger.scale = 0.4;

var dessert = createSprite(200,200);
dessert.setAnimation("watermelon");
dessert.scale = 0.3;

drawSprites();
```

#### Conceitos aplicados

- Criação de múltiplos sprites;
- Utilização de diferentes animações;
- Alteração da propriedade `scale`;
- Posicionamento de sprites utilizando coordenadas;
- Construção de cenários combinando elementos gráficos;
- Utilização da função `drawSprites()` para renderização dos objetos.

## Desafios Encontrados

Durante o desenvolvimento das atividades, alguns desafios precisaram ser superados:

- Compreender a finalidade das propriedades dos sprites;
- Ajustar corretamente a escala de cada objeto para manter uma boa proporção visual;
- Posicionar os sprites de forma organizada dentro do cenário;
- Entender a relação entre os elementos desenhados manualmente e os sprites adicionados posteriormente.

## Aprendizados

Ao final da semana, foram consolidados os seguintes conhecimentos:

- Manipulação das propriedades dos sprites;
- Utilização da propriedade `scale` para redimensionamento;
- Aplicação de animações disponíveis na biblioteca do Game Lab;
- Organização de elementos gráficos em um mesmo cenário;
- Desenvolvimento de cenas mais elaboradas utilizando sprites.

## Conclusão

As atividades desta semana permitiram compreender que os sprites não se limitam apenas à exibição de imagens, mas possuem diversas propriedades que podem ser modificadas para atender às necessidades do projeto. O estudo da propriedade `scale` e da organização dos elementos na tela proporcionou uma melhor compreensão sobre a construção de interfaces gráficas, preparando o caminho para as próximas etapas da disciplina, que abordarão movimentação e interação entre os objetos.
