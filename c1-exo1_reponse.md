Exercice 1 : Les trois cadences

1. La formule employée
La cadence d'affichage se donne en hertz, c'est-à-dire en images par seconde. La durée d'une seule image est donc l'inverse de cette cadence, exprimé en millisecondes :
T (ms) = 1000 ÷ f (Hz)
Le chapitre indique que quatre étapes échappent entièrement à notre programme : les capteurs (1 à 2 ms), la transmission (1 à 3 ms), la composition (1 à 2 ms) et l'affichage de la ligne (2 à 5 ms). En retenant une valeur médiane de 8 ms pour l'ensemble, le temps qui reste au code est :
T (code) = T (image) − 8 ms
2. Les opérations posées
Cas n°1 : 72 hertz
Durée d'une image
T = 1000 ÷ 72
   = 13,8888… ms
   = 13,9 ms	Ce qu'il reste au code
      13,9 ms
−     8,0 ms
=     5,9 ms


Cas n°2 : 90 hertz
Durée d'une image
T = 1000 ÷ 90
   = 11,1111… ms
   = 11,1 ms	Ce qu'il reste au code
      11,1 ms
−     8,0 ms
=     3,1 ms


Cas n°3 : 120 hertz
Durée d'une image
T = 1000 ÷ 120
   = 8,3333… ms
   = 8,3 ms	Ce qu'il reste au code
      8,3 ms
−     8,0 ms
=     0,3 ms





