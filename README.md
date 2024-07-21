# Projeto CSS

### Objetivo do Projeto
O objetivo principal do projeto foi construir uma Landing Page utilizando HTML e CSS, para poder exercitar todos os conhecimentos adiquiridos durante as aulas.

## Efeitos Adicionados

#### Transições e Animações 

Eu tomei a liberdade adicionar alguns efeitos de transição em algumas propriedades CSS, com o intuito de
adicionar um efeito de animação sutil, para que o projeto tenha um resultado um pouco diferente do esperado.

#### [Animação 1] Button.

##### Explicação:

- **Transição de Propriedades**: Define uma transição suave para as propriedades `background-color` e `transform`
com duração de 0.3 segundos e um efeito `ease` (suavização).

#### [Animação 2] Modules.

##### Explicação:

- **Estado Inicial**: Cada elemento `.module` é inicialmente deslocado 20 pixels para baixo (`translateY(20px)`) e a
transição de opacidade e transformação é definida para 0.5 segundos com suavização `ease`.

#### [Animação 3] Parágrafo.

##### Explicação:

- **Elemento Animado**: Parágrafos (`p`) dentro do elemento com o ID `#transform-world`.
  - No início da animação (`0%`), o elemento está deslocado 100% para a direita (`translateX(100%)`).
  - No final da animação (`100%`), o elemento retorna para a posição original (`translateX(0)`).