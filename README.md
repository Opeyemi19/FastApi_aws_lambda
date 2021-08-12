# FastApi_aws_lambda

Les outils utilisés dans ce Tuto pour deployer ce projet:

- GitHub Action, pour faire le CI/CD
- AWS S3, pour stocker notre api zippé
- AWS Lambda, pour exécuter notre fichier main.py qui contient nos fonctions et qui a été zippé se trouvant sur sur S3.
- AWS API GATEWAY, qui nous permet d'avoir accès à notre API grace au service AWS Lambda.