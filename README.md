# kubeapp

To create secret for helm deployment  for local docker registry use below:
````
`kubectl create secret docker-registry regcred \
--docker-server=https://hub.docker.com/repositories/reddyy123 \
> --docker-username=reddyy123 \
> --docker-password=Vinod@12345 \
> --docker-email=pvreddy444@gmail.com`````

Regcred is the name of the secret.