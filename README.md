# Spring-AOP-AspectJ
Ce TP est permet d’intégrer l’aspect de journalisation dans une application web MVC, ainsi que d’assurer l’intégrité des données et la sécurité d’accès.
Etape de ce TP
- Créer un projet Spring starter Boot en selectionnant le dependance spring Web, MySql Driver et Spring Data JPA
- Créer un package com.testAOP.model et y créer la classe Employee caractérisé par 2 strings empId et name. Générer le constructeur par défaut, paramétrique et les setters et getters.
- Créer un package com.testAOP.service et y ajouter la classe EmployeeService
- Créer le package com.testAOP.aspect et y ajouter la EmployeeServiceAspect
- Créer le package com.testAOP.controller et y ajouter la classe EmployeeController qui représente le controleur de notre application
