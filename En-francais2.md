

<p>
<div style="float:left;width:30px" markdown="1">

 ![image](/assets/images/insert-variable.png) 
</div>
1. Insert variable assignment :<br>
Il s'agit du bouton qui va permettre de stocker une valeur qui sera réutilisée par le bot plus loin dans la conversation

<p>
<div style="float:left;width:30px" markdown="1">

 ![image](/assets/images/chevrons.png) 
</div>
2. Insert code :

La syntaxe du code d'action à saisir sera &#60;action = name_of_action&#62. Il s'agit de la ligne de code d'action qui va permettre au bot de suivre le fil d'une conversation. On va mettre l'action dans un premier output d'intent, et la même syntaxe dans la conditionnelle de l'output d'intent suivant, ce qui va permettre de créer un chemin conversationnel.
</p>


<p>
<div style="float:left;width:30px" markdown="1">

 ![image](/assets/images/button.png) 
</div>
3. Button :

Permet de créer un bouton qui va être cliquable par l'utilisateur et qui donc va permettre de standadiser les inputs. On peut créer un bouton Oui, Non, ou n'importe quel input souhaité.
<p>

<p>
<div style="float:left;width:40px" markdown="1">

 ![image](/assets/images/trash.png) 
</div>
3. Trash :<br>
Ce bouton sert à supprimer un des trois items cliquables énoncés ci-dessus. Il faut d'abord supprimer le texte, puis cliquer sur le bouton pour le sélectionner, puis cliquer sur la corbeille.

</p>

### Ajout d'une conditionnelle
<p>

![image](/assets/images/conditional-in-output-options.png)

<div style="float:left;width:50px" markdown="1">

 ![image](/assets/images/conditional.png) 
</div>
5. Conditionnelle <br>
Quand on ouvre un nouvel intent, dans les outputs, supprimer la ligne "I don't understand." Apparaît alors une étoile à trois branches qu'on appelle une conditionnelle. Cette étoile est proposée tant que les outputs ne contiennent pas d'outputs non conditionnels. Elle doit contenir le même code que le code d'action qui précède, dans la logique de la conversation.
</p>