# Q1 : Décrire ce que renvoie la méthode qui liste les questions ?
Réponse:

[{"id":1,"translations":[{"language":"fr","value":"Quel est le pays le plus grand consommateur de café par habitant ?"},{"language":"en","value":"Which country is the largest per capita coffee consumer?"},{"language":"it","value":"Quale paese è il più grande consumatore di caffè pro capite?"}],"catgory":{"translations":[{"language":"fr","value":"Culture Générale"},{"language":"en","value":"General Culture"},{"language":"it","value":"Cultura generale"}]}},{"id":2,"translations":[{"language":"fr","value":"Quel animal est le plus dangereux pour l’Homme ?"},{"language":"en","value":"Which animal is the most dangerous for man?"},{"language":"it","value":"Quale animale è il più pericoloso per l'uomo?"}],"catgory":{"translations":[{"language":"fr","value":"Culture Générale"},{"language":"en","value":"General Culture"},{"language":"it","value":"Cultura generale"}]}}]

elle renvoie un json composé de questions avec un id, translations qui est composé de language et value pour la langue et la valeur, catgory composé de language et value aussi pour préciser la catégorie de la question en plusieurs langue 

# Q2 : Décrire ce que renvoie la méthode qui liste les propositions d'une question ?
Réponse:
[{"id":1,"translations":[{"language":"fr","value":"Brésil"},{"language":"en","value":"Brazil"},{"language":"it","value":"Brasile"}],"question":{"id":1,"translations":[{"language":"fr","value":"Quel est le pays le plus grand consommateur de café par habitant ?"},{"language":"en","value":"Which country is the largest per capita coffee consumer?"},{"language":"it","value":"Quale paese è il più grande consumatore di caffè pro capite?"}],"catgory":{"translations":[{"language":"fr","value":"Culture Générale"},{"language":"en","value":"General Culture"},{"language":"it","value":"Cultura generale"}]}}}]

cette fois presque pareil on a un champ id, translations qui représente cette fois la réponse, et questions qui représente la question à la réponse en plusieurs langues



# Q3 : Décrire ce que renvoie la méthode qui évalue des réponses ?
Réponse: 0

renvoie le score de la réponse envoyer en tant que json 

# Q4 : Quelle est la valeur de la RSS utilisée par l'api quarkus en mode JVM ?
Réponse: 209792 KO

# Q5: Quel est le temps et la taille de la réponse  de la méthode qui liste les questions
Temps:19.497221s
Taille:883 bytes

# Q6: Quel est le temps et la taille de la réponse  de la méthode qui liste les propositions d'une question
Temps:12.791497s
Taille:609 bytes

# Q7: Quel est le temps et la taille de la réponse  de la méthode qui évalue les réponses
Temps:0.058426s
Taille:1 bytes

# Q8 : Empreinte mémoire en mode natif ?
Réponse:2280

# Q9: Temps et  taille  réponse   liste les questions
Temps:21.970081s
Taille:883 bytes

# Q10: Temps et  taille  réponse  liste des propositions
Temps:13.492778s
Taille:609 bytes

# Q11: Temps et  taille  réponse  évaluation les réponses
Temps:0.002186s
Taille:1 bytes

# Q12:  Proposition 1
Description: réduire la complexité quand c'est possible
Temps:12.505275s
Taille:609 bytes

# Q13:  Proposition 2
Description: enlever les imports et déclaration inutiles
Temps:12.653831s
Taille:609 bytes

# Q14:  Proposition 3
Description: la mise en cache 
Temps: 18.594660s
Taille: 609 bytes

# Q15:  Proposition 4
Description: supprimer la partie traduction qui ne fait pas partie des besoins du client 
Temps:0.595913s
Taille:191 bytes