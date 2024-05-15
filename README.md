# Kubernetes-webapp

This is a simple Kubernetes project with ingress, service and deployment

1)2 Deployment files will create 2 pods with webapp1 and webapp2.
2)Service is created and linked to the pods throgh deployment labels.
3)Ingress is created with rules which forwards user request to the service and service distributed those request to the pods

![image](https://github.com/Chethankm21/Kubernetes-webapp/assets/96200923/5c096dd7-cd8a-45e0-87ba-a1ebb69daaad)

