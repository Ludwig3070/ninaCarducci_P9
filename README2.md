liens utiles pour cette formation

[purge css] https://www.youtube.com/watch?v=qarJQ00MNAc&t=366s

[Avoid large layout shifts](https://web.dev/articles/optimize-cls?utm_source=lighthouse&utm_medium=devtools&hl=fr)

[loading lazy](https://developer.mozilla.org/fr/docs/Web/Performance/Lazy_loading)

[utilisation pour convertir les images au format webp](https://www.freeconvert.com/fr/jpg-to-webp/download)

[compresseur web p](https://imagecompressor.11zon.com/fr/compress-webp/)

[rel="noopener"](https://developer.mozilla.org/fr/docs/Web/HTML/Attributes/rel/noopener)

[csp](https://developer.chrome.com/docs/lighthouse/best-practices/csp-xss?utm_source=lighthouse&utm_medium=devtools&hl=fr)

<script src="./mon-script.js"></script>
La balise <meta> que vous avez fournie est une directive de stratégie de sécurité de contenu (Content Security Policy, CSP) qui spécifie les sources autorisées pour les scripts sur votre page web. Dans ce cas, la directive script-src 'none' indique que les scripts JavaScript ne peuvent être chargés à partir d'aucune source externe.

Cela signifie que votre page n'autorisera pas l'exécution de scripts JavaScript provenant de sources externes telles que des CDN ou des serveurs tiers. Tous les scripts doivent être inclus directement dans le code de la page ou via des attributs src qui pointent vers des ressources internes du site.

Assurez-vous de placer la balise <meta> avec la directive CSP dans la section <head> avant tout contenu pouvant déclencher l'exécution de scripts, comme les balises <script> ou les attributs onclick. Cela garantira que la politique de sécurité du contenu est appliquée avant que le navigateur ne commence à interpréter le reste de la page.



[Réduisez les ressources CSS inutilisées Économies potentielles](https://developer.chrome.com/docs/lighthouse/performance/unused-css-rules?utm_source=lighthouse&utm_medium=devtools&hl=fr)


[Properly size images Potential savings of 138 KiB ](https://developer.chrome.com/docs/lighthouse/performance/uses-responsive-images?utm_source=lighthouse&utm_medium=devtools&hl=fr)

[Activez la compression de texte Économies potentielles de 355 Kio](https://developer.chrome.com/docs/lighthouse/performance/uses-text-compression?utm_source=lighthouse&utm_medium=devtools&hl=fr)

[voir reponse de chat gpt ci dessous](https://developer.mozilla.org/fr/docs/Web/HTML/Attributes/autocomplete)

Le message d'erreur indique que le navigateur reconnaît l'identifiant (ID) ou le nom (name) d'un champ de formulaire, mais il s'attend également à trouver un attribut autocomplete associé à ce champ de formulaire. Bien que ce message soit une mise en garde et non une erreur critique, il est recommandé d'ajouter l'attribut autocomplete pour améliorer la compatibilité avec la fonctionnalité d'autocomplétion du navigateur.

Dans votre cas, vous pouvez simplement ajouter l'attribut autocomplete à votre champ de formulaire, par exemple :

<input type="email" name="email" id="email" autocomplete="email">

L'attribut autocomplete peut prendre différentes valeurs, telles que "email", "name", "address", "postal-code", etc., en fonction du type de données attendues dans le champ. Dans cet exemple, j'ai utilisé "email" comme valeur pour correspondre au type de champ (champ d'adresse e-mail). Cela permettra au navigateur de mieux comprendre quel type de données est attendu dans ce champ et d'autocompléter en conséquence.

En ajoutant cet attribut à votre champ de formulaire, vous devriez résoudre le message d'erreur dans la console de Firefox.

[minifier JS](https://www.toptal.com/developers/javascript-minifier)

[inserer le balisage des donnees structureesou enrichies](https://www.youtube.com/watch?v=g9h6bGH0xoE&t=242s)

[outil d'aide au balisage de google](https://www.google.com/webmasters/markup-helper/u/0/)

[documentation sur les donnees structurees](https://developers.google.com/search/docs/appearance/structured-data/intro-structured-data?hl=fr)

[outil pour les donnees structurees](https://support.google.com/webmasters/answer/7445569?hl=fr)

[blog interessant](https://fr.semrush.com/blog/comment-obtenir-des-rich-snippets/)

[schema.org validate super interessant](https://schema.org/)

