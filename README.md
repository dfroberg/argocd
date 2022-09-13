# Ingress

~~~bash
kubectl create ingress argocd-localhost --class=nginx --rule="argocd.cs.aml.ink/*=argocd-server:80" --rule="argocd.cs.aml.ink/*=argocd-server:443"
~~~
