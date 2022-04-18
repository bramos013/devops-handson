## DevOps - HandsOn

Este repositório consiste em um lab DevOps, no qual busco aprimorar meus conhecimentos nas principais ferramentas de mercado.
Para o provisionamento das VM's utilizei o Vagrant como Hypervisor, onde todas utilizam CentOS 7 como S.O. Para a automação da 
infraestrutura foi utilizado o Ansible, posteriormente o ambiente foi todo versionado utilizando Git e integrado a ferramentas 
de suma importância, como Jenkins para realizar o CI/CD e o SonarQube para verificar a qualidade de código. Com o build da
pipeline concluído, foi possível armazenar a imagem do container no Nexus, utilizando ele como um registry Docker. Para finalizar
algumas ferramentas de monitoramento foram instaladas e integradas ao repositório para verificar se o ambiente continua disponível

<img src = "https://github.com/bramos013/devops-handson/blob/main/roadmap.jpeg" width = "600px" />

### Wiki

* <a href='https://github.com/bramos013/devops-handson/wiki/Vagrant' target='Vagrant'>Hypervisor - Vagrant </a>
* <a href='https://github.com/bramos013/devops-handson/wiki/Ansible' target='IaC'>IaC - Ansible </a>
* <a href='https://github.com/bramos013/devops-handson/wiki/Git' target='Git'>Versionamento - Git </a>
* <a href='https://github.com/bramos013/devops-handson/wiki/Docker' target='Docker'>Containers - Docker </a>
* <a href='https://github.com/bramos013/devops-handson/wiki/Docker-Compose' target='Docker-Compose'>Containers - Docker Compose </a>
* <a href='https://github.com/bramos013/devops-handson/wiki/Docker-Swarm' target='Docker-Swarm'>Containers - Docker Swarm </a>
* <a href='https://github.com/bramos013/devops-handson/wiki/SonarQube' target='SonarQube'>QA - SonarQube </a>
* <a href='https://github.com/bramos013/devops-handson/wiki/Jenkins' target='Jenkins'>CI/CD - Jenkins </a>
* <a href='https://github.com/bramos013/devops-handson/wiki/Nexus' target='Nexus'>Repo Manager - Nexus </a>
* <a href='https://github.com/bramos013/devops-handson/wiki/Prometheus' target='Prometheus'>Monitoramento - Prometheus </a>
* <a href='https://github.com/bramos013/devops-handson/wiki/Grafana' target='Grafana'>Monitoramento - Grafana </a>
 
### Observações

O objetivo deste repositório é voltado nas ferramentas DevOps, por este motivo utilizei aplicações já desenvolvidas.
