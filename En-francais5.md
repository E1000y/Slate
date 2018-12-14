---
layout : default
---

#Bonjour <br>
Input: <br> bonjour<br>
bjr<br>
output: Voulez-vous une pizza sucrée? [Oui] [Non] <action=sweetyesno>


![image](/assets/images/image3.png)

Le texte action = sweetyesno doit être recopié dans la conditionnelle suivante pour lier l'intent #Bonjour à l'intent #Oui suivant. On va suivra la branche des Oui pour enter les deux Outputs contenus dans l'intent #Oui sur la branche de gauche du schéma.

#Oui<br>
Input : Oui<br>
Output : <br>
action=sweetyesno<br>
Est-ce que vous voulez des pommes?
[Oui][Non]<action = pommesyesno>

![image](/assets/images/pommesyesno.png) 

#Oui<br>
Input : Oui <br>
Output :<br>
action=pommesyesno<br>
C'est parti pour une pizza pommes chocolat <br>

![image](/assets/images/pommes-chocolat.png) 

Félicitations, vous avez écrit votre première branche de schéma conversationnel! Maintenant nous allons rajouter le Non qui conduit à Pizza tout chocolat.




<div style = "text-align:center" markdown="1">
<a href="En-francais4.html" class="previous">&laquo; Previous</a>
<a href="En-francais6.html" class="next">Next &raquo;</a>
</div>

