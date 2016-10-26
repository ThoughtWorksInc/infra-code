# infra-code
TechRadar Academy em PoA - Cloud

## Sugestões

DevOps no contexto deste workshop

<img src="https://www.evernote.com/shard/s115/sh/3b31bc6b-9ac8-406d-9c22-49f877e40fe6/e3639865f82d7350/res/cf453a2f-8816-4552-a962-e11c4039a39e/skitch.png" alt="slide1" style="width: 400px;"/>
---
<img src="https://www.evernote.com/shard/s115/sh/635e07ab-81f0-41dc-8226-ccca4c77bb41/c192fe0fcd63b20a/res/c228a7aa-c595-4552-a08f-faacf1e62118/skitch.png" alt="slide2" style="width: 400px;"/>
---
<img src="https://www.evernote.com/shard/s115/sh/9b4814df-3a94-44a2-9e49-05760cdd265d/b51544406c33b1cb/res/6da8c115-f39c-4731-8362-418529ca5d85/skitch.png" alt="slide2" style="width: 400px;"/>
---

AWS API
* Diferentes formas de interação
  * Console Web
  * SDKs
    * Android, Javascript (Browser/Node), iOS, Java, .NET, PHP, Python, Ruby, Go, C++
  * CLI

Tradução - nomes dos serviços vs nomes fora da nuvem 
Lock-in

Infraestrutura como código - IaC - Infrastructure as Code
  * IaC repo organization
  * Automação
    * CloudFormation
    * Ansible
  * Autenticação
    * IAM e STS
    * Usuários
      * root vs IAM users
      * Federados (Identity federation)
    * LLC - Long Lived Credentials - Credenciais de Vida Longa
    * SLC - Short Lived Credentials - Credenciais de Vida Curta
  * Organizando código
    * por ambiente (dev/uat/prod)
  * Tests?

Modelo / Walking Skeleton

VPC
  * SDN
  * diferente de rede comum
  * não existe broadcast
  * VPC - AZ (Availability Zone)
    <img src="http://docs.aws.amazon.com/AmazonVPC/latest/UserGuide/images/vpc-diagram.png" alt="VPC e Availability Zone" style="width: 200px;"/>
  * Subnet
    <img src="http://docs.aws.amazon.com/AmazonVPC/latest/UserGuide/images/subnets-diagram.png" alt="Subnets" style="width: 200px;"/>

Armazenamento/Storage
  * EBS
  * EFS
  * S3

Responsabilidades compartilhadas
