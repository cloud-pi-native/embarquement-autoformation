#### Ce tutoriel permet de tester le déploiment d'un flux gitops et jouer avec les paramètres.
Cet example est décliné du cours de Techword with nana : https://www.youtube.com/watch?v=MeU5_k9ssrs

## Prérequis :
Disposer d'un cluster kubernetes avec un ingres controler d'installé. 
L'exemple a été testé avec traefik sur le cluster managé scaleway.
(a tester avec usage de l'hyperviseur light 'multipass' :  https://multipass.run/install + k3s )

```bash
# installation d'ArgoCD dans votre cluster k8s
kubectl create namespace argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml

# access ArgoCD UI ( vous pouvez aussi utiliser un outils plus convivial à installer sur le poste, tel que Lens https://k8slens.dev/ )
kubectl get svc -n argocd
kubectl port-forward svc/argocd-server 8080:443 -n argocd

# login with admin user and below token (as in documentation):
kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 --decode && echo

# you can change and delete init password

```
</br>

## Manipulation d'exemple du tutoriel 

tips : rappatrier l'ensemble de l'exemple en local afin de pouvoir pour jouer avec les valeurs. ( ou faite un fork de ce repository ) 
Ajouter dans votre fichier /etc/hosts le nom de domaine utilisé : 

```bash
sudo vi /etc/hosts
<enter password>
#ajouter à la fin du fichier la ligne suivante
<ip-of-your-cluster> echo.fake-domain.local
```

## jouez sur les valeurs et regarder le cluster se modifier directement dans l'interface
< instructions.... >




#### Links

* Config repo: [https://gitlab.com/nanuchi/argocd-app-config](https://gitlab.com/nanuchi/argocd-app-config)

* Docker repo: [https://hub.docker.com/repository/docker/nanajanashia/argocd-app](https://hub.docker.com/repository/docker/nanajanashia/argocd-app)

* Install ArgoCD: [https://argo-cd.readthedocs.io/en/stable/getting_started/#1-install-argo-cd](https://argo-cd.readthedocs.io/en/stable/getting_started/#1-install-argo-cd)

* Login to ArgoCD: [https://argo-cd.readthedocs.io/en/stable/getting_started/#4-login-using-the-cli](https://argo-cd.readthedocs.io/en/stable/getting_started/#4-login-using-the-cli)

* ArgoCD Configuration: [https://argo-cd.readthedocs.io/en/stable/operator-manual/declarative-setup/](https://argo-cd.readthedocs.io/en/stable/operator-manual/declarative-setup/)
