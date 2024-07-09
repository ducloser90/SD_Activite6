# Activité Pratique N° 6 - Architectures Micro-services

## Partie 1.1 Rest API et Spring Data REST

- Spring Initializr pour configurer un nouveau projet Spring Boot

  <img width="1440" alt="Screenshot 2024-07-07 at 10 52 47 AM" src="https://github.com/ducloser90/SD_Activite6/assets/167253342/3235ef08-a066-405f-8d5d-1c0aac5c451d">

- Creation de l'entite BankAccount

  ![image](https://github.com/ducloser90/SD_Activite6/assets/167253342/ba3dfc77-48a3-4db7-a6cf-38211509b62f)

- Creation de l'interface BankAccountRepository

  ![image](https://github.com/ducloser90/SD_Activite6/assets/167253342/a865efae-6b35-4423-8e8f-65dd31de5cab)

- Configuration de fichier application.properties

  ![image](https://github.com/ducloser90/SD_Activite6/assets/167253342/a92ccd96-d5a1-49ac-93fe-83270a629d2e)

- L'ajout des accounts

  <img width="897" alt="Screenshot 2024-07-07 at 11 11 16 AM" src="https://github.com/ducloser90/SD_Activite6/assets/167253342/b0ea6680-c009-4695-9a2d-4b6370b48082">

  <img width="797" alt="Screenshot 2024-07-07 at 11 25 12 AM" src="https://github.com/ducloser90/SD_Activite6/assets/167253342/73dd7b48-dd0f-46ae-b98d-5f697f551e14">

- Création d'un Contrôleur REST

  <img width="841" alt="Screenshot 2024-07-07 at 11 42 51 AM" src="https://github.com/ducloser90/SD_Activite6/assets/167253342/7bbd8aed-2462-442c-948b-5c08315f1d80">

- Test :

  <img width="1440" alt="Screenshot 2024-07-07 at 11 54 19 AM" src="https://github.com/ducloser90/SD_Activite6/assets/167253342/ac1a3f30-f252-42d3-96bc-0664fe4f7eb5">

  <img width="1439" alt="Screenshot 2024-07-07 at 11 56 24 AM" src="https://github.com/ducloser90/SD_Activite6/assets/167253342/09dadc87-8bc7-4ab1-b1a5-693739036926">

- L'utilisation de la documentation OpenAPI (Swagger)

      - Ajouter les Dépendances
  
  ![image](https://github.com/ducloser90/SD_Activite6/assets/167253342/d4242135-9478-4eb6-954c-f4837f4b29f2)

  <img width="1438" alt="Screenshot 2024-07-07 at 1 21 10 PM" src="https://github.com/ducloser90/SD_Activite6/assets/167253342/a13996ea-bc32-4641-85ff-d772e4a4d940">

      - Test pour ajouter un compte

  <img width="1440" alt="Screenshot 2024-07-07 at 1 26 43 PM" src="https://github.com/ducloser90/SD_Activite6/assets/167253342/1499453c-757b-4ffd-ac00-e328e76229b4">

      - Resultat :

  <img width="1440" alt="Screenshot 2024-07-07 at 1 27 24 PM" src="https://github.com/ducloser90/SD_Activite6/assets/167253342/1fbe4091-5112-45c2-b39b-45e8ea251edb">

- Integrer Spring Data REST

    - Ajouter les Dépendances
 
  ![image](https://github.com/ducloser90/SD_Activite6/assets/167253342/1637f984-be94-4c3a-9fe0-69f2eb92d85b)

    - Ajouter l'annotation @RepositoryRestResource dans l'interface
 
  ![image](https://github.com/ducloser90/SD_Activite6/assets/167253342/584ae75f-b335-4b32-9cae-94f1329829d2)

    - Test :
      
  ![image](https://github.com/ducloser90/SD_Activite6/assets/167253342/4eab02b3-7924-4993-8892-35a71ed3ea0e)

- Creer une projection

  ![image](https://github.com/ducloser90/SD_Activite6/assets/167253342/27e03b45-918d-41e7-8bbb-c81268ac8efd)

  <img width="1440" alt="Screenshot 2024-07-07 at 2 09 43 PM" src="https://github.com/ducloser90/SD_Activite6/assets/167253342/471a1175-4269-45a2-b63d-d3443102e962">

- Creer une methode personnalisee

![image](https://github.com/ducloser90/SD_Activite6/assets/167253342/69ac5306-1d9f-476f-9d79-b5034c788055)

<img width="1440" alt="Screenshot 2024-07-07 at 1 51 46 PM" src="https://github.com/ducloser90/SD_Activite6/assets/167253342/488a0ad5-1574-4cd5-8ca6-e470d372407c">

- Autres Tests :

<img width="1440" alt="Screenshot 2024-07-07 at 4 06 48 PM" src="https://github.com/ducloser90/SD_Activite6/assets/167253342/a00f4654-d408-401e-bddd-a58e1b05a045">

## Partie 1.2 GraphQL

- Ajouter les Dépendances

  <img width="733" alt="Screenshot 2024-07-08 at 9 56 00 AM" src="https://github.com/ducloser90/SD_Activite6/assets/167253342/7cb95f20-1c24-4c79-ba51-b15491fe95fa">

- Schema GraphQL

  ![image](https://github.com/ducloser90/SD_Activite6/assets/167253342/274f4867-daa5-4f5a-a40b-fc39e389f9ae)

- Configuration GraphQL (classe)

  ![image](https://github.com/ducloser90/SD_Activite6/assets/167253342/aae543da-11a7-4678-bfdb-cb213e334e4b)

- Configurer le fichier application.properties pour activer l'interface graphiql

  ![image](https://github.com/ducloser90/SD_Activite6/assets/167253342/10ad978b-6c5b-46ad-b919-88f9d540a5b0)

  <img width="1440" alt="Screenshot 2024-07-08 at 10 16 48 AM" src="https://github.com/ducloser90/SD_Activite6/assets/167253342/f1a2ef50-349b-4766-a1f5-6d478cf6c60e">

- Tests :

  ![image](https://github.com/ducloser90/SD_Activite6/assets/167253342/5ffbf80e-b14c-4627-882a-4601d35a113e)

  <img width="1440" alt="Screenshot 2024-07-08 at 10 33 42 AM" src="https://github.com/ducloser90/SD_Activite6/assets/167253342/8fdaf040-0675-468b-8fd8-44ef9c60f863">

- Recuperer le message d'exception

  <img width="975" alt="Screenshot 2024-07-08 at 10 40 58 AM" src="https://github.com/ducloser90/SD_Activite6/assets/167253342/d771a48e-aa72-4ab4-9bc0-090d2a469ff8">

  <img width="1440" alt="Screenshot 2024-07-08 at 10 41 11 AM" src="https://github.com/ducloser90/SD_Activite6/assets/167253342/e384e78d-45d0-4499-8cc4-1a89393456e2">

- Une methode qui permet d'ajouter un compte (Mutation)

  <img width="1439" alt="Screenshot 2024-07-08 at 10 59 03 AM" src="https://github.com/ducloser90/SD_Activite6/assets/167253342/7227f77d-d60e-4c0a-a42b-d40f596dfc04">

- Requete parametree

  ![image](https://github.com/ducloser90/SD_Activite6/assets/167253342/80a4f320-42e2-4baa-a6c9-90fce1e5d819)

- Une methode updateAccount

  ![image](https://github.com/ducloser90/SD_Activite6/assets/167253342/06f18771-b426-42b3-ab80-27c4ae68cb7c)

- Une methode deleteAccount

  ![image](https://github.com/ducloser90/SD_Activite6/assets/167253342/29d6547e-5642-4ae1-9b09-b527a3e6693f)

- Les relations (Customer et BankAccount)

  ![image](https://github.com/ducloser90/SD_Activite6/assets/167253342/95e09b9f-f182-4876-88db-835384d44915)

- Tests:

  ![image](https://github.com/ducloser90/SD_Activite6/assets/167253342/a5c36ba9-9776-402c-ad7d-5127f8967eac)

  ![image](https://github.com/ducloser90/SD_Activite6/assets/167253342/99d4a89a-6130-4d07-a8c7-fb9c3088c683)












  






















