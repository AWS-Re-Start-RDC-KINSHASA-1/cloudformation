#lancer une instance avec cloudformation avec load balancer et autoscalling grace à notre script .yml

Etape1 : lancer une  le service cloudformation et upload le fichier ec222.yml

![Capture d'écran 2024-03-04 171555](https://github.com/AWS-Re-Start-RDC-KINSHASA-1/cloudformation/assets/125833085/e5778764-ecbf-488f-944a-f2d2ceb260cf)

Etape 2 :donner le nom au service à lancer et appuyer sur next 

![Capture d'écran 2024-03-04 172310](https://github.com/AWS-Re-Start-RDC-KINSHASA-1/cloudformation/assets/125833085/102d4e86-fa38-4d6c-95eb-f79744261209)

Etape 3: laisser les valeurs par defaut et passer à next 

![Capture d'écran 2024-03-04 172634](https://github.com/AWS-Re-Start-RDC-KINSHASA-1/cloudformation/assets/125833085/eaafabb4-a266-4ed5-a88c-9e3db31fdf8b)

Etape 4: appuyer sur submit et lancer linistialisation du service

![Capture d'écran 2024-03-04 172901](https://github.com/AWS-Re-Start-RDC-KINSHASA-1/cloudformation/assets/125833085/0200aebf-87b0-42c4-a957-d535e42cc137)


# votre instance devrait afficher le resultat si bas, felicitation vous avez lancer une instance EC2 grace à cloud formation

![Capture d'écran 2024-03-04 173209](https://github.com/AWS-Re-Start-RDC-KINSHASA-1/cloudformation/assets/125833085/22098597-38de-4435-af8d-97b4165fbb09)

#Noter bien veuillez modifier le valeur des subnet, du vpc du security group  et de la clé ssh  pour qu'ils correspondentà vos informations

#Maintenant nous allons utiliser faire du pipeline avec code commit pour gerer le versionning de notre infra

Step 5: Lancer code commit et creer un repository

![Capture d'écran 2024-03-04 175233](https://github.com/AWS-Re-Start-RDC-KINSHASA-1/cloudformation/assets/125833085/3f75f507-ea24-44ab-b048-6e52658aeff7)

STep6 : Nommer le repository et creer 

![Capture d'écran 2024-03-04 175535](https://github.com/AWS-Re-Start-RDC-KINSHASA-1/cloudformation/assets/125833085/9c0a60ae-8662-4db7-aaad-f6d0946e5f23)

Step 7: Après avoir creer le repository, creer le file pour le commit changes.

![Capture d'écran 2024-03-04 180241](https://github.com/AWS-Re-Start-RDC-KINSHASA-1/cloudformation/assets/125833085/d775d140-c72a-4d60-9307-ad0e34f41436)

Step 8: upload le code contenu dans yml puis remplisser les informations.

![Capture d'écran 2024-03-04 180545](https://github.com/AWS-Re-Start-RDC-KINSHASA-1/cloudformation/assets/125833085/74c5c5ad-dcc2-4db0-9496-4d76962fd5fd)

Step9: votrefichier txt est crée , aller sur codepipeline et creer une pipeline

![Capture d'écran 2024-03-04 181128](https://github.com/AWS-Re-Start-RDC-KINSHASA-1/cloudformation/assets/125833085/9884167d-b22f-4d54-b66e-43749def4930)

Step10: donner un nom à votre pipeline et attacher un role 

![Capture d'écran 2024-03-04 181529](https://github.com/AWS-Re-Start-RDC-KINSHASA-1/cloudformation/assets/125833085/5e184987-f833-49d3-b692-aba500147960)

step11: choisisez comme source codecommit et attacher le repository recemment creer et comme branch-name "main"

![Capture d'écran 2024-03-04 182107](https://github.com/AWS-Re-Start-RDC-KINSHASA-1/cloudformation/assets/125833085/ef0d7789-aeaf-482d-990f-0bf2d75e8eab)

step 12: sauter cette etape avec un skip

![Capture d'écran 2024-03-04 182239](https://github.com/AWS-Re-Start-RDC-KINSHASA-1/cloudformation/assets/125833085/812aff97-7191-430b-8ae3-9329b8caa0b7)

step 13: choisir 







