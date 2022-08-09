# gitOps
## Advantage
* Consistency. Avoid missing deployment
* Continious Testing. e.g. dry run
* CD
* Version Control for microservices.

## git flow
* PR to sit

![prtosit](gitops-B.drawio.png)

* PR to master

![prtosit](gitops-A.drawio.png)

## Meeting Notes
* 請 DevOps 建立新 namespace 
* sit 仍需手動的項目：
  * upgrade image with latest tag, restart deployment
  * delete resource
  * change secret content, restart deployment
