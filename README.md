
# Table de matières
- [Cahier des Charges](#cahier-des-charges)
- [Diagramme de cas d'utilisation](#use-case)
- [Diagramme de classe](#class)
- [Diagrammes de séquence](#sequence)
- [Collaborateurs](#Collaborateurs)

## <a name="cahier-des-charges"></a> Cahier des charges

On propose une plateforme d'éducation en ligne sous forme d'un site web complet dédié à l'enseignement du 
développement web et de la programmation. Cette ressource pédagogique offre une variété de 
tutoriels, de guides et de ressources interactives soigneusement élaborés pour répondre aux 
besoins des apprenants, qu'ils soient débutants ou avancés. Cette plateforme couvre un large 
éventail de langages de programmation, de technologies web et de concepts clés essentiels à la 
création de sites web dynamiques et interactifs [Cahier des Charges](https://github.com/Marouane124/Projet-UML/blob/main/Cahier%20des%20charges.pdf).

## <a name="use-case"></a> Diagramme de cas d'utilisation
![Use Case Diagram](https://github.com/Marouane124/Projet-UML/assets/110178036/81121ae7-5787-410e-8552-fc48d5e46f50)

## <a name="class"></a> Diagramme de classe
![Class Diagram](https://github.com/Marouane124/Projet-UML/assets/110178036/c31b00ab-1bab-465c-8d7d-33bec66b55d5)

## <a name="sequence"></a> Diagrammes de séquence
Les diagrammes de séquence que nous développerons illustreront l’utilisation de cinq cas d’utilisation spécifiques :
- [La création d'un nouveau cours par un administrateur](#sequence1)
- [La connection d'un administrateur à la platforme](#sequence6)
- [L'inscription d'un visiteur sur la platforme](#sequence2)
- [La connection d'un apprenant à la platforme](#sequence3)
- [Consultation d'un cours par un apprenant](#sequence4)
- [L'inscription d'un apprenant dans un cours](#sequence5)

Pour ce faire, nous aborderons la boîte blanche, qui nous permet de représenter les interactions entre les objets internes de l'application.
Dans cette structure, nous introduirons trois nouvelles classes; le contrôleur (Controller) qui est responsable de la logique de traitement, la classe view qui
représente le programme 'Main' qui s'interesse aux interactions de l'utilisater et lase Base de donnée qui s'occupera de la connection et les traitements sur la BD.

### <a name="sequence1"></a> La création d'un nouveau cours par un administrateur :
Ce modèle sera représenté par quatres classes supplémentaires : Admin, Cours, Section et Chapitre.
![diS](https://github.com/Marouane124/Projet-UML/blob/63903767719b58cfbe3ec2b018adc23a25e7bbb8/Diagrammes/Diagramme%20de%20sequence%20Y/ajouter%20nouveau%20cours!ajouter%20nouveau%20cours!ajouter%20nouveau%20cours_5.jpg)

### <a name="sequence6"></a> La connection d'un administrateur à la platforme :
Ce modèle sera représenté par une seule classe supplémentaire : Admin.
![diS](https://github.com/Marouane124/Projet-UML/blob/63903767719b58cfbe3ec2b018adc23a25e7bbb8/Diagrammes/Diagramme%20de%20sequence%20Y/se%20Connecter%20Admin!se%20Connecter%20Admin!se%20Connecter%20Admin_6.jpg)

### <a name="sequence2"></a> L'inscription d'un visiteur sur la platforme :
Ce modèle sera représenté par une seule classe supplémentaire : Apprenant.
![diS](https://github.com/Marouane124/Projet-UML/blob/63903767719b58cfbe3ec2b018adc23a25e7bbb8/Diagrammes/Diagramme%20de%20sequence%20Y/s'inscrire!s'inscrire!s'inscrire_0.jpg)

### <a name="sequence3"></a> La connection d'un apprenant à la platforme :
Ce modèle sera représenté par une classe supplémentaire : Apprenant.
![diS](https://github.com/Marouane124/Projet-UML/blob/63903767719b58cfbe3ec2b018adc23a25e7bbb8/Diagrammes/Diagramme%20de%20sequence%20Y/se%20Connecter%20Apprenant!se%20Connecter%20Apprenant!se%20Connecter%20Apprenant_2.jpg)

### <a name="sequence4"></a> Consultation d'un cours par un apprenant :
Ce modèle sera représenté par une classe supplémentaire : Cours.
![diS](https://github.com/Marouane124/Projet-UML/blob/63903767719b58cfbe3ec2b018adc23a25e7bbb8/Diagrammes/Diagramme%20de%20sequence%20Y/consulter%20les%20cours!consulter%20les%20cours!consulter%20les%20cours_3.jpg)

### <a name="sequence5"></a> L'inscription d'un apprenant dans un cours :
Ce modèle sera représenté par une classe supplémentaire : Cours.

Il integre aussi le diagramme de sequence de la consultaion d'un cours.
![diS](https://github.com/Marouane124/Projet-UML/blob/63903767719b58cfbe3ec2b018adc23a25e7bbb8/Diagrammes/Diagramme%20de%20sequence%20Y/s'inscrire%20dasn%20un%20cours!s'inscrire%20dasn%20un%20cours!s'inscrire%20dasn%20un%20cours_4.jpg)

### <a name="Collaborateurs"></a> Collaborateurs
- **AIT KIKA Marouane**
- **CHALATI Yassine**
- GRP : **7**
  
