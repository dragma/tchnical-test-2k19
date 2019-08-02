# Le jeu du bouche à oreille

## Sujet

Votre mission, si vous l'acceptez, sera de se marrer un bon coup en manipulant les API [text to speech](https://www.ibm.com/watson/services/text-to-speech/) et [speech to text](https://www.ibm.com/watson/services/speech-to-text/) d'IBM.
Vous allez devoir éprouver ces services en recréant le jeu du bouche à oreille. 
Il y a des chances qu'on observe de belles choses ! :D

### Déroulement d'une partie

- Au début de la partie un nombre de tour est décidé par l'utilisateur.
- L'utilisateur écrit ensuite une phrase / paragraphe de la taille de son choix.
- Un tour est composé de la succession d'un [text to speech](https://www.ibm.com/watson/services/text-to-speech/) puis d'un [speech to text](https://www.ibm.com/watson/services/speech-to-text/)
- À chaque tour, le texte généré ainsi qu'une note comparative (sur 20) doit être sauvegardé sur un serveur distant, sur l'échelle de votre choix, avec l'algorithme de votre choix.
- En fin de partie, un récapitulatif des tours devra être affiché, ainsi que la note globale.

## Consignes

### Variantes sur la règle du jeu

Vous devrez tout faire pour que ces services se comprennent le moins possible (par exemple en changeant les langues entre les tours) si jamais les résultats sont trop parfaits (parce que sinon ça sera pas marrant ! **=]** )

### Technos

Les technologies à utiliser sont (évidemment)  a minima

- `react-native` (& `expo` eventuellement)
- `nodejs`

Libre à vous ensuite d'utiliser la manière que vous voulez pour stocker les état et résultats.
Je recommande cela dit un mongo, car rapide à implémenter et à déployer avec docker.

L'aspect graphique n'est pas très important. Cela dit, si vous avez des envies créatrices, ne vous privez pas :D !

La performance et l'optimisation est un plus pas (du tout) obligatoire. Le but est que je puisse voir comment vous codez / commitez sur un thème, qui, je l'espère, sera aussi décalé que sympathique.

L'exercice sera à me remettre sur un repo github ou gitlab au choix !

### API

Le pricing de cette API autorise une utilisation gratuite [jusqu'à 500 minutes par mois](https://www.ibm.com/cloud/watson-speech-to-text/pricing). Il faut simplement se créer un compte.

---

Bon courage !

[![Bon chance](https://img.youtube.com/vi/7OGpsoJ1kwk/0.jpg)](https://www.youtube.com/watch?v=7OGpsoJ1kwk)

