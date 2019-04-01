# Index des clés et lexiques des termes de Premier Langage

## G

### grader (clé obligatoire)

Dans Premier Langage, on désigne par le terme de grader le programme Python qui doit corriger
les réponses de l'apprenant. Le grader assure en fait deux missions :
* Il établit une note entre 0 et 100 en analysant les réponses de l'apprenant.
* Il prépare des feedbacks adaptés suivant les réponses de l'apprenant.
La clé `grader` est donc obligatoire dans tout exercice PL. Soit le grader est définit sur
place localement dans l'exercice mais comme l'écriture d'un grader demande un peu d'expérience
avec PL, le plus simple est souvent d'utiliser un template pour hériter de son grader.

## T

### title (clé obligatoire)

La valeur associé à la clé `title` donne un titre à l'exerice PL. Si vous définissez cette balise
dans une activité, alors vous lui spécifierez un titre. Un bon titre est juste une chaîne de caratères.
Un bon titre décrit simplement le contenu de l'exercice. Les bons titres facilite les recherches et la
réutilisabilité des ressources.


### text (clé obligatoire)

La clé `text` est très souvent définie sur plusieurs ligne. La balise à vocation à contenir 
le corps de l'énoncé de l'exercice dans un exercice PL. C'est donc l'ensemble des consignes
que vous souhaitez transmettre à votre apprenant avant qu'il remplisse le formulaire de 
l'exercice et qu'il soumette sa réponse. 