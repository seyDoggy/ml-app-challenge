## Défi d'application
##### Défi de programmation pour les candidats potentiels
### Instructions
1. L'objectif est de créer une application mobile native exécutable répondant aux critères d'acceptation ci-dessous.
2. Les données requises pour chaque vue sont contenues dans le dossier /data.
3. Vous êtes libre d'utiliser des frameworks ou des plugins pour vous aider dans cette tâche. Si vous le faites, veuillez expliquer pourquoi.
4. Vous disposez d'une liberté de création pour concevoir l'interface utilisateur à votre convenance pour afficher les données.
5. Indiquez toutes les instructions nécessaires pour créer et exécuter votre application.
6. Les instructions pour partager votre code avec nous auront été fournies par e-mail.

### Critères d'acceptation
**SCÉNARIO: L'utilisateur lance votre application pour la première fois.**   
LORSQUE l'utilisateur est sur l'écran d'accueil de son appareil mobile   
ET l'utilisateur n'a jamais ouvert l'application auparavant   
QUAND l'utilisateur ouvre l'application   
ALORS l'utilisateur se voit alors proposer une page de destination avec un bouton intitulé "Ouvrir".
___
**SCÉNARIO: L'utilisateur tape sur "Ouvrir"**       
LORSQUE l'utilisateur est sur la page d’accueil de l’application   
QUAND l'utilisateur appuie sur le bouton "Ouvrir"   
ALORS l'utilisateur est amené à une page avec une liste de ses comptes   
ET quelques données pour chaque compte   
ET la page a un bouton "Quitter" dans la barre de navigation.
___
**SCÉNARIO: L'utilisateur lance votre application plusieurs fois successivement**       
LORSQUE l'utilisateur est sur l'écran d'accueil de son appareil mobile      
ET l'utilisateur a déjà ouvert l'application auparavant     
ET l'utilisateur n'a pas tapé sur le bouton "Quitter" lors de sa session précédente     
QUAND l'utilisateur ouvre l'application     
ALORS l'utilisateur est amené à une page avec une liste de ses comptes  
ET quelques données pour chaque compte  
ET la page a un bouton "Quitter" dans la barre de navigation.   
___
**SCÉNARIO: L'utilisateur veut voir les transactions d'un compte particulier**  
LORSQUE l'utilisateur visualise une liste de comptes    
QUAND l'utilisateur tape sur un compte spécifique   
ALORS L'utilisateur est alors présenté une vue contenant un historique des transactions pour ledit compte.
___
**SCÉNARIO: L'utilisateur veut arrêter de visualiser une liste de comptes**     
LORSQUE l'utilisateur visualise une liste de comptes    
QUAND l'utilisateur appuie sur le bouton "Quitter"  
ALORS L'utilisateur se voit rediriger vers la page d’accueil de l’application avec un bouton intitulé "Ouvrir". 
 
