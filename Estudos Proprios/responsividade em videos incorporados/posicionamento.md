# O que é posicionamento "*position*"

Position é uma propriedade em CSS que determina como será feito o posicionamento de um elemento. Algumas das possibilidades que estudei estão descritas abaixo. Um elemento é considerado posicionado se a propriedade position é qualquer outra além da padrão: static.

## Estático "*static*"

Static é o padrão. Um elemento posicionado estaticamente obedece o flow normal do documento. Ou seja, é renderizado de acordo com os padrões. Atributos como top, left, bottom, right e z-index não têm efeito.

## Relative "*relative*"

Nesse caso o elementos tem sua posição inicial padrão de acorco com o flow normal do documento, mas tem um deslocamento "*offset*" a partir da posição inicial de acorco com top,, bottom, left e right. Z-index funciona. O elemento tem um espaço criado no documento, ou seja, mesmo com um offset diferente de 0, o espaço que o objeto ocuparia se mantém ali, vazio.

## Absoluto "*absolute*"

Esse por fim não cria um espaço para o objeto, e ele é posicionado em relação ao (0,0) do elemento parente (obrigatoriamente posicionado) mais próximo.