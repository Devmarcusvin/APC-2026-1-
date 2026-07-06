# Semana 04

## Objetivos da Semana

Nesta semana, o objetivo foi compreender o funcionamento da geração de números aleatórios e sua aplicação no desenvolvimento de programas interativos. As atividades tiveram como foco explorar a função `randomNumber()`, entendendo como ela pode ser utilizada para criar comportamentos dinâmicos e diferentes resultados a cada execução do programa.

## Code.org

Durante a **Lição 4 – Random Numbers**, foram realizados diversos exercícios utilizando números aleatórios para controlar propriedades dos objetos desenhados na tela. A principal proposta foi compreender como a aleatoriedade pode tornar aplicações mais interessantes, evitando resultados repetitivos.

Nos exercícios desenvolvidos, foi possível utilizar a função `randomNumber()` para alterar automaticamente a posição de figuras geométricas. Dessa forma, cada vez que o programa era executado, os objetos eram posicionados em locais diferentes dentro do intervalo definido pelo programador.

Como atividade prática, foi desenvolvido um desenho representando uma lagarta colorida. Cada segmento do corpo recebia uma pequena variação em sua posição vertical por meio da função `randomNumber(190, 210)`, fazendo com que o desenho apresentasse pequenas diferenças a cada nova execução. Esse exercício demonstrou, de forma simples, como a programação pode gerar comportamentos variados utilizando apenas uma função de números aleatórios.

## Exercício Desenvolvido

### Lagarta utilizando números aleatórios

Neste exercício foi utilizada a função `randomNumber()` para alterar automaticamente a posição vertical de cada segmento da lagarta, produzindo pequenas variações visuais a cada execução do programa.

#### Código

```javascript
background("skyBlue");

// vermelho
fill("red");
ellipse(100, randomNumber(190, 210), 50, 50);

// laranja
fill("orange");
ellipse(140, randomNumber(190, 210), 50, 50);

// amarelo
fill("yellow");
ellipse(180, randomNumber(190, 210), 50, 50);

// verde
fill("green");
ellipse(220, randomNumber(190, 210), 50, 50);

// azul
fill("blue");
ellipse(260, randomNumber(190, 210), 50, 50);

// roxo
fill("purple");
ellipse(300, randomNumber(190, 210), 50, 50);

// cabeça
fill("black");
ellipse(100, randomNumber(190, 210), 10, 10);
```

#### Conceitos aplicados

- Utilização da função `randomNumber()`;
- Geração de números aleatórios dentro de um intervalo;
- Construção de desenhos utilizando figuras geométricas;
- Aplicação da aleatoriedade para criar resultados diferentes a cada execução.

## Desafios Encontrados

Durante as atividades, alguns desafios precisaram ser superados:

- Compreender o funcionamento da função `randomNumber()`;
- Definir intervalos adequados para a geração dos valores;
- Organizar o código de forma clara e legível;
- Entender que o programa produz resultados diferentes a cada execução.

## Aprendizados

Ao final da semana, foram consolidados os seguintes conhecimentos:

- Funcionamento da geração de números aleatórios;
- Utilização de intervalos para controlar valores;
- Aplicação da aleatoriedade em projetos gráficos;
- Desenvolvimento do raciocínio lógico para criar programas mais dinâmicos.

## Conclusão

As atividades desenvolvidas nesta semana permitiram compreender como a utilização de números aleatórios pode tornar programas mais interessantes e interativos. A função `randomNumber()` mostrou-se um recurso importante para criar variações automáticas em objetos gráficos, sendo um conceito amplamente utilizado no desenvolvimento de jogos e aplicações.
