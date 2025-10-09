La mannette PS5 d'INTech paut etre util pour debuged des probleme ou juste faire plaisir a des personne

pour la connecter on fait les command suivant. la mannete PS5 banche battletron a pour mac C4:5D:FD:05:06:07

bluetoothctl

dans le teminal interactif.

scan on
pair <adresse_MAC>
trust <adresse_MAC>
connect <adresse_MAC>
exit

Si tout c'est bien passer allors la mannette passe d'une led blanche a un led bleu continue. 
Si la led devient rouge c'est quel a etait apairer en mode alternatif. il faut enlever avec la command remove <adresse_MAC_de_la_manette> puis ressayer.
