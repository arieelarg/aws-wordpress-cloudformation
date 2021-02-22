aws-wordpress-cloudformation
Receta AWS: Wordpress con CloudFormation

Se busca crear una infraestructura escalable de alta disponibilidad con AWS para plataforma Wordpress

### Recursos:

1. EC2 - Centos 7 Linux 2
1. ELB
1. AutoScalingGroup
1. EFS - /wp-content
1. CloudFront para /wp-content
1. RDS - Aurora Cluster Write/Read


### Configuraciones

* Se realizaron configuraciones con el uso del comando "sed" en wp-config.php
* Mediante la creación de VH en httpd se implementa dirección de dominio del sitio Wordpress
* Posibilidad de aislar recursos mediante VPC dentro de una VPC mayor
* Para instalar wordpress se utiliza "wp-cli"
