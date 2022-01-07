# O que é um id?

O id é uma ferramenta que podemos usar em alguns elementos html para dar uma **identificação** única por página àquele elemento. É como um RG, apenas um elemento pode ter aquele id específico por página html. Usar o mesmo id em mais de um elemento na mesma página pode até funcionar, mas não está correto.

# O que é uma classe ?

A classe é mais abstrata que o id. Ela pode ser usada para estilizar múltiplos elementos que tenham a mesma classe. Além disso um mesmo elemento pode ter simultaneamente múltiplas classes, além de ter múltiplas classes e um id.

# Quando usar id ao invés de classe ?

Pode parecer intuitivo se perguntar o porquê de usar id sendo que a classe parece muito mais eficiente. O id é usado para estilizar um único elemento, enquanto classes podem também estilizar tanto um, quanto vários.

Seria perda de tempo usar id em certo elemento, e depois de um tempo, escalonando o código, precisarmos voltar e trocar por uma classe, então parece mais simples usar classes apenas. Isso está certo, mas apenas quanto à estilização.

Em termos de estilo não faz diferença prática uma opção sobre a outra, usar diretamente classes ajuda com a escalabilidade do código. Mas id têm funções além de estilo, funções que classes não têm.

id podem ser usados para navegação interna na página usando âncoras, já que cada id é único por página. Além disso id serão usados mais à frente com JavaScript para criar interação com usuário.