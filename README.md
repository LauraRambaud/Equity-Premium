# Equity-Premium


Tâches / Remarques à faire
format texte ! 

remarques codes / data : 

read me et autre / ce que je fais


------ Collecte data ------ 
- vérif dispo data avant 1990 pour justifier cette date comme date de départ dans mon mémoire
- il me faut -36m pour mom36m et beta
- il me faut 2 actions en + 
- MO est suspect 

------ IMPUTER ------ 
- déjà je comprends pas vraiment pourquoi je ne fais pas interpolate (au lieu de la moyenne)
- vérif excel > moyenne fausse 

CALCULS COVARIATES
- en général : pour le loc de partout ??

------ Yearly ------ 
- yearly : enlever les .loc
- vérifier la puissance et pq c'est puissance SIX (j'étais sûre que c'était 5)
- cashpr → mal calculé, des valeurs aberrantes 
- ajustement facteur : vérifier sur Bloomberg / envoyer un mail au client 

------ Monthly ------ 
- prendre l'année fiscale pour PX LAST et volume c'est très très con (par exemple Apple s'arrête en septembre 2020 
il manque donc forcément la fin de l'année, il faut prendre des années complètes : je vais enlever l'année 2020 pour l'instant
comme elle sera incomplète pour d'autres données aussi)
- dates manquantes en monthly (vérifier si le rempmlissage se fait bien) : 
29/03/1991
31/05/1999
29/03/2002
31/05/2004
31/05/2010
29/03/2013
30/03/2018
- vérifier la définition de dolvol
- idiosyncratic : il me manque le retour hebdomadaire du marché... + voir le taux sans risque hebdomadaire. 
- illiquidity : idem (demander par mail)
- indmom → vérifier et voir avec mon prof (ce qu'il avait trouvé j'ai oublié)

- faire vérifier à mon prof le calcul des momentums (deux compositions ??)
- size → est-ce que c'est un log ? vérifier le tran + le papier de Gu et al
- stdturn → il me faut les shares daily haha lol

- baspread > mal calculé il me faut les informations daily 
- cashpr > mal calculé LOL + aberrant 

------ Quarterly ------ 
- il faut commencer un trimestre avant 