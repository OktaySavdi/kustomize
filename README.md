# kustomize

[Kustomize](https://kustomize.io/)  is a great tool that allows developers to customise Kubernetes resources, including deployments and services, without changing the original YAML configuration files.

In most situations, projects are being developed at different stages and are transferred to different development environments, such as development, testing, production, etc. In such scenarios, changing the original YAML files at different stages could be an annoying situation for the entire team. But by using Kustomize, developers can get rid of this burden and make adjustments when necessary.

**# install**

curl -s "https://raw.githubusercontent.com/kubernetes-sigs/kustomize/master/hack/install_kustomize.sh"  | bash

**# build**

./kustomize build someapp/ 

./kustomize build someapp/ | kubectl apply -f -

**# references**

https://kubectl.docs.kubernetes.io/references/kustomize/

![image](https://user-images.githubusercontent.com/3519706/115189581-56dec500-a0ef-11eb-9e18-a3a3e8deb43e.png)
