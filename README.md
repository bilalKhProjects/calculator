# Calculator - Projet Gradle

Ce projet est une simple calculatrice implémentée en utilisant Java et construite avec Gradle. Il offre une interface utilisateur basique en ligne de commande pour effectuer des opérations arithmétiques simples telles que l'addition, la soustraction, la multiplication et la division.

## Fonctionnalités :

### Opérations basiques : 
Effectuez des opérations arithmétiques de base comme l'addition, la soustraction, la multiplication et la division.

### Gestion des erreurs : 
Le programme gère les entrées utilisateur incorrectes ou non valides et fournit des messages d'erreur appropriés pour guider l'utilisateur.

### Tests unitaires : 
Le projet est livré avec une suite de tests unitaires pour garantir le bon fonctionnement des fonctionnalités de base.

### Couverture de code : 
Utilisation de JaCoCo pour générer des rapports de couverture de code, permettant ainsi de vérifier la qualité des tests effectués sur le code.

### Analyse statique du code :
Utilisation de Checkstyle pour maintenir une cohérence dans le code et éviter les erreurs de style.

## Instructions d'utilisation :

### Installation de Gradle : 
Assurez-vous d'avoir Gradle installé sur votre système. Si ce n'est pas le cas, vous pouvez le télécharger et l'installer à partir du site officiel de Gradle.

### Clonage du repository : 
Clonez ce repository sur votre machine locale en utilisant la commande suivante : 
`git clone https://github.com/votre-utilisateur/calculator.git`

### Compilation du projet : 
Naviguez vers le répertoire du projet et exécutez la commande suivante pour compiler le projet avec Gradle : 
`./gradlew compileJava`

### Exécution des tests unitaires :
Exécutez les tests unitaires en utilisant la commande : 
`./gradlew test`

### Couverture de code : 
Générez des rapports de couverture de code à l'aide de JaCoCo :
`./gradlew jacocoTestReport`

### Analyse statique du code : 
Exécutez l'analyse statique du code avec Checkstyle :
`./gradlew checkstyleMain`

### Structure du projet :
src/: Ce répertoire contient le code source Java de la calculatrice.

main/java/: Contient les fichiers source Java principaux.
Calculator.java: Classe principale de la calculatrice, contenant la logique métier pour effectuer les opérations.
test/java/: Contient les fichiers source Java pour les tests unitaires.
CalculatorTest.java: Fichier de test pour tester les fonctionnalités de la calculatrice.
build.gradle: Le fichier de configuration Gradle qui définit les dépendances du projet et les tâches de construction.

Jenkinsfile: Le fichier de pipeline Jenkins contenant les étapes de compilation, de test, de génération de rapports, et d'analyse statique du code.

### Auteur :
Ce projet a été développé par KHARBACH Bilal. N'hésitez pas à me contacter si vous avez des questions ou des suggestions concernant ce projet.

Nous espérons que cette calculatrice vous sera utile pour effectuer vos calculs de base ! 🧮
