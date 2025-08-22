# Prerequisites
#####
- JDK 11
- Maven 3
- MySQL 8 

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
# Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/db_backup.sql
- db_backup.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < db_backup.sql




use the terrform ifra we created using github iac profile
and and retriver the kubectl config frile from thier and deploy our appp using helm on that cluster name

we ucreate the ecr repo and build and docker file and push those image to ecr 
adn used those image and tag using ecr login and deployusing helm with lastest image in cluster

curl -H "Host: vprofile.bits.work.gd" http://a9688c2a219aa4538849ccab693ff3fa-576421d4a203aea1.elb.us-east-1.amazonaws.com

if dnbs bnot resolved do the host in ur windows 
a9688c2a219aa4538849ccab693ff3fa-576421d4a203aea1.elb.us-east-1.amazonaws.com  vprofile.bits.work.gd
3.234.78.178   vprofile.bits.work.gd

#clean the worklspace

use the aws configure with adminstrator access for aws 
aws eks update-kubeconfig --name vpro-ekss --region us-easet-1

kubectl delete -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.1.3/deploy/static/provider/aws/deploy.yaml

helm list
helm uninstall vprofile-stack

terraform init -backend-config="bucket=$vprofileactions431"

terraform init -backend-config="bucket =vprofileactions431"