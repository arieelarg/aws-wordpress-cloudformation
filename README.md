# aws-wordpress-cloudformation
Receta AWS: Wordpress con CloudFormation

## Se busca crear una infraestructura escalable de alta disponibilidad con AWS para plataforma Wordpress

# Recursos:

# EC2 - Centos 7 Linux 2
# ELB
# AutoScalingGroup
# EFS - /wp-content
# CloudFront para /wp-content
# RDS - Aurora Cluster Write/Read


# Configuraciones

# Se realizaron configuraciones con el uso del comando "sed" en wp-config.php
# Mediante la creación de VH en httpd se implementa dirección de dominio del sitio Wordpress
# Posibilidad de aislar recursos mediante VPC dentro de una VPC mayor
# Para instalar wordpress se utiliza "wp-cli"
