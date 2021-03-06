---
title: Guia de estilo de código
---
# Guia de estilo de código {#guia_de_estilo_de_código_title}

A comunidade PHP é grande e diversa, composta por inúmeras bibliotecas, frameworks e componentes. É comum para
desenvolvedores PHP escolher vários destes e combiná-los em um único projeto. É importante que código PHP siga (o
mais próximo possível) um estilo de código comum para que desenvolvedores PHP possam misturar várias bibliotecas em
seus projetos.

O [Framework Interop Group][fig] propôs e aprovou uma série de recomendações de estilo, conhecidas como [PSR-0][psr0],
[PSR-1][psr1], [PSR-2][psr2] e [PSR-4][psr4]. Não deixe os nomes estranhos confundí-lo, estas recomendações são meramente um conjunto
de regras que projetos como Drupal, Zend, Symfony, CakePHP, phpBB, AWS SDK, FuelPHP, Lithium etc. estão começando a
adotar. Você pode utilizá-las para seus próprios projetos, ou continuar utilizando seu estilo pessoal.

Idealmente você deveria escrever código PHP que adere a um ou mais destes padrões. Pode ser qualquer combinação das
PSR's, ou um dos padrões de código feitos pela PEAR ou Zend. Isso significa que outros desenvolvedores podem facilmente
ler e trabalhar no seu código, e aplicações que implementem os componentes possam ter consistência, mesmo trabalhando
com bastante código de terceiros.

* [Leia sobre a PSR-0][psr0]
* [Leia sobre a PSR-1][psr1]
* [Leia sobre a PSR-2][psr2]
* [Leia sobre a PSR-4][psr4]
* [Leia sobre os Padrões de Código da PEAR][pear-cs]
* [Leia sobre os Padrões de Código da Zend][zend-cs]

Você pode usar o [PHP_CodeSniffer][phpcs] para checar seu código contra qualquer uma dessas recomendações, e plugins
para editores de texto como o [Sublime Text 2][st-cs] para fazer a verificação em tempo real.

Use o [PHP Coding Standards Fixer][phpcsfixer] do Fabien Potencier para automaticamente modificar seu código para que
ele seja compatível com os padrões, evitando fazer as alterações na mão.

O Inglês é a linguagem preferida para todos os nomes simbólicos e para a infra-estrutura do código. Comentários devem
ser escritos em qualquer linguagem que possa ser facilmente lida por todos os atuais e futuros desenvolvedores que
possam trabalhar nessa base de código.

[fig]: http://www.php-fig.org/
[psr0]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-0.md
[psr1]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md
[psr2]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md
[psr4]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-4-autoloader.md
[pear-cs]: http://pear.php.net/manual/en/standards.php
[zend-cs]: http://framework.zend.com/wiki/display/ZFDEV2/Coding+Standards
[phpcs]: http://pear.php.net/package/PHP_CodeSniffer/
[st-cs]: https://github.com/benmatselby/sublime-phpcs
[phpcsfixer]: http://cs.sensiolabs.org/
