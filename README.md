# ALB-ingress-example
Example of AWS ALB + Ingress controller

## Informatiom

The example usage of AWS Ingress alongside with EKS and Application Load Balancer.

The ingress creates 1 ALB, and two route53 records, for each record, used separate certificate, HTTP-to-HTTPS redirect and group.name for feature group of resources.

## 2048-game

2048-game used as a basis, more information you can find in the [AWS documentation](https://docs.aws.amazon.com/eks/latest/userguide/alb-ingress.html "Application load balancing on Amazon EKS")


