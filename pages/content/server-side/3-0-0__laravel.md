---
layout: course
permalink: server-side/laravel/
published: true
#
abbreviations:
  - computer
hyperlinks:
  - csse
  - technology
title: Laravel
---
{%- include includes.md %}

> Boeken
> ---
> Verplichte boeken (te downloaden vanaf het hogeschoolnetwerk):
>
> - [Beginning Laravel (Sinha, 2017)](http://link.springer.com/book/10.1007/978-1-4842-2538-7)
> - [Design Patterns in PHP and Laravel (Dockins, 2017)](http://link.springer.com/book/10.1007/978-1-4842-2451-9)
> - [PHP 7 Quick Scripting Reference (Olsson, 2016)](http://link.springer.com/book/10.1007/978-1-4842-1922-5)
> - [PHP 7 Zend Certification Study Guide (Beak, 2017)](https://link.springer.com/book/10.1007/978-1-4842-3246-0)
> - [PHP Arrays (Prettyman, 2017)](https://link.springer.com/book/10.1007/978-1-4842-2556-1)
{:.card.card-book}

> Zie ook
> ---
> - [PHP]({% link references/reference-php/1-0-0__inleiding.md %})
> - Learn X in Y minutes:
>   - [Composer](https://learnxinyminutes.com/docs/php-composer/)
>   - [Git](https://learnxinyminutes.com/docs/git/)
>   - [YAML](https://learnxinyminutes.com/docs/yaml/)
> - Blogs:
>   - [Taylor Otwell](https://medium.com/@taylorotwell) (Maker en oprichter van Laravel)
>   - [Mohamed Said](http://themsaid.com) (Webdeveloper bij Laravel)
>   - [Laravel News Blog](https://laravel-news.com/blog)
>   - [Laravel Community Portal](https://laravel.io)
> - Tutorials:
>   - [Diving Laravel](https://divinglaravel.com)
>   - [Performant Laravel](https://serversforhackers.com/laravel-perf)
{:.card.card-book}

Wat is Laravel?
---------------

> [Laravel][]  
> The PHP Framework For Web Artisans
{:.block}

Laravel is een PHP-framework voor RAD dat ontwikkeld werd door [Taylor Otwell][], een voormalig .NET-ontwikkelaar.

Laravel probeert het wiel niet opnieuw uit te vinden, maar inspireert zich op de andere frameworks. En niet enkel PHP-frameworks, maar ook onder andere [Microsoft .NET][] en [Ruby on Rails][]. Het maakt daarenboven gebruik van [Symfony][]-componenten.

Het microframework [Lumen][] is het kleinere broertje van Laravel. Doordat Lumen gebaseerd is op Laravel-componenten kan een Lumen-project relatief makkelijk naar een Laravel-project geüpgraded worden.

> Symfony
> ---
> [Symfony][] is het populairste *enterprise-level* PHP-framework. Naast een framework is het ook een verzameling van losse componenten die in ander projecten gebruikt kunnen worden. [Projects using Symfony](https://symfony.com/projects) is een lijst van projecten die Symfony-componenten gebruiken.
{:.card}

Waarom een framework?
---------------------

Webprojecten zijn ondertussen zo complex geworden dat je als individuele ontwikkelaar geen tijd meer hebt om het wiel opnieuw uit te vinden. 

Een framework biedt oplossingen voor heel wat courante problemen waarmee je als webontwikkelaar geconfronteerd wordt. Door een framework te gebruiken kan je je als ontwikkelaar focussen op de **opdracht** in plaats van de technologie.

Andere voordelen:

 - Goed **getest** doordat automatische tests gebruikt worden en doordat het al in veel projecten gebruikt werd.
 - Goed **gedocumenteerd**.
 - Dwingt een zekere mate van **structuur en uniformiteit** af. Dit faciliteert het samenwerken met andere ontwikkelaars.
 - Eenvoudige updates en onderhoud van de applicatie.

Waarom Laravel?
---------------

### Volwassen

Het is een *volwassen* framework, want het is al in ontwikkeling sinds 2011. Ondertussen zitten we al aan de 5de generatie. Sinds versie 4 is Laravel gebaseerd op Symfony-componenten en volgt de Laravel Roadmap de [Symfony Roadmap](http://symfony.com/doc/current/contributing/community/releases.html#schedule), waardoor de Laravel Releases kort na de Symfony Releases volgen.

> - [Laracasts][]: de officiële Laravel tutorialsite van [Jeffrey Way](https://twitter.com/jeffrey_way).
> - [Laracon AU][], [Laracon EU][], [Laracon US][] en [Laracon Online][]: de officiële congressen.


### Up-and-coming

 - Nieuwste generatie RAD-frameworks.
 - Al enkel jaren de meeste [stars](https://github.com/search?l=PHP&o=desc&q=php&s=stars&type=Repositories&utf8=✓) en [forks](https://github.com/search?l=PHP&o=desc&q=php&s=forks&type=Repositories&utf8=✓) van alle PHP-projecten op GitHub (maart 2017).
 
### State-of-the-Art

 - PHP 7.1.3+ (sinds Laravel 5.6), 
 - Lid van [PHP Framework Interop Group][PHP-FIG]
 - Past de geldende best practices toe:
   - *Architectural Pattern:* MVC
   - *Design Patterns:*
     - [Decorator](http://designpatternsphp.readthedocs.io/en/latest/Structural/Decorator/README.html)
     - [Dependency Injection](http://designpatternsphp.readthedocs.io/en/latest/Structural/DependencyInjection/README.html)
     - Dispatcher
     - [Facade](http://designpatternsphp.readthedocs.io/en/latest/Structural/Facade/README.html)
     - [Iterator](http://designpatternsphp.readthedocs.io/en/latest/Behavioral/Iterator/README.html)
     - [Observer](http://designpatternsphp.readthedocs.io/en/latest/Behavioral/Observer/README.html)
     - [Repository](http://designpatternsphp.readthedocs.io/en/latest/More/Repository/README.html)
     - [Singleton](http://designpatternsphp.readthedocs.io/en/latest/Creational/Singleton/README.html)
     -  …

> PHP Framework Interop Group
> ---
> [PHP-FIG][] is een organisatie waar bijna elk PHP-project van betekenis lid van is. Deze organisatie draagt bij tot de professionalisering van de PHP-community door de samewerking tussen de leden in de hand te werken. Ze doet dit door [PSR][]'s af te spreken.
{:.card}
