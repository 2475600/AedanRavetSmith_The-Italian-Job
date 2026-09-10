The italian job - Piratage du système de contrôle de circulation.

Aedan Ravet Smith

L'exemple choisi est le film "The italian Job" (2003), plus précisément la scène ou Lyle pirate le système de contrôle des feux de circulations de Los Angeles. 
[Extrait de la scène](https://clip.cafe/the-italian-job-2003/you-want-all-greens-s1/)

## Résumé

Dans "The italian Job" (2003), Lyle surnommé Napster est le membre de l'équipe spécialisé en informatique. Il pirate le système qui contrôle les feux de circulation de Los Angeles. Il réussi à prendre le contrô des feux et les utilises pour créer des accidents eft des embouteillages afin d'aider son équipe a s'enfuir après le vol. 
Cette scène montre comment le piratage d'un système informatique peut avoir des conséquences dans le monde réel, particulièrement lorsqu'il s'agit d'une infrastructure importante. 

## Vulnérabilité / exploit / correctif

Black Hat : Lyle est un black hat puisqu<il accède à un système sans autorisation et l'utilise à des finds criminelles.
Faille : La sécurité du système de contrôle permet à Lyle d'obtenir un accès non autorisé au système.
Exploit : Une fois connecté, Lyle prend le contrôle des feux de circulation et modifie leur foncitonnement pour provoquer des accidents et des embouteillages.
Correctif : Le système devrait utiliser une authentification forte, une segmentation du réseau, des permissions limitées et une surveillance des connexions. Un système de secours devrait également permettre de reprendre rapidement le contrôle des feux en cas d'attaque.

## Confidentialité, intégrité ou disponibilité / CVSS 4.0

Confidentalité : faible - Lyle ne cherche pas principalement à voler des informations.
Intégrité : élevée - Il modifie direcement le fonctionnement des feux de circulation.
Disponibilité : élevée - L'attaque perturbe le fonctionnement normal de la circulaiton et crée des embouteillages.

AV:N (Network) - L'accès au système peut être effectué à distance par le réseau.
AC:L (Low) - Une fois l'accès obtenu, l'attaque ne semble pas nécessiter de manipulation complexe.
AT:N (None) - Aucun événement particulier supplémentaire n'est nécessaire pour réaliser l'attaque.
PR:N (None) - L'attaquand n'est pas censé avoir de privilège légitime avant l'attaque.
UI:N (None) - Aucune interaction d'un utilisateur n'est nécessaire,
VC:N (None) - La confidentialité des informations n'est pas réellement compromise.
VI:H (High) - Le fonctionnement normal de la circulation peut etre fortement perturvbé.
SC:N / SI:N / SA:N - L'attadque ne vise pas directement un autre système informatique.

Vecteur CVSS : `CVSS:4.0/AV:N/AC:L/AT:N/PR:N/UI:N/VC:N/VI:H/VA:H/SC:N/SI:N/SA:N`
Score cvss 4 .0 : 9,3 (Critique).

L'attaque est donc considérée comme critique puisqu'un accès à distance peut permettre de modifier fortement l'intégrité et la disponibilité d'une infrastructure importante.
