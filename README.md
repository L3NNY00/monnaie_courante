# MonnaieCourante - Application web de gestion de budget

## Contexte

## Gestion d'erreurs
Les erreurs contenues dans le code sont gérées grâce à des try-catch, qui renvoient le cas échéant des erreurs sous la forme suivante :  
`CodeErreurPDO`-`LigneCodeResponsable`  
Exemple :  
`HY000-20` où `HY000` est une 'General error' et `20` est la dernière ligne de code exécutée avant le retour d'erreur.
