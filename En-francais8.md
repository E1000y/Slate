---
layout : default
---

On peut tout à fait, et c'est le cas ici, créer deux schémas de conversation dans le même bot

À noter : Un intent compte souvent un ou deux inputs pour plusieurs outputs différents.

    #Contact
    Input : contact
    Output : 
    Voulez-vous donner votre numéro de téléphone ?
    <action = getphoneyesno>[Oui][Non]

![image](/assets/images/Contact-getphoneyesno.png)


Cliquer sur le signe plus et sur SAVE;


<div style="float:left" markdown="1">

 ![image](/assets/images/assignment.png) 
</div> On va insérer une variable. Il faut écrire la valeur de la variable à l'intérieur du carré qui résulte de la pression sur le bouton insert variable assignment.<br>


<br>#Oui<br>
Input : Oui<br>
Output :<br>
action = getphoneyesno <br>
Quel est votre numéro de téléphone? ![image](/assets/images/phonenbr.png)<br>
<action=confirmphonenbr>

![images](/assets/images/Oui-Contact.png)

Cliquer sur le signe plus et sur SAVE.


## 1. Les intents #Any

On va créer un intent #Any:

on clique sur créer un nouvel intent, on renomme l'intent en #Any, et on clique sur insert block any dans les inputs de #Any :

![images](assets/images/any-block-input.png)

Ensuite on paramètre l'output 












<div style = "text-align:center" markdown="1">
<a href="En-francais7.html" class="previous">&laquo; Previous</a>
<a href="En-francais9.html" class="next">Next &raquo;</a>
</div>

