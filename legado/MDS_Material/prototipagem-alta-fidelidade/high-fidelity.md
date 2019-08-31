# Prototipagem de Alta Fidelidade

Introdução

Um protótipo é comumente definido como uma versão preliminar de algum projeto, seja carro, software ou maquete, sendo que o mesmo deve portar características correspondentes com a proposta do projeto.

A prototipagem em si possui no **mínimo** duas etapas que culminam no desenvolvimento dos protótipos de baixa e alta fidelidade.

Na primeira etapa é feita a concepção das características do produto e elaborado um esboço de como o produto deve se apresentar ou se comportar, surge aí o **protótipo de baixa fidelidade**.

Na segunda etapa é feito o aprofundamento do protótipo de baixa fidelidade, sendo que este novo protótipo, de **alta fidelidade** , deve ser o mais parecido possível com o produto final. Porém não é necessário que o mesmo seja feito utilizando das mesmas tecnologias do produto final.

Aqui falaremos da prototipagem no campo de engenharia de software.

 Por que prototipar?

Vários são os motivos que justificam o porquê de utilizar protótipos. Alguns deles são:

Ajuda na percepção e listagem de requisitos, tanto por parte do cliente quanto dos desenvolvedores.

Muitas vezes quando conversando com o cliente, podem não ser captados ou podem ser esquecidos alguns requisitos que serão lembrados durante a fase de prototipagem, seja pelos desenvolvedores, seja pelo cliente.

Cria uma base sólida para o desenvolvimento.

A partir do protótipo, a implementação da solução se torna mais simples por conta dos desenvolvedores possuírem um modelo a seguir na hora de desenvolver.

Permite ao usuário final interagir com o processo de desenvolvimento.

O _feedback_ do cliente permite que mudanças sejam feitas no começo da implementação ao invés de mudar alguns detalhes no final do projeto, causando menor dano ao cronograma do projeto.

Ajuda a criar soluções inovadoras.

Durante a prototipagem, podem surgir idéias inovadoras para a solução do problema do projeto.

Reaproveitamento de código

Dependendo da forma de prototipagem, e da ferramenta utilizada, é possível que o protótipo gere código ou possa ser aproveitado no produto final. Ex.: o Photoshop pode exportar código CSS; Um protótipo em html estático pode ter sua estrutura re-aproveitada, em sua maioria, na view de uma aplicação web.

Algumas ferramentas de prototipagem de alta fidelidade

- Justinmind
- Origami Studio
- Moqups
- Axure
- Proto.IO
- UxPin

Selecionando uma ferramenta de prototipagem de software

Hoje no mercado existem várias ferramentas de prototipagem de software, e a principal diferença entre elas é a facilidade do uso e adaptação ao meio corporativo, como por exemplo, a ferramenta Axure possui uma maneira simples de compartilhamento de layouts que permite que várias pessoas possam contribuir em um mesmo protótipo.

Outras como a UXPin, além de disponibilizar uma ampla gama de tutoriais e livros em seu site, é considerada uma das maiores e melhores ferramentas de prototipagem no mercado.

Existem outras opções para a prototipagem de alta fidelidade, já que a mesma não necessariamente precisa possuir código ou ter seu código fonte reaproveitado no sistema final. Prototipagens de alta fidelidade podem, por exemplo, ser implementadas em páginas html estáticas, imagens criadas em editores de imagens, como o Adobe Photoshop, ou em ferramentas online.







# Tutorial

Vamos projetar um website similar ao github utilizando da técnica de prototipagem de alta fidelidade por página estática, onde vamos fazer o uso do framework Bootstrap. Primeiramente é necessário um protótipo de baixa de fidelidade para ter noção de como o sistema deve parecer:

![](https://github.com/andre-filho/00-Disciplina/blob/master/MDS_Material/prototipagem-alta-fidelidade/img/IMG_20170606_121423.jpg)

1- Primeiramente o deve-se importar as dependências do Bootstrap, que são as stylesheet e o javascript.

![](https://github.com/andre-filho/00-Disciplina/blob/master/MDS_Material/prototipagem-alta-fidelidade/img/passo1.png)

2- Seguindo o protótipo de baixa de fidelidade, vamos incluir os campos de login e senha, como é somente um protótipo o botão de logar no sistema deve ser somente um link para a página seguinte.

![](https://github.com/andre-filho/00-Disciplina/blob/master/MDS_Material/prototipagem-alta-fidelidade/img/foto%20login%20code1.png)

3- Vamos então customizar o estilo da página no master.css

![](https://github.com/andre-filho/00-Disciplina/blob/master/MDS_Material/prototipagem-alta-fidelidade/img/login%20css.png)

4- Esse é o resultado:

![](https://github.com/andre-filho/00-Disciplina/blob/master/MDS_Material/prototipagem-alta-fidelidade/img/login%20final.png)

5- Vamos dividir a página de profile em navbar e o conteúdo, primeiramente vamos implementar a navbar:

![](https://github.com/andre-filho/00-Disciplina/blob/master/MDS_Material/prototipagem-alta-fidelidade/img/profile%20navbar%20code.png)

6- Em seguida vamos implementar o conteúdo da página:

![](https://github.com/andre-filho/00-Disciplina/blob/master/MDS_Material/prototipagem-alta-fidelidade/img/profile%201.png)

7- E por fim vamos customizar o master.css para tornar a paǵina mais agradável:

![](https://github.com/andre-filho/00-Disciplina/blob/master/MDS_Material/prototipagem-alta-fidelidade/img/profile%20css.png)

8- Esse é o resultado final do profile:

![](https://github.com/andre-filho/00-Disciplina/blob/master/MDS_Material/prototipagem-alta-fidelidade/img/profiling.png)

# Finalizando

O conjunto de páginas estáticas criadas nesse treinamento formam um protótipo de um webapp por possuir representações de como se daria a navegação e experiência do software final.
Com um protótipo desses, o cliente pode perceber mais facilmente funcionalidades que passaram despercebidas ou foram esquecidas durante o levantamento de requisitos, ou outros requisitos não funcionais de usabilidade.
Com isso chegamos ao fim do treinamento.
Obrigado.
