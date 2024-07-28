exrcice9
S3 : Vous lancez une instance EC2 pour exécuter le script de backup du fichier archivé (contenant 4 fichiers). Vous créez un bucket S3 pour stocker les backups. Et arrêter une fois que nous atteignons 4 backups.

Configuration des permissions avec IAM : créez un rôle IAM avec des permissions d'accès complet à S3 (S3 Full Access) attaché à l'instance EC2.
1.Configurer aws cli dans notre ec2 suivre les étapes 
entrer les infration suivant:
AWS Access Key ID
AWS Secret Access Key
Default region name (par exemple, us-west-2)
Default output format (par exemple, json)
2.lister les backuts
3. creer le dossier et dedans placées 4fichier à compresser avec la commmande tar et presiser le nombre de backup 
4.utilisation de crontab -e pour que apres une minute l'on fasse le backup