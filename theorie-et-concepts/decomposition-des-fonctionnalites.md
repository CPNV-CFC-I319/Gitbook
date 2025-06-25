# Décomposition des fonctionnalités

Source : [Standford university](https://cs.stanford.edu/people/nick/py/python-function.html)

Un programme est régulièrement constitué de plusieurs lignes de code regroupés dans un ou plusieurs fichiers.

Il est nécessaire de subdiviser la logique de son code en fonctions ayant une tâche, une responsabilité unique. Un peu comme si vous ameniez vos idées, paragraphes après paragraphe, pour structurer vos propos.

Un principe important à appliquer dès vos débuts en développement est résumé par l'acronyme SRP pour "Single Responsability Principle".

Source: [dev.to - srp](https://dev.to/ggorantala/solid-single-responsibility-principle-with-examples-h0f)

## Avantages du SRP

### <mark style="color:orange;">Amélioration de la lisibilité du code</mark>

<mark style="color:orange;">La lecture et la compréhension</mark> du code sont facilitées lorsque chaque classe ou module a une responsabilité unique. Cela permet aux développeurs de <mark style="color:orange;">comprendre rapidement l'objectif</mark> de la classe ou du module et sa <mark style="color:orange;">relation avec d'autres parties du système</mark>.&#x20;

### <mark style="color:orange;">Amélioration de la maintenabilité du code</mark>

En <mark style="color:orange;">décomposant une fonctionnalité complexe en modules plus petits et plus ciblé</mark>s, le SRP permet aux développeurs d'apporter plus facilement des modifications au code sans affecter d'autres parties du système. Cela signifie que <mark style="color:orange;">la maintenance et le dépannage du code prennent moins de temps et sont moins coûteux</mark>.&#x20;

### <mark style="color:orange;">Facilite la réutilisation du code</mark>

Le code qui adhère à l'SRP est souvent plus modulaire et <mark style="color:orange;">réutilisable</mark>. Cela signifie que les développeurs peuvent facilement réutiliser le code dans d'autres parties du système ou <mark style="color:orange;">dans d'autres projets</mark>.&#x20;

### <mark style="color:orange;">Améliore l'évolutivité (</mark>_<mark style="color:orange;">scalabilité)</mark>_ <mark style="color:orange;"></mark><mark style="color:orange;">du système</mark>

Le maintien d'une responsabilité unique pour chaque classe ou module devient <mark style="color:orange;">de plus en plus important au fur et à mesure que la base de code s'étoffe</mark>.&#x20;

L'SRP garantit que <mark style="color:orange;">la base de code reste évolutive</mark> et peut facilement s'adapter à des changements ou à de nouvelles fonctionnalités <mark style="color:orange;">sans avoir d'impact sur le reste du système</mark>.

## Conclusion

Dans l'ensemble, le respect du principe de responsabilité unique améliore la qualité et la maintenabilité de la base de code, ce qui facilite la gestion, les tests et le déploiement.

### En savoir plus

Le SRP est un des principes intégré à un concept plus large du nom de SOLID, dans lequel le S signifie le SRP dont nous avons discuté.

{% embed url="https://dev.to/ggorantala/series/23913" %}

