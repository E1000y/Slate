---
layout : default
---
    #Non <br>
    Input : non <br>
    Output: <br>
    action=pommesyesno<br>
    C'est parti pour une pizza tout chocolat!<br>


 ![image](assets/images/Tout-chocolat.png)

Ne pas oublier de cliquer sur SAVE avant d'essayer le schéma dans le playground.

Puis nous allons rajouter la branche de droite, 

    #Non<br>
    Input : non<br>
    Output : <br>
    action=sweetyesno<br>
    Voulez-vous des champignons ?
    [Oui][Non]<action=mushroomsyesno>

    #Oui<br>
    Input : oui<br>
    Output :<br>
    action = mushroomsyesno<br>
    C'est parti pour une Reine

    #Non<br>
    Input : non<br>
    Output :<br>
    action=mushroomsyesno<br>
    C'est parti pour une trois fromages !



Et voilà,  votre premier schéma de conversation est paramétré ! Passons maintenant à un exemple suivant, l'exemple de la prise de contact, qui gère des saisies manuelles effectuées par l'utilisateur.








<div style = "text-align:center" markdown="1">
<a href="En-francais5.html" class="previous">&laquo; Previous</a>
<a href="En-francais7.html" class="next">Next &raquo;</a>
</div>

