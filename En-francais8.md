---
layout : default
---

On peut tout à fait, et c'est le cas ici, créer deux schémas de conversation dans le même bot

À noter : les inputs étant les mêmes que les intents, on les entre une fois dans les intents et après ils ne changent plus. C'est la raison pour laquelle ils ne vont pas être réécrits dans les exemples suivants. Le même intent compte donc plusieurs outputs différents.

    #Contact
    Input : contact
    Output : 
    Voulez-vous donner votre numéro de téléphone ?
    <action = getphoneyesno>[Oui][Non]

<div style="float:left;width:5%" markdown="1">

 ![image](/assets/images/assignment.png) 
</div> On va insérer une variable. Il faut écrire la valeur de la variable à l'intérieur du carré qui résulte de la pression sur le bouton insert variable assignment.<br>


<br>#Oui<br>
Input : Oui<br>
Output :<br>
action = getphoneyesno <br>
Quel est votre numéro de téléphone? ![image](/assets/images/phonenbr.png)<br>
<action=confirmphonenbr>









<div style = "text-align:center" markdown="1">
<a href="En-francais7.html" class="previous">&laquo; Previous</a>
<a href="En-francais9.html" class="next">Next &raquo;</a>
</div>

