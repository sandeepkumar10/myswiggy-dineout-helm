myswiggy-helm

Installation steps:
example: dineout

helm add repo myswiggy https://sandeepkumar10.github.io/myswiggy-helm/
helm repo ls
helm repo update 
helm search repo myswiggy
helm install mydineout myswiggy/dineout
