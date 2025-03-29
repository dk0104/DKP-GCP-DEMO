# toy-infrastructure
# Links und andere nuetzliche Hinweise
- [cert-manager](https://cert-manager.io/docs/tutorials/acme/http-validation/)
- [istio](https://cert-manager.io/docs/tutorials/acme/http-validation/)
- [argo-cd](https://argo-cd.readthedocs.io)

# Features

- Ausfahlsicherheit
- Autoscailing
- CICD
- Backup
- Authentication Manager
- Service Mesch
- Monitoring and Tracing 


# Ausfahlsicherheit

Zur einhaltung der AS wurde 3 master Node in 3 unterscheidlichen Zonen erstell somit ist die HW von eienanader getrennt.


# CICD
Teil der Aufgabe war enie funktionierende CICD Einheit vorgesehen , fuer diese Zwecke wurde [ArgoCD](https://argo-cd.readthedocs.io) ausgesucht. 

## [ArgoCD](https://argo-cd.readthedocs.io) Installation
### Helm Installation
ArgoCD installation wurde mittels Helm durchgefuehrt , die Values wurden nichet geendert , erstmal standrd Installation mal sehen was wir spaeter brauche.

###  TLS Configuration
Konfiguration mittels cert-manager.

### Argo CD CLI
- get argocd password

``` shell
 argocd admin initial-password -n argocd

```

### Access Argo CD API Server
### Login Using The CLI

``` shell
argocd login localhost:8000

```


















