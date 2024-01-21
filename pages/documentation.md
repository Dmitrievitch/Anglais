<img src="/pages/images/tags.png" alt="test">

# Manuel d'utilisateur du logiciel Anki

La lecture des paragraphes qui suivent est indispensable pour une bonne compréhension de cet outil. Nous avons fait le choix d'Anki, notamment pour sa puissance et sa gratuité
(contrairement à quizlet par exemple). Vous trouverez la documentation officielle [ici](https://apps.ankiweb.net/docs/manual.fr.html).
Une lecture attentive de cette dernière est recommandée. En tout état de cause, nous exposons ci-dessous les fonctionnalités utilisées.

## Présentation

Anki est un logiciel libre permettant d'apprendre et de réviser des cartes-mémoires grâce à la répétition espacée. Son algorithme se base sur la courbe d'Ebbinghaus.

Vous pouvez télécharger Anki [ici](https://apps.ankiweb.net/). Notez que la version Windows/Linux/MacOS/Android est gratuite. La version iOS est quant
à elle payante. Néanmoins, les révisions sont toujours possibles gratuitement depuis n'importe quelle plateforme via le site web [ankiweb.net](https://ankiweb.net) mais
les fonctionnalités sont moindres (pas la possibilité de faire de **révisions personnalisée**). L'utilisation d'un ordinateur reste recommandée.

## Organisation

Anki fonctionne par **cartes** qui se trouvent dans des **paquets**.
À chaque couple de mots, mettons **apple** et **pomme**, deux cartes correspondantes sont créées : une carte **recto = apple** avec **verso = pomme** ainsi
qu'une autre carte **recto = pomme** avec **verso = apple**. Cela, afin d'éviter que l'élève ne retienne son vocabulaire que dans un seul sens.

## Paquets

À chaque carte (par carte nous sous-entendons un duo de carte (puisque deux cartes adjacentes sont équivalentes en contenu)) est associé une balise (tag en anglais).
Explicitons leur utilité. En effet, anki gère très mal les grandes quantités de paquets. Par exemple, si je veux apprendre le livre de **la vie** qui contient les chapitres orgueil, avarice, luxure, envie, gourmandise, colère et paresse, rentrer directement chacun de ces chapitre sous forme de paquet indépendant dans anki serait contre productif (il faut imaginer une situation où il y aurait des dizaines de chapitres pour chaque matière et donc des centaines de paquets).
C'est pourquoi nous rentrons tous ces chapitres dans un seul gros paquet nommé **la vie** et à chaque carte nous associons une balise (balise orgueil, balise avarice, etc.). De fait, nous passons
d'une structure en dossier (très lourde) à un structure en balise (très légère).

Tous les mots de vocabulaire, idiomes et points de culture du manuel *The Big Picture* sont tapés dans le paquet **Anglais**.
Il s'avère que l'on ne révise pas à la même cadence une série de vocabulaire, qu'une série de phrases ou encore qu'une série de paragraphes.
C'est pourquoi, le vocabulaire, les idiomes et la culture se trouvent dans les sous paquets respectifs **Vocabulaire**, **Idiomes** et **Culture**.

L'image ci-dessous illustre cette arborescence.

![accueil](/pages/images/tags.png)

De fait, il devient possible de faire une séance "apprentissage/révision des idiomes anglais" indépendamment d'une séance "apprentissage/révision du vocabulaire anglais".

## Apprentissage et révisions

Lorsque vous décidez d'étudier un paquet, dans un premier temps vous tombez sur un mot (anglais ou français) comme ci-dessous.

![recto](/images/recto.png)

À ce moment, vous cherchez mentalement (ou à voix haute !) le traduction puis vous vérifiez votre réponse comme ci-dessous.

![verso](/images/verso.png)


## Tags

Une utilisation d'Anki **quotidienne** vous permettra d'assimilier l'entièreté du vocabulaire du manuel de façon douce, puisque chaque jour Anki vous fera apprendre des nouveaux mots
et vous fera réviser les anciens mots. La fréquence d'apparition d'un mot se base sur vos performances 
Si je veux réviser le chapitre **Health_issues** de la partie lifestyles, le tag correspondant est Anglais::Lifestyles::Health_issues::Vocabulaire. Attention à la syntaxe de la commande.
Cette dernière décrit l'arborescence ci-dessous.

![tags](/images/tags.png)

## Notations

La façon dont est rédigé le vocabulaire d'anglais reproduit strictement celle du manuel *The Big Picture*. Nous nous proposons d'en expliciter la forme :
- le slash **/** permet de distinguer différentes tournures. Exemple : **a beautiful / pretty / graceful hat** appelle la traduction **un beau / joli / gracieux chapeau**.
- la virgule **,** permet de distinguer différentes traductions. Exemple : **a thief, a robber** appelle la traduction **un voleur #2**. Notez ici la présence du **#2** qui indique que
lorsque je suis en présence du mot **voleur #2**, on attend de moi deux traductions en anglais. Même principe dans le sens contraire et/ou avec un plus grand nombre de traductions.
- Notez les abréviations courantes : **sb** pour **somebody**, **qn** pour **quelqu'un**, **sth** pour **something**, **qch** pour **quelque chose**.


## Révisions

Le vocabulaire de chaque chapitre est entièrement tapé dans les paquets. Certains trouveront cela embêtant car ils connaîtrons peut être déjà certains mots, mais dans la mesure
où les paquets s'adressent à un large public, il était nécessaire de rentrer tous les mots afin d'éviter des disparîtés entre élèves. En outre, une piqûre de rappelle ne fait pas de mal, et s'il
s'avère que le mot est réellement su du fond du coeur, l'algorithme d'Anki se chargera d'enterrer la carte correspondante.

De façon générale, je publie un jeu de carte (qui équivaut à un chapitre) par semaine le vendredi ou samedi soir. De fait il est possible d'entamer les révisions dès lundi. Dans la mesure où chaque chapitre contient moins de 100 mots, une utilisation **quotidienne** de Anki permet en apprenant moins de 20 mots par jour, de finir son vocabulaire de façon naturelle dans la semaine. Lorsque Mme Binet annonce
les échéances, je tape les chapitres correspondants. En dehors des échéances, je tape les autres chapitres.

## Révisions personnalisée

Par défaut, Anki voudra vous faire apprendre 30 mots par jours (quota changeable) qui se trouvent dans le paquets **Anglais**. Or ce paquet contient tous les chapitres tapés jusqu'à présent. Certes, il est intéressant de réviser et d'apprendre tous les jours du vocabulaire divers mais pour les échéances, c'est moins pratique.

C'est pourquoi, si j'ai besoin de réviser le chapitre **Health_issues** pour la semaine prochaine, je vais dans le paquet **Vocabulaire** et je fait **Révisions personnalisée** puis **Etude par carte ou tag**.

Dans un premier temps on sélectionne un nombre de carte suffisamment grand.
Ensuite deux cas sont à distinguer pour une échéance au 6 janvier:
- Je suis le 1er janvier, je sélectionne **Seulement les nouvelles cartes**
- Je suis le 5 janvier, je sélectionne **Toutes les cartes dans un ordre aléatoire**

Puis, il faut choisir le tag Anglais::Lifestyles::Health_issues::Vocabulaire
