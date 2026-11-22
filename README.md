# Serveur dédié pas cher : combien coûte réellement l'entrée de gamme, quelles conditions se cachent derrière les prix d'appel et quel matériel vous obtenez pour ce tarif (tableaux comparatifs)

Un serveur dédié pas cher se situe aujourd'hui entre 4,74 € HT et 13 € HT par mois pour les prix d'appel, et entre 65 € et 115 € HT par mois pour la première machine réellement confortable. Scaleway annonce 4,74 €/mois avec un engagement de 12 mois sur sa gamme Start, Firstheberg affiche 12,99 € HT/mois pour un Intel Atom à 4 Go de RAM et 100 Mbit/s garantis. Au-dessus, ASN CLOUD démarre à 65 €/mois HT avec 32 Go de DDR4 ECC, OVHcloud à 114,99 € HT/mois plus 114,99 € de frais d'installation, et les configurations dédiées listées par AVA Hosting commencent à 95,32 $/mois pour un Ryzen 5 4650G avec du NVMe.

Trois lignes décident de la facture réelle : la durée d'engagement collée au prix affiché, les frais d'installation, et le débit garanti. Le reste, souvent, est du décor.

> **Trois profils, trois réponses**
>
> - Un site vitrine, un lab, une sortie de VPS : la machine à 12,99 € HT/mois suffit, à condition d'accepter 4 Go de RAM et 100 Mbit/s garantis.
> - Une base de données, deux ou trois sites, du trafic irrégulier : visez 32 Go de RAM et du NVMe. C'est la zone 33 € à 115 € par mois, engagement et frais d'installation inclus dans le calcul.
> - Un besoin de machine physique hébergée en France pour raison juridique : ASN CLOUD est le seul des opérateurs comparés ici à détailler la localisation Lyon / Grenoble et l'argument qui va avec.
>
> Deux lignes à vérifier avant de cliquer : la durée d'engagement et les frais d'installation. 👉 [parcourir les configurations dédiées listées chez AVA Hosting](https://my.ava.hosting/aff.php?aff=15562)

## Les configurations dédiées listées chez AVA Hosting

AVA Hosting présente quatre configurations dédiées sur sa boutique, de 95,32 $ à 167,09 $ par mois, facturées au mois. La moins chère n'est pas la plus ancienne : c'est un Ryzen 5 4650G (6 cœurs / 12 threads) avec 16 Go de DDR4, 256 Go de NVMe extensibles à quatre disques supplémentaires, un port 1 Gbit/s, une IPv4 et la protection DDoS annoncée sur l'ensemble des fiches.

| Configuration | Cœurs / threads | RAM et stockage | Prix affiché | Lien |
| --- | --- | --- | --- | --- |
| AMD Ryzen 5 4650G | 6C / 12T | dès 16 Go DDR4, dès 256 Go NVMe, jusqu'à 4 disques en plus | 95,32 $/mois | [voir la fiche Ryzen 5 4650G](https://my.ava.hosting/aff.php?aff=15562) |
| 2 × Intel Xeon E5-2680 v2 | 20C / 40T | 256 Go DDR3 ECC, 8 × 600 Go SAS, contrôleur RAID | 111,02 $/mois | [consulter la configuration double Xeon E5-2680 v2](https://my.ava.hosting/aff.php?aff=15562) |
| 2 × Intel Xeon E5-2620 v3 | 12C / 24T | dès 32 Go DDR4, dès 1 To SSD, contrôleur RAID | 134,57 $/mois | [examiner l'offre double Xeon E5-2620 v3](https://my.ava.hosting/aff.php?aff=15562) |
| 2 × Intel Xeon E5-2699 v3 | 36C / 72T | dès 32 Go DDR4, dès 1 To SSD, contrôleur RAID | 167,09 $/mois | [détail de la configuration 36 cœurs](https://my.ava.hosting/aff.php?aff=15562) |

Deux détails comptent avant de commander. Les tarifs sont affichés en dollars US sur la page boutique, pas en euros, donc la conversion et les éventuels frais de paiement international s'ajoutent à l'addition. Et chaque fiche porte un compteur de disponibilité : au moment de la consultation, la configuration Ryzen affichait 0 disponible, celle en double Xeon E5-2680 v2 une seule machine. Sur du bare metal, le stock est réel, il tourne vite, et une fiche à 0 ne se commande pas.

Le positionnement est cohérent avec le marché : à 95 $, vous n'achetez pas du low-cost, vous achetez une machine récente avec du NVMe. Ceux qui cherchent le tarif le plus bas possible doivent regarder plus bas dans le comparatif, avec les compromis que cela implique.

## Ce que coûtent les serveurs dédiés pas chers des autres opérateurs

Quatre opérateurs suffisent à cartographier le marché français de l'entrée de gamme. Les écarts de prix ne viennent pas du nombre de cœurs, mais de l'âge du matériel et du débit réellement garanti.

| Opérateur | Prix d'appel | Condition de facturation | Configuration d'entrée | Débit |
| --- | --- | --- | --- | --- |
| Scaleway (Dedibox) | 4,74 €/mois HT | engagement 12 mois | gamme Start, 4 Go de RAM, 1 SSD 120 Go | jusqu'à 1 Gbit/s selon le modèle |
| Firstheberg | 12,99 € HT/mois | prix affiché au 3 novembre 2026 | Intel Atom 2 cœurs 1,80 GHz, 4 Go, 2 × 500 Go HDD ou 1 × 128 Go SSD | 100 Mbit/s garantis, burst 1 Gbit/s |
| ASN CLOUD | 65 €/mois HT | mensuel | Xeon E5-2640 v3 8C/16T, 32 Go DDR4 ECC, 2 × 500 Go SSD | 300 Mbit/s garantis, burst 1 Gbit/s |
| OVHcloud (Advance) | 114,99 € HT/mois | + 114,99 € de frais d'installation | EPYC 4244P 6C/12T, 32 Go DDR5, 2 × 960 Go NVMe | 3 Gbit/s garantis et non comptés |

Le saut de prix entre 13 € et 65 € n'est pas une marge commerciale : c'est le passage d'un processeur Atom de 2 cœurs avec 4 Go de RAM à un Xeon 8 cœurs / 16 threads avec 32 Go de DDR4 ECC et deux SSD. Entre 65 € et 114,99 €, vous payez une génération de processeur (EPYC 4004 et DDR5), du NVMe, 3 Gbit/s garantis et une gamme de services autour.

## Pourquoi « dès 4,74 € » ne veut pas dire 4,74 €

La quasi-totalité des prix d'appel sont conditionnés. Sur les dix-huit configurations du tableau Scaleway, seize portent explicitement la mention « avec engagement 12 mois » ou « avec engagement 36 mois ». Le tarif sans engagement n'est pas affiché à côté, ce qui interdit de le présenter comme un prix mensuel libre.

Le chiffre d'appel lui-même bouge d'une page à l'autre : la page Dedibox annonce 4,74 €/mois avec engagement 12 mois, quand une autre page du même site affiche 4,99 €/mois pour la même gamme Start. Les deux sont officiels, l'écart est de 5 %.

L'engagement de 36 mois est plus lourd qu'il n'y paraît. Chez Scaleway, la configuration 6 cœurs avec 32 Go et 2 × 1 To NVMe est à 33,99 €/mois avec engagement 36 mois, et la machine 8 cœurs EPYC 4345P avec 64 Go à 101,99 €/mois, également sur 36 mois. Vous bloquez le tarif, mais aussi la machine : au bout du contrat, le matériel a trois ans et les générations suivantes sont passées.

Les frais d'installation sont l'autre ligne qui disparaît des comparaisons. Chez OVHcloud, chaque configuration Advance les facture à hauteur d'un mois de loyer : ADVANCE-12024 à 114,99 € HT/mois, ADVANCE-22024 à 154,99 €, ADVANCE-12026 à 159,99 €, ADVANCE-32024 à 199,99 €, avec à chaque fois des frais d'installation du même montant. Sur la première, la première année coûte 13 × 114,99 € = **1 494,87 € HT**, et non 12 × 114,99 € = 1 379,88 €. Les 114,99 € d'écart représentent 8 % de la facture annuelle, sans contrepartie matérielle.

👉 [vérifier les tarifs et la disponibilité actuels sur la boutique AVA Hosting](https://my.ava.hosting/aff.php?aff=15562)

## Débit garanti et burst : la ligne qui change vraiment l'usage

Un port 1 Gbit/s ne veut pas dire 1 Gbit/s utilisables en permanence. Firstheberg garantit 100 Mbit/s sur son offre Atom, avec une connexion 1 Gbit/s et du burst à 1 Gbit/s. ASN CLOUD annonce 300 Mbit/s garantis en continu sur un port 1 Gbit/s, avec la possibilité de monter jusqu'à 1 Gbit/s pour absorber les pics, sans surfacturation. OVHcloud parle de 3 Gbit/s publics non comptés et garantis sur la gamme Advance, plus 25 Gbit/s de réseau privé.

La différence entre garantie et burst se traduit en heures. À 100 Mbit/s, le plafond théorique est de 12,5 Mo/s : une sauvegarde de 100 Go prend plus de deux heures si le débit tient. À 300 Mbit/s garantis, la même opération tombe sous les 45 minutes. Pour un site vitrine, personne ne le remarque. Pour de la distribution de fichiers, de la vidéo, de la réplication ou des sauvegardes nocturnes, c'est la contrainte principale de l'offre à 13 €.

Le burst n'est pas une ressource réservée. Il absorbe les pics quand la capacité est disponible sur le réseau, ce qui est le cas la plupart du temps, mais ne constitue aucun engagement contractuel. Un hébergeur qui écrit « jusqu'à 1 Gbit/s » ne garantit rien du tout, et c'est précisément la formulation employée par Scaleway sur la majorité de ses lignes Start.

👉 [comparer les configurations dédiées et leurs caractéristiques réseau](https://my.ava.hosting/aff.php?aff=15562)

## Le support 24/7 est souvent une option payante

C'est le poste où les grilles tarifaires sont les plus discrètes. Firstheberg inclut un support technique et commercial, avec un délai d'intervention matériel et réseau de 2 heures ouvrées et un rétablissement sous 4 heures ouvrées. Hors heures ouvrées, les mêmes engagements passent en « best effort ». L'intervention 24h/7 et le support incident 24h/7 ne sont disponibles qu'à partir de l'option Critique, facturée en supplément.

ASN CLOUD annonce un support par ticket, e-mail et téléphone du lundi au vendredi, 8 h–18 h, hors jours fériés, avec extension sur devis. Pour une panne un samedi soir, vous ouvrez un ticket et vous attendez le lundi.

Les fiches produit d'AVA Hosting mentionnent un support 24/7 sur les quatre configurations dédiées, y compris l'entrée de gamme. C'est une différence de nature avec les deux précédents, à confirmer au moment de la commande si votre activité ne supporte pas l'attente.

Le SLA mérite le même examen. Firstheberg annonce 99,95 % et Scaleway 99,9 %, OVHcloud 99,95 % sur la disponibilité réseau avec des crédits de service en cas de manquement. Un pourcentage sans mécanisme de compensation est un affichage, pas une garantie.

## Génération de matériel : le critère que les tableaux de prix masquent

Un Atom 2 cœurs à 1,80 GHz avec 4 Go de RAM et 571 points de benchmark, c'est une machine pour un site à faible trafic, un serveur de test ou une passerelle. Pas pour une base de données, pas pour de la virtualisation, pas pour un Prestashop avec 3 000 références.

À 65 €, ASN CLOUD passe au Xeon E5-2640 v3 (8 cœurs / 16 threads, 2,6 à 3,4 GHz) avec 32 Go de DDR4 ECC et deux SSD de 500 Go. Toute la gamme reste sur des Xeon E5 v3, une génération ancienne mais homogène et correctement dimensionnée en mémoire.

À 114,99 €, OVHcloud saute deux générations avec des EPYC 4004, de la DDR5 à 5200 MHz et du NVMe 960 Go en classe Enterprise. Le nombre de cœurs est identique à celui du Xeon à 65 € (6C/12T sur ADVANCE-12024), la différence se joue ailleurs : fréquence, bande passante mémoire, latence de stockage.

Chez AVA Hosting, la même logique est visible dans la grille. Le Ryzen 5 4650G à 95,32 $ est la machine la plus moderne de la liste, en NVMe. Le double Xeon E5-2680 v2 à 111,02 $ aligne 20 cœurs et 40 threads, mais avec de la DDR3 et huit disques SAS de 600 Go. Sur une charge applicative classique, les 20 cœurs DDR3 ne compensent pas l'écart de génération. Le nombre de cœurs est l'argument le plus facile à afficher et le moins prédictif de ce que vous obtiendrez.

## Livraison, sauvegardes, adresses IP : les coûts qui arrivent après

Une sauvegarde n'est jamais incluse par défaut dans ces tarifs. ASN CLOUD facture le stockage de sauvegarde NFS et Proxmox Backup Server à 0,02 € HT/Go/mois, soit environ 10 € HT/mois pour 500 Go et 20 € pour 1 To. Firstheberg annonce une option Backup FTP de 100 Go, mais la mention « Prochainement » indique qu'elle n'est pas encore commandable : ne la comptez pas dans votre plan.

D'autres lignes s'ajoutent selon les usages. Chez Firstheberg, une IPv4 fail-over démarre à 1,99 € HT/mois et l'option Ticket+ (trois tickets simultanés et priorisation) à 2,99 € HT/mois. Chez AVA Hosting, une IPv4 est incluse par configuration, avec des add-ons optionnels.

La livraison n'est pas instantanée partout. ASN CLOUD annonce 24 à 72 heures ouvrées entre la commande et la mise à disposition, avec possibilité de préparer le matériel en amont. Un projet qui doit être en ligne le soir même doit en tenir compte.

## Quel serveur dédié pas cher pour quel usage

**Un site vitrine, un environnement de test, une migration depuis un VPS.** L'Atom à 12,99 € HT/mois fait le travail, à condition d'accepter 4 Go de RAM et 100 Mbit/s garantis. La gamme Start de Scaleway joue le même rôle pour moins cher, avec un engagement de 12 mois à accepter.

**Une base de données, deux ou trois sites, du trafic irrégulier.** Il faut 32 Go de RAM et du NVMe. Trois options se tiennent : Scaleway à 33,99 €/mois sur 36 mois, OVHcloud ADVANCE-12024 à 114,99 € HT/mois plus frais d'installation, ou le Ryzen 5 4650G d'AVA Hosting à 95,32 $/mois avec 16 Go extensibles et du NVMe. La première est la moins chère, la deuxième la plus récente techniquement, la troisième la plus rapide à mettre en œuvre si le stock est disponible.

**De la mémoire à bas coût au volume.** Le double Xeon E5-2680 v2 d'AVA Hosting à 111,02 $ embarque 256 Go de DDR3 ECC et huit disques SAS. Pour de la virtualisation légère ou du stockage, ce type de configuration reste difficile à battre au gigaoctet de RAM, à condition d'accepter une plateforme ancienne.

**Un impératif de localisation.** ASN CLOUD héberge à Lyon-Vénissieux et à Grenoble, avec un argumentaire explicite sur la juridiction française et le Cloud Act. Si ce critère est décisif, vérifiez la localisation physique des machines auprès du fournisseur retenu avant de payer, y compris chez AVA Hosting : la boutique ne l'affiche pas dans les fiches produit.

## Questions fréquentes

**Un serveur dédié à 13 € peut-il remplacer un VPS à 5 € ?**
Oui pour la charge, non pour la souplesse. Un dédié vous réserve la machine entière, sans voisin ni contention de ressources, ce qu'un VPS ne peut pas garantir puisque ses ressources physiques sont partagées. En contrepartie, vous héritez d'un Atom ancien et de 100 Mbit/s garantis, là où un VPS récent offre souvent du NVMe et davantage de RAM pour moins cher.

**À quoi sert l'IPMI concrètement ?**
IPMI est une interface de management bas niveau intégrée à la carte mère. Elle donne accès à la console BIOS, permet un redémarrage matériel, l'installation d'un système depuis une image ISO et le diagnostic de panne, comme si vous étiez devant la machine. ASN CLOUD l'inclut sur toutes ses formules, et les fiches AVA Hosting mentionnent un accès de management à distance sur les configurations Xeon.

**300 Mbit/s garantis sur un port 1 Gbit/s, c'est contradictoire ?**
Non. Le port physique tourne à 1 Gbit/s, les 300 Mbit/s correspondent au débit garanti en continu. Le surplus sert à absorber les pics, sans surfacturation chez ASN CLOUD. C'est un plancher contractuel, pas un plafond.

**Pourquoi le prix de renouvellement est-il parfois introuvable ?**
Parce que le champ n'est pas toujours rempli. Sur la fiche Firstheberg consultée le 3 novembre 2026, la mention « Le prix au renouvellement sera de € HT/mois » apparaît avec un montant vide. Le 12,99 € est donc un prix affiché à un instant donné, pas une promesse de stabilité. Demandez le tarif de renouvellement par écrit avant de commander.

**Un SLA de 99,95 %, ça compense une panne ?**
Seulement s'il est assorti de crédits de service. OVHcloud les mentionne explicitement sur la gamme Advance. Ailleurs, vérifiez ce que le pourcentage déclenche réellement.

## Ce qu'il faut vérifier avant de payer

Le choix se résume à trois règles. Un besoin ponctuel ou un site à faible trafic : prenez l'entrée de gamme la moins chère, en assumant les 4 Go de RAM et le débit garanti à trois chiffres. Un usage qui produit de la valeur : visez 32 Go de RAM et du NVMe, et comparez le coût de la première année, frais d'installation inclus, plutôt que le prix mensuel affiché. Un besoin de mémoire ou de stockage massif : les configurations à base de Xeon E5 restent pertinentes, à condition de ne pas attendre d'elles la performance d'un processeur récent.

Trois vérifications avant de valider un panier : la durée d'engagement attachée au prix, l'existence et le montant des frais d'installation, et le débit garanti en continu, distinct du burst. Ajoutez-y le prix du renouvellement et celui de la sauvegarde, qui ne figurent presque jamais dans la colonne « à partir de ».

👉 [voir les offres dédiées actuellement listées chez AVA Hosting](https://my.ava.hosting/aff.php?aff=15562)
