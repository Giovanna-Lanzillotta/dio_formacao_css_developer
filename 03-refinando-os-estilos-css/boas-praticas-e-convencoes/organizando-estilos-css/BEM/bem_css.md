[B] Bloco
[E] Elemento
[M] Modificador

* ``Bem faz alusão a Programação Orientada a Objetos (POO), uma maneira de descrever a realidade no código, com uma maneira de desrever a realidade no código, com uma variedade de padões e uma maneira de pensar nas entidades do programa.`` *
> - Varga Stepanova, desenvolvedora front-end do projeto.

- Bloco (Block):
    - Entidade independente (bloco de construção)
    - Elemento pai
    - [BLOCO] (.btn)

- Elmento (Elements)
    - Elemento filho
    - Não independente
    - Vinculado a um bloco
    - [BLOCO]__[ELEMENTO] (.btn__price)

- Modificador (Modifier)
    - Modifica um bloco ou um elemento
    - Variante para alterar a aparência
        - Variar uma propriedade
        - Atribuir um estado
    - [BLOCO]__[ELEMENTO]--[MODIFICADOR]
    .menu--dark
    .btn--orange
    .menu__link--disabled