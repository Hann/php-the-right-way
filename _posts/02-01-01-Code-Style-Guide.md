---
title: 코딩 스타일 가이드
---

# 코딩 스타일 가이드  {#code_style_guide_title}

PHP 커뮤니티는 매우 거대하고, 수많은 라이브러리와 프레임워크, 컴포넌트들이 존재합니다. 
이렇게 많은 선택지들 중에 몇 가지를 골라 프로젝트에 적용하는 일은 PHP 개발자에게 일상적인 일입니다.
다양한 라이브러리를 조합하여 사용하는 일을 수월하게 하려면 가능한한 공통적인 코드 스타일을 적용하는 일이
중요합니다.

[Framework Interop Group][fig]에서는 [PSR-0][psr0], [PSR-1][psr1], [PSR-2][psr2]이라는 권장 스타일 가이드를 발표했습니다.
이들 가이드는 Drupal, Zend, Symfony, CakePHP, phpBB, AWS SDK, FuelPHP, Lithium 등의 프로젝트에서 적용하기 시작한
스타일 규칙들의 모음입니다.

가능하다면 여러분은 알려진 표준 스타일에 맞춰 코드를 작성해야 합니다. 몇 가지 PSR을 조합하거나, 
PEAR나 Zend에서 만든 스타일 표준을 사용할 수도 있습니다. 그렇게 함으로써 다른 개발자들도 여러분의 코드를
쉽게 읽고 사용할 수 있으며, 많은 써드파티 라이브러리를 사용하면서도 어플리케이션 코드의 일관성을
유지할 수 있습니다.

* [Read about PSR-0][psr0]
* [Read about PSR-1][psr1]
* [Read about PSR-2][psr2]
* [Read about PEAR Coding Standards][pear-cs]
* [Read about Zend Coding Standards][zend-cs]

[PHP_CodeSniffer][phpcs]라는 도구를 사용하면 코드가 이들 가이드를 따르는지 체크할 수 있습니다.
[Sublime Text 2][st-cs] 같은 텍스트 편집기에는 실시간으로 코드를 체크해주는 플러그인도 제공됩니다.

Fabien Potencier의 [PHP Coding Standards Fixer][phpcsfixer]라는 도구는 
표준 스타일에 맞게 코드를 자동으로 수정해줘서 여러분이 직접 일일이 코드를 수정하는 수고를 덜어줍니다.

코드에 사용되는 모든 기호는 영어로 작성하는 것이 좋습니다. 주석은 코드를 사용할 사람들이 편하게 
읽고 쓸 수 있다면 어떤 언어로 기록해도 됩니다.

[fig]: http://www.php-fig.org/
[psr0]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-0.md
[psr1]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md
[psr2]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md
[psr3]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-3-logger-interface.md
[pear-cs]: http://pear.php.net/manual/en/standards.php
[zend-cs]: http://framework.zend.com/wiki/display/ZFDEV2/Coding+Standards
[phpcs]: http://pear.php.net/package/PHP_CodeSniffer/
[st-cs]: https://github.com/benmatselby/sublime-phpcs
[phpcsfixer]: http://cs.sensiolabs.org/
