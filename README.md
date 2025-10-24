EXERCICE 1:

Objectif
Mettre en œuvre le principe d’interface en Java pour créer un système de paiement flexible et extensible, capable de gérer plusieurs moyens de paiement sans modifier la logique principale.

Fonctionnalités principales
PaymentMethod : définit les méthodes pay(), refund() et getName().
CreditCard / PayPal / Bitcoin : implémentent le contrat avec leurs attributs spécifiques (solde, identifiant, etc.).
PaymentProcessor : gère dynamiquement un tableau de PaymentMethod et applique les paiements + remboursements.
Main : crée des moyens de paiement, les ajoute au processeur et lance les transactions.

<img width="1226" height="424" alt="image" src="https://github.com/user-attachments/assets/e379aaee-c686-4cf2-8e8c-d1e51a28aeb8" />

EXERCICE 2:

Objectif
Mettre en œuvre le principe d’interface en Java pour créer un système de notification extensible, où plusieurs canaux (Email, SMS, Push) respectent un contrat commun et sont gérés dynamiquement par un gestionnaire unique.

Fonctionnalités principales
Notification (interface) : définit les méthodes send(), getPriority() et getType().
EmailNotification / SMSNotification / PushNotification : implémentent chacune le contrat avec un comportement spécifique.
NotificationManager :
Gère un tableau dynamique de canaux (Notification[]).
Trie les notifications selon la priorité décroissante.
Diffuse un message à tous les canaux enregistrés.
Main : crée et enregistre plusieurs canaux, puis envoie des messages à différents destinataires.

<img width="1430" height="443" alt="image" src="https://github.com/user-attachments/assets/b5be4e7a-c979-46d9-a376-2cc632bee6e0" />
